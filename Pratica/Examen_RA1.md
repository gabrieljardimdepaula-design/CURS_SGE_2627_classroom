# Examen pràctic RA1 — Identificació de sistemes ERP-CRM

## MÒDUL: Sistemes de Gestió Empresarial

RA1: Identifica sistemes de planificació de recursos empresarials i de gestió de relacions amb clients (ERP-CRM) reconeixent-ne les característiques i verificant la configuració del sistema informàtic.

## INSTRUCCIONS

 - Durada: **1 hora**.
 - Examen individual i sense apunts.
 - **Totes les respostes s'han de justificar.** Una resposta correcta sense justificació no puntua.
 - Les justificacions han de ser breus (1-3 línies), però han de fer servir els conceptes treballats a classe.
 - Puntuació total: **100 punts**.
 - **Obligatòri** l'ús d'OBS Studio per grabar tota la sessió de l'examen (test i pràctic).

| Pregunta |Puntuació | Temps orientatiu |
| :---- | :----: | :----: |
| 1. Classificació d'empreses | 25 | 15 min |
| 2. Tipus de programari empresarial i mòduls | 15 | 8 min |
| 3. Models de desplegament i llicències | 20 | 10 min |
| 4. Arquitectura, escalat i verificació | 20 | 12 min |
| 5. Cas integral: anàlisi d'una proposta | 20 | 15 min |

---

## PREGUNTA 1 — Classificació d'empreses (25 punts)

Llegeix la descripció d'aquestes cinc empreses:

**A) Bicicletes Pep Soler**
En Pep és l'únic propietari d'una botiga i taller de bicicletes a Vic. Té 3 treballadors i factura uns 280.000 € l'any. Els seus clients són particulars del poble.

**B) Fruites del Segrià SCCL**
38 socis treballadors que cultiven i cullen préssecs i pomes. Els socis prenen les decisions en assemblea i es reparteixen els beneficis segons la seva participació. Venen tota la producció a cadenes de supermercats de tot l'Estat. Volum de negoci: 7 M€. Balanç: 5 M€.

**C) Metal·lúrgica del Ripollès SA**
Fabrica peces d'acer per a fabricants de cotxes d'Espanya, França i Alemanya. Té 46 treballadors, un volum de negoci de 14 M€ i un balanç de 12 M€. El capital està dividit en accions en mans d'inversors privats.

**D) Aigües del Penedès SA**
Gestiona el subministrament d'aigua a les llars de 12 municipis de la comarca. El 55% del capital és del Consell Comarcal i el 45% d'una empresa privada, que cobra dividends cada any. Té 120 treballadors i factura 22 M€.

**E) Associació Rebost Solidari del Raval**
Recull aliments i els reparteix a famílies vulnerables del barri del Raval (Barcelona). Té 7 treballadors contractats i 40 voluntaris. Es finança amb donacions i subvencions, i tot el que ingressa es reinverteix en l'activitat.

**1.a)** (1,5 p) Omple la taula classificant cada empresa segons tots els criteris treballats. Si algun criteri no és aplicable o és dubtós, indica-ho i justifica-ho a l'apartat 1.d.

| Empresa | Sector | Mida | Propietat del capital | Àmbit | Destí dels beneficis | Forma jurídica | Model de negoci (B2B, B2C...) |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| A |terciario | micro|capital privado | |con animo de lucro |sociedad limitdada |B2C |
| B |primario |pequeña |capital privado | | con animo de lucro|coperativa | B2G|
| C |secundario |grande |capital privado | | con animo de lucro|sociedad ilimitada |b2b |
| D |terciario |grande |publico / privado | |con animo de lucro |capital abierto | B2C| 
| E |terciario |mediana |privado | |sin animo de lucro |ong| c2c|

**1.b)** Si només mirem el nombre de treballadors, l'empresa **C** seria petita. Quina mida li correspon realment? Justifica-ho amb la regla que s'aplica per determinar la mida d'una empresa.

**Resposta: **
es grande porque su balanço es mas grande que 10 mi euros. 

<br><br><br>

