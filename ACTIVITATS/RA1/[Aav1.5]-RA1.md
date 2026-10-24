# Informe de operaciones — Actividad 1.4

## 1. Operaciones realizadas

### Operación 1 — Comprobar la versión de Python
**Comando/acción ejecutada:** `python --version`, `python3 --version` y `py --version`.  
**Resultado obtenido:** Las tres comprobaciones devolvieron Python 3.14.4, versión demasiado reciente para Odoo, que normalmente se ejecuta con 3.10–3.12.  
**Fecha:** 18/10/2026, entre las 20:45 y las 20:50

----------------------------------------------------

### Operación 2 — Comprobar si PostgreSQL ya estaba instalado
**Comando/acción ejecutada:** `psql --version`, comprobación de la carpeta de instalación y búsqueda del servicio "postgres".  
**Resultado obtenido:** PostgreSQL no estaba instalado: ni el comando psql ni el servicio existían en el sistema.  
**Fecha:** 18/10/2026, entre las 20:45 y las 20:50

----------------------------------------------------

### Operación 3 — Comprobar el espacio libre en disco
**Comando/acción ejecutada:** `Get-PSDrive` para consultar el espacio usado y libre de la unidad C:.  
**Resultado obtenido:** Unidad C: con 291,1 GB libres (661,8 GB en uso). Espacio de sobra para la instalación.  
**Fecha:** 18/10/2026, entre las 20:45 y las 20:50

----------------------------------------------------

### Operación 4 — Comprobar los puertos 5432 y 8069 antes de instalar
**Comando/acción ejecutada:** `netstat` filtrado por los puertos 5432 y 8069.  
**Resultado obtenido:** Los puertos 5432 y 8069 estaban libres sin ningun proceso escuchando en ellos  
**Fecha:** 18/10/2026, entre las 20:45 y las 20:50

----------------------------------------------------

### Operación 5 — Instalar PostgreSQL 17
**Comando/acción ejecutada:** `winget install` de PostgreSQL 17 en modo desatendido.  
**Resultado obtenido:** La instalacion descargó la versión 17.11-5 pero fallo al crear el cluster con código de salida 1.  
**Fecha:** 18/10/2026, entre las 20:45 y 21:00

----------------------------------------------------

### Operación 6 — Crear el clúster, arrancar PostgreSQL y validar la conexión
**Comando/acción ejecutada:** `initdb` para crear el cluster en una carpeta del usuario, `pg_ctl start` para arrancar el servidor y `psql` para comprobar la version.  
**Resultado obtenido:** El cluster se creó correctamente el servidor arrancó y quedó escuchando en el puerto 5432  
**Fecha:** 18/10/2026, entre las 20:55 y 21:00

----------------------------------------------------

### Operación 7 — Revisar de nuevo el puerto 8069
**Comando/acción ejecutada:** `netstat` filtrado por el puerto 8069.  
**Resultado obtenido:** El puerto 8069 seguía libre, sin ningún proceso escuchando tras la instalación.  
**Fecha:** 18/10/2026, entre las 20:55 y las 21:00

### Resumen de la checklist final

| Requisito | Valor obtenido | Cumple (Sí/No) |
|---|---|---|
| Sistema operativo | Windows 11 Home, versión 10.0.26300 | Sí |
| Versión de Python | Python 3.14.4 | No |
| PostgreSQL instalado/versión | PostgreSQL 17.11 | Sí |
| Espacio libre en disco | 291,1 GB libres en C: | Sí |
| Puerto 5432 libre | Libre antes de instalar; ahora lo usa PostgreSQL | Sí |
| Puerto 8069 libre | Libre | Sí |

---

## 2. Documentación de incidencias

### Ficha de incidencia 1 — La instalación de PostgreSQL falla al crear el clúster

| Campo | Detalle |
|---|---|
| **Fecha y hora** | 18/10/2026, entre las 20:50 y las 21:00 |
| **Descripción del problema** | Winget copió los archivos de PostgreSQL, pero initdb falló al inicializar el clúster. |
| **Pasos para reproducirlo** | Instalar PostgreSQL 17 con winget, sin permisos de administrador. |
| **Mensaje de error obtenido** | `El instalador falló con el código de salida: 1`. En el log del instalador: `Failed to initialise the database cluster with initdb`. Efecto añadido: `psql` no se reconocía porque la carpeta `bin` no estaba en el PATH. |
| **Causa detectada** | Faltaban permisos de administrador, necesarios para crear el servicio y el clúster. |
| **Solución aplicada** | Se añadió la carpeta `bin` de PostgreSQL al PATH, se borró la carpeta `data` incompleta, se creó el clúster a mano en una carpeta del usuario con `initdb` y se arrancó el servidor con `pg_ctl`. |
| **Limitación** | El servidor corre como proceso de usuario, por lo que hay que arrancarlo a mano tras cada reinicio. |
| **Solución definitiva propuesta** | Reinstalar como administrador o registrar el servicio con pg_ctl. |

---

###  Ficha de incidencia 2, sin resolver — Versión de Python demasiado reciente

| Campo | Detalle |
|---|---|
| **Fecha y hora** | 18/10/2026, entre las 20:45 y 20:50 |
| **Descripción del problema** | Python 3.14.4 esta instalado pero Odoo suele ejecutarse con versiones 3.10–3.12. Es una valoración propia: la incompatibilidad no se ha comprobado con la documentacion oficial de Odoo |
| **Pasos para reproducirlo** | Ejecutar `python --version` en un terminal |
| **Mensaje de error obtenido** | Ninguno; el comando funciona correctamente. |
| **Causa detectada** | Se instaló la versión más reciente, sin validar compatibilidad con Odoo. |
| **Solución propuesta, no aplicada** | Crear un entorno virtual con Python 3.12 para instalar Odoo. |