**1.c)** Per què és important per a una empresa saber en quina categoria de mida es troba? Dona dos motius.

**Resposta:
1 El tamaño de las empresas tienen franjas de obligaciones legales y  fiscales diferentes. 
2 El tamaño puede determinar cuales inceentivos, abonos y inversiones van a tener.
<br><br>

**1.d)** Quina de les cinc empreses t'ha costat més de classificar? En quin criteri i per què? Justifica la decisió que has pres.

**Resposta:**
La E, porque nao se como se enquadra exatamente en cual setor. he ponido terciario, poruqe entendo que es un servicio. La forma juridica y ambito tambien,  ya que no tienen lucro, entonces la enquadre como ONG. 
<br><br><br>

---

## PREGUNTA 2 — Tipus de programari empresarial i mòduls d'un ERP (15 punts)

**2.a)** Indica quin tipus de programari empresarial fa servir cada empresa (*aplicacions genèriques, programari a mida, programari estàndard* o *ERP*) i justifica-ho:

1. Una gestoria de 4 persones ho gestiona tot amb Excel, Word i Gmail.
2. Un laboratori va encarregar a una consultora un programa fet expressament per al seu procés de control de qualitat. Fa 14 mesos que hi treballen i encara apareixen errors. Cada canvi que demanen té un cost elevat.
3. Una botiga fa servir un programa de facturació, un altre per a les nòmines i un altre per a l'estoc, cadascun d'un fabricant diferent. Cada setmana algú ha de copiar dades d'un programa a l'altre manualment.
4. A una distribuïdora, quan un comercial registra una venda, l'estoc del magatzem i la comptabilitat s'actualitzen automàticament.

| Cas | Tipus de programari | Justificació |
| :---- | :---- | :---- |
| 1 |programa standard  |no hay inidicio en el enunciado que los progrmas standars como excel e word sean un problema o no esten satisfaziendo las necessidades del negocio. pero si es un problema, una aplicacion generica de gestoria va bien.  |
| 2 |programari a mitad |El fracaso en el funcionamiento del programa a medida durante 14 meses no tiene que ver con la necesidad del programa, es decir, con su propósito  sino con la forma en que se realizó; es decir, con su desarrollo, que resultó aparentemente precario. Un sector específico, dentro de un proceso que requiere un alto nivel de especialidad, fiabilidad y acountability, lo que implica asumir la responsabilidad por los daños que el producto pueda causar exige, efectivamente, un software a medida  auditable que les de controle sobre la producion y el produto final.  |
| 3 |erp |permite una gestion centralizada de la informacion |
| 4 |aplicacion generica | barata simples y eficiente para una demanda poco compleja en terminos de informacion.| 

**2.b)** Quina característica tècnica d'un ERP fa possible el que passa al cas 4?

**Resposta:**

<br>ERP como ODOO san modulares, y si puede associar modluos especificos entre si, ademas de escalar con el  negocio y ser de codico abierto lo que facilita la adopcion y la continuidad del contrato<br>

**2.c)** Una cadena de 3 fleques amb un obrador propi on es fa tot el pa vol implantar un ERP. Tria **4 mòduls** que necessitaria i explica per a què faria servir cadascun **en aquest negoci concret**.

**Resposta:**

<br><br><br><br>

---

## PREGUNTA 3 — Models de desplegament i llicències (20 punts)

**3.a)** Per a cada empresa, tria el model de desplegament més adequat (*on-premise, IaaS, PaaS* o *SaaS*) i justifica-ho. Cada model s'ha de fer servir **una sola vegada**.

1. Una gestoria de 8 persones sense cap informàtic. Volen accedir a l'ERP des de casa i pagar una quota mensual per usuari.
2. Una empresa de desenvolupament vol desplegar Odoo amb uns mòduls propis que ha programat. Volen centrar-se en el codi i no haver de gestionar ni el sistema operatiu ni els servidors.
3. Una empresa té un equip de sistemes que vol control total sobre el sistema operatiu i sobre la configuració de PostgreSQL. No vol comprar ni mantenir servidors físics.
4. Un hospital té l'obligació que les dades dels pacients no surtin de les seves instal·lacions i disposa d'un CPD propi amb personal tècnic.

| Cas | Model | Justificació |
| :---- | :---- | :---- |
| 1 |SAAS |Orientado al usuário final y facturado por usuário |
| 2 |PAAS |lo que necesita la empresa es la camada que conecta la infra estrucutra con la aplicacion. |
| 3 |IAAS |necesita contratar infraestructura y capacidad computacional si no quiere mantener servidores fisicos. |
| 4 |PAAS |el tecnico despliga una aplicacion para manipular los datos y la pone en una plataforma que gestione la infra servidor  +  banco.  |

**3.b)** Completa la taula indicant qui gestiona cada element, el **client** o el **proveïdor**:

| Element | IaaS | PaaS | SaaS |
| :---- | :---- | :---- | :---- |
| Aplicació (ERP) |usuario |usuario | empresa|
| Sistema operatiu |usuario | empresa| empresa|
| Servidors / virtualització |usuario  | empresa| empresa|

**3.c)** El gerent d'una PIME diu: *"Odoo Community té llicència de codi obert, per tant implantar-lo a la nostra empresa no ens costarà res."* És correcte? Raona-ho i indica quins costos hauria de tenir en compte.

**Resposta:**
No es corecto, hay que configurarla, despligarla, hacer los testes y mantenerla. 
<br><br><br>

---

## PREGUNTA 4 — Arquitectura, escalat i verificació de la instal·lació (20 punts)

**Logística Montseny SL** va instal·lar fa 10 anys un ERP als ordinadors de les oficines. Cada ordinador té el programa instal·lat i es connecta directament a una base de dades central que conté també la lògica de negoci. Ara l'empresa té 80 treballadors i 15 comercials que treballen fora de l'oficina amb el mòbil. El sistema va molt lent i, quan el servidor cau, tota l'empresa s'atura.

**4.a)**  Quina arquitectura té l'ERP actual? Justifica-ho.

**Resposta:**
una arquitetura de dos camadas, enq ue el usuario iteractua con la interface que interactua con  la logica del negocio esta en el servidor + banco de datos.
<br><br>

**4.b)**  Dona **dues raons** per les quals aquesta arquitectura ja no és adequada per a Logística Montseny.

**Resposta:**
Hay escalado los usuarios, lo que exige mucho del servidor + banco.
<br><br>

**4.c)** Proposa una nova arquitectura i descriu què hi hauria a cada capa **en el cas d'aquesta empresa**.

**Resposta:**
haria una arquiterua de 3 camadas,  separar la logica del negocio, la interface y el banco,  para que se pueda distribuir el consumo de recursos por mas servidores y mejorar la performance. 
<br><br><br>

**4.d)** El responsable d'informàtica proposa *"comprar més RAM i una CPU més potent per al servidor"*.
 - Quin tipus d'escalat és? 
 - Resoldria el problema de la lentitud? I el de *"quan el servidor cau, tota l'empresa s'atura"*? 
 - Quin tipus d'escalat proposaries a mitjà termini i quin inconvenient té? 

**Resposta:**
1- vertical
2 - No.
3 - Horizontal, pero es tiene un mantenimiento mas dificl y complejo. 
<br><br><br><br>

**4.e)** Abans d'instal·lar Odoo al nou servidor, un tècnic ha executat aquestes comandes. El fabricant demana com a mínim **Python 3.10**, **PostgreSQL instal·lat** i **10 GB lliures** en disc, i els ports **5432** i **8069** lliures.

```
$ cat /etc/os-release | grep PRETTY
PRETTY_NAME="Ubuntu 24.04.1 LTS"

$ python3 --version
Python 3.12.3

$ psql --version
Command 'psql' not found, but can be installed with:
sudo apt install postgresql-client-common

$ df -h /
Filesystem      Size  Used Avail Use% Mounted on
/dev/sda2        50G   48G  2,0G  96% /

$ sudo lsof -i :5432

$ sudo lsof -i :8069
COMMAND  PID  USER   FD   TYPE DEVICE SIZE/OFF NODE NAME
python3 2210 jordi    3u  IPv4  41237      0t0  TCP *:8069 (LISTEN)
```

1. Omple el checklist:

| Requisit | Valor obtingut | Compleix (Sí/No) |
| :---- | :---- | :---- |
| Sistema operatiu | | |
| Versió de Python | | |
| PostgreSQL instal·lat/versió | | |
| Espai lliure en disc | | |
| Port 5432 lliure | | |
| Port 8069 lliure | | |

2. Tria **una** de les incidències detectades i documenta-la amb aquests camps: *descripció del problema, missatge d'error o evidència, causa detectada i solució proposada*.

**Resposta:**

<br><br><br><br>

---

## PREGUNTA 5 — Cas integral: anàlisi d'una proposta (20 punts)

**VetCare Catalunya SL** és una cadena de 6 clíniques veterinàries repartides per Catalunya. Té 70 treballadors, un volum de negoci de 12 M€ i un balanç de 9 M€. A les clíniques es fan visites, operacions i vacunacions, i cada clínica té una petita botiga on es venen pinsos i medicaments. Cal guardar l'historial clínic de cada animal i enviar recordatoris de vacunes als propietaris.

Actualment cada clínica fa servir un programa diferent per a les visites, dues clíniques encara guarden els historials en paper, les nòmines es fan amb Excel i la comptabilitat la porta una gestoria externa.

Una consultora els ha fet aquesta proposta:

> 1. *"Com que el vostre balanç és inferior a 10 M€, sou una petita empresa i podeu optar a ajudes per a petites empreses."*  
> 2. *"Us recomanem un ERP vertical genèric com Odoo, que s'adapta a qualsevol sector."*
> 3. *"L'instal·larem amb MySQL, que és el SGBD que coneix el nostre equip."*
> 4. *"Muntarem una arquitectura de 2 capes, que és la més robusta per a empreses amb diverses seus i molts usuaris."*
> 5. *"El contractareu en mode SaaS, així el vostre informàtic podrà actualitzar el sistema operatiu del servidor quan ho cregui convenient."*
> 6. *"L'ERP és tan intuïtiu que no caldrà fer cap formació: el personal s'hi adaptarà sol."*

**5.a)** Detecta i corregeix **com a mínim 4 errors** de la proposta. Per a cada error, explica per què és incorrecte i què seria correcte.

**Resposta:**

 1. *"Com que el vostre balanç és inferior a 10 M€, sou una petita empresa i podeu optar a ajudes per a petites empreses."*  
  
 no. la condicion es, menos de 50 trabajodres o mas de 10 mi de euros de balanço.  

 4. *"Muntarem una arquitectura de 2 capes, que és la més robusta per a empreses amb diverses seus i molts usuaris."*
  No se aplica a la cuantidad de usuários y la distribuicion del uso. 

*"El contractareu en mode SaaS, així el vostre informàtic podrà actualitzar el sistema operatiu del servidor quan ho cregui convenient."
un SAAS no permite actulizar un sistema operativo  
  


> 4. *"Muntarem una arquitectura de 2 capes, que és la més robusta per a empreses amb diverses seus i molts usuaris."

<br><br><br><br><br><br>

**5.b)** Per a VetCare, és millor un ERP **vertical** o un d'**horitzontal**? Dona un avantatge i un inconvenient de cada opció **aplicats a aquest cas** i pren una decisió justificada.

**Resposta:**

<br><br><br><br>

**5.c)** Amb un CRM n'hi hauria prou? Indica quines necessitats de VetCare cobriria un CRM i quines no.

**Resposta:**

<br><br><br>

**5.d)** Identifica **3 reptes** concrets que trobarà VetCare en implantar l'ERP (de tipus diferents) i proposa una mesura per a cadascun.

**Resposta:**

<br><br><br><br>

**5.e)** Proposa **un indicador (KPI)** que permeti demostrar a la direcció, al cap d'un any, que l'ERP ha millorat el funcionament de l'empresa. Justifica per què és un bon indicador.

**Resposta:**

<br><br>
