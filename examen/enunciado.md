# Test RA1 (Versió B) — Identificació de sistemes ERP-CRM

## AVALUACIÓ TEST
 - Cada pregunta correcta suma 1 punt.
 - Cada resposta incorrecta resta 0,33 punts.

Aquest test consta de 33 preguntes tipus test (opció múltiple, resposta única) basades exclusivament en la teoria i les activitats treballades al RA1:

---

**1.** Una empresa de 3 treballadors que ven directament a particulars des d'una única botiga local decideix implantar un ERP complet tipus SAP S/4HANA amb arquitectura de tres capes distribuïda en clústers. Segons els criteris de la teoria, aquesta decisió és:

    A) Adequada, perquè tot ERP ha de tenir sempre arquitectura distribuïda
    B) Obligatòria per llei
    C) Un possible sobredimensionament, ja que una arquitectura tan complexa i un ERP orientat a grans empreses no es correspon amb les necessitats d'una microempresa
    D) Irrellevant, l'arquitectura no depèn de la mida de l'empresa

**Resposta: C**

**2.** Per què es recomana una arquitectura de 3 capes en comptes de 2 capes per a l'ERP de TechNova?

    A) Perquè és més barata d'implementar
    B) Perquè no requereix base de dades
    C) Perquè només permet un usuari connectat alhora
    D) Perquè separa presentació, lògica de negoci i dades, facilitant escalabilitat, manteniment i seguretat en una empresa amb diversos departaments

**Resposta: D**

**3.** Segons els criteris de la teoria, com s'ha de classificar TechNova per mida, tenint 45 treballadors i sense dades que indiquin que supera els llindars de volum de negoci i balanç?

    A) Petita empresa, perquè té entre 10 i 49 treballadors i no consta que superi els límits en dos dels tres criteris
    B) Mitjana empresa, perquè està a prop del límit superior de petita empresa i té una estructura funcional completa
    C) Microempresa, perquè té menys de 50 treballadors
    D) Gran empresa, perquè té cinc departaments

**Resposta: A**

**4.** Quin seria l'error conceptual d'algú que afirma que "un sistema CRM i un sistema ERP són exactament el mateix, només canvia el nom"?

    A) Cap, són sinònims exactes
    B) Un ERP integra tots els processos i dades de l'empresa (finances, producció, RRHH, etc.) mentre que un CRM se centra específicament en la gestió de la relació amb els clients (comercial, màrqueting, postvenda), i de fet el CRM pot ser un mòdul dins d'un ERP
    C) El CRM sempre és més gran que l'ERP
    D) L'ERP només serveix per a vendes

**Resposta: B**

**5.** Un tècnic proposa per a una gran multinacional (500+ empleats, diverses seus) mantenir una única instància de base de dades sense rèpliques ni clústers "per simplicitat, com a l'etapa 1 de l'exemple d'escalat". Per què aquesta proposta és inadequada segons l'exemple de la teoria?

    A) Perquè és exactament el que recomana la teoria per a grans empreses
    B) Perquè les bases de dades úniques no existeixen
    C) Perquè la teoria mostra que a l'etapa de gran empresa cal una arquitectura de base de dades distribuïda (clústers, rèpliques, alta disponibilitat) per suportar milers de transaccions en temps real, cosa que una única instància no garanteix
    D) Perquè les multinacionals no necessiten bases de dades

**Resposta:C**

**6.** Segons el sector de l'activitat, una empresa de pesca es classifica com:

    A) Sector primari
    B) Sector secundari
    C) Sector terciari
    D) Sector quaternari

**Resposta: A**

**7.** Quina seria la conseqüència més probable de saltar-se el pas de "proves de funcionament" abans de posar en producció un ERP-CRM recentment instal·lat, segons l'ordre de passos de la teoria?

    A) Cap, aquest pas és opcional i no afecta res
    B) Es podrien detectar en producció (amb dades i usuaris reals) errors de configuració que s'haurien pogut trobar i corregir abans, en un entorn controlat
    C) El sistema es tornaria automàticament més ràpid
    D) Els mòduls s'instal·larien sols

**Resposta: B**

**8.** Oracle NetSuite és un ERP:

    A) On-premise exclusivament
    B) De codi obert
    C) Natiu al núvol (SaaS)
    D) Especialitzat en retail i distribució

**Resposta: C**

**9.** Un ERP horitzontal, segons la teoria, es caracteritza per:

    A) Estar dissenyat només per a hospitals
    B) Ser genèric i modular, adaptable a qualsevol tipus d'empresa
    C) Estar especialitzat en un únic sector regulat
    D) No incloure mòduls de comptabilitat

**Resposta: B**

**10.** Quina diferència de control té l'usuari entre PaaS i IaaS segons la teoria?

    A) En IaaS l'usuari no té cap control sobre res
    B) En PaaS l'usuari no té cap control sobre la infraestructura però sí control parcial sobre la plataforma, mentre en IaaS té control total sobre la plataforma (SO inclòs) però no sobre el maquinari físic
    C) PaaS i IaaS donen exactament el mateix nivell de control
    D) En PaaS l'usuari controla el maquinari físic

**Resposta: A**

**11.** Segons l'activitat 1.4, quin port utilitza per defecte Odoo?

    A) 5432
    B) 80
    C) 8069
    D) 443

**Resposta: A**

**12.** Segons la teoria, quin és un avantatge dels ERP?

    A) Cost d'adquisició reduït sempre
    B) No requereix formació dels treballadors
    C) Una única instal·lació i manteniment
    D) Elimina completament el risc de ciberatacs

**Resposta: C**

**13.** Per què es descarta Salesforce o SuiteCRM en solitari com a solució per a TechNova?

    A) Perquè no són sistemes CRM reals
    B) Perquè no tenen versió gratuïta
    C) Perquè no funcionen amb navegador web
    D) Perquè només cobririen la part comercial (Vendes/ Màrqueting) i no la resta de departaments (RRHH, Administració, Desenvolupament)

**Resposta: D**

**14.** HubSpot CRM es caracteritza, segons la teoria, per seguir un model:

    A) Freemium
    B) Propietari pur de pagament
    C) De codi obert gratuït
    D) Exclusivament on-premise

**Resposta: A**

**15.** Una limitació de l'escalat horitzontal esmentada a la teoria és:

    A) Té un límit físic molt baix
    B) Requereix una arquitectura més complexa (balancejadors, sincronització, rèplica)
    C) Si el servidor falla, tot el sistema cau
    D) No millora mai el rendiment

**Resposta: B**

**16.** Si l'ERP connecta els departaments de Vendes i Desenvolupament, per què "projectes lliurats a temps" és un KPI més útil que "nombre de reunions internes"?

    A) Perquè les reunions no es poden comptar
    B) Perquè Desenvolupament no té projectes
    C) Perquè Vendes no influeix en els terminis de lliurament
    D) Perquè mesura directament el resultat de la coordinació entre ambdós departaments, mentre que el nombre de reunions és només una activitat, no un resultat

**Resposta: D**

**17.** Si dues empreses tenen la mateixa mida (45 empleats) però una és una consultora de software B2B (com TechNova) i l'altra és una botiga online B2C amb milers de comandes diàries, per què podria no ser vàlid recomanar el mateix ERP i la mateixa arquitectura a totes dues sense matisos?

    A) Perquè la mida és l'únic factor rellevant en qualsevol cas
    B) Perquè les botigues online no poden usar ERP
    C) Perquè els requisits tècnics (volum de transaccions, necessitat d'escalat, tipus de mòduls prioritaris com TPV/logística en el cas B2C) depenen també de l'activitat i del volum d'operacions, no només del nombre d'empleats
    D) Perquè B2B i B2C sempre necessiten el mateix programari

**Resposta: C**

**18.** Una empresa com TechNova (45 empleats, PIME, pressupost ajustat) rep la proposta de contractar Salesforce Sales Cloud com a únic sistema per digitalitzar TOTA l'empresa (RRHH, comptabilitat, projectes i vendes). Quin és l'error principal d'aquesta proposta, segons el raonament aplicat al cas?

    A) Salesforce és fonamentalment un CRM (orientat a vendes/relació amb clients) i no cobriria per si sol RRHH, comptabilitat ni gestió de projectes, que és el que necessita realment TechNova
    B) Salesforce no existeix en format SaaS
    C) Salesforce només funciona amb PostgreSQL
    D) Salesforce no permet integrar-se amb cap altre sistema

**Resposta: A**

**19.** Per què es diu que en una arquitectura de tres capes es facilita la seguretat en comparació amb la de dues capes?

    A) Perquè cada capa es pot reforçar de manera independent (p. ex. xifratge a la base de dades, tallafocs a la lògica)
    B) Perquè no cal connexió a internet
    C) Perquè elimina la necessitat d'un servidor
    D) Perquè no hi ha usuaris connectats

**Resposta: A**

**20.** Quina relació hi ha entre la mida de TechNova i el pressupost disponible a l'hora de triar entre Odoo Community i SAP Business One?

    A) La mida no influeix mai en la tria d'ERP
    B) SAP Business One és gratuït per a empreses petites
    C) El pressupost només afecta el SGBD, no l'ERP
    D) Com a PIME amb pressupost ajustat, una solució de cost inicial baix com Odoo Community s'ajusta millor que una solució com SAP, molt més cara per a aquest volum

**Resposta: D**

**21.** Una startup de 5 persones que ofereix el seu propi programari com a servei web (sense que el client hagi d'instal·lar res) a altres empreses és, respecte al model de monetització que ELLA MATEIXA ofereix als seus clients:

    A) Un proveïdor IaaS
    B) Un proveïdor PaaS
    C) Un proveïdor SaaS
    D) Un proveïdor on-premise

**Resposta: C**

**22.** Un ERP integra les dades i processos de l'empresa mitjançant:

    A) Diversos gestors de bases de dades independents per mòdul
    B) Fulls de càlcul enllaçats
    C) Un únic sistema d'emmagatzematge/gestor de base de dades compartit
    D) Un servidor de correu centralitzat

**Resposta: A**

**23.** Per què instal·lar un ERP amb un SGBD no oficialment suportat pel fabricant pot comportar pèrdua de suport tècnic?

    A) Perquè el fabricant sempre dona suport a qualsevol configuració
    B) Perquè els SGBD no suportats són sempre gratuïts
    C) Perquè no afecta el suport, només el rendiment
    D) Perquè el fabricant o partner de manteniment pot negar-se a donar suport si la instal·lació no segueix la configuració oficial

**Resposta:D**

**24.** En una arquitectura de dues capes (two-tier), els components són:

    A) Presentació, lògica de negoci i dades
    B) Només base de dades
    C) Client i servidor
    D) Presentació i dades, sense lògica de negoci

**Resposta: C**

**25.** Dissenyant una solució per a una empresa fictícia de 8 treballadors (microempresa) que ven roba online directament a particulars (B2C) i vol el mínim manteniment tècnic possible, quina combinació és més coherent amb els criteris aplicats a TechNova?

    A) SAP S/4HANA on-premise amb arquitectura de dos servidors propis
    B) Un desenvolupament de programari a mida des de zero
    C) Un ERP-CRM lleuger en format SaaS, sense necessitat de gestionar SO ni SGBD propis
    D) IaaS amb gestió manual de tota la infraestructura

**Resposta: C**

**26.** Què significa RPC segons la teoria?

    A) Remote Process Control
    B) Remote Procedure Call
    C) Rapid Process Configuration
    D) Remote Program Connection

**Resposta: B**

**27.** En l'exemple d'escalat d'un ERP de 3 capes de la teoria, què diferencia principalment l'etapa 3 (gran empresa) de l'etapa 1 (petita empresa)?

    A) L'etapa 3 elimina la capa de dades
    B) L'etapa 3 utilitza una arquitectura distribuïda amb clústers i rèpliques per suportar milers de transaccions, mentre l'etapa 1 té una sola instància de base de dades
    C) L'etapa 1 no té capa de presentació
    D) No hi ha diferències significatives

**Resposta: B**

**28.** Si una empresa com TechNova decidís, en comptes d'Odoo, apostar per un desenvolupament de programari a mida fet pel seu propi departament de Desenvolupament (25 persones) per digitalitzar tots els processos, quin inconvenient clau de la teoria sobre "programari a mida" hauria de tenir en compte abans de decidir-ho?

    A) Cap, ja tenen l'equip tècnic
    B) Que el programari a mida sempre és més barat que un ERP estàndard
    C) Que el programari a mida no es pot fer mai en local
    D) Que el programa no s'ha provat mai (a diferència d'un ERP estàndard ja testat en molts clients) i qualsevol canvi futur implicarà cost de desenvolupament intern, allunyant l'equip de la seva feina principal (projectes de clients)

**Resposta: D**

**29.** Microsoft Dynamics 365 utilitza com a SGBD:

    A) Microsoft SQL Server
    B) PostgreSQL
    C) MySQL/MariaDB
    D) Oracle Database

**Resposta: A**

**30.** Un grup d'alumnes documenta la seva incidència de l'activitat 1.5 dient només: "Python no anava bé, el vam actualitzar i ja està." Segons els criteris de correcció de l'activitat 1.5, aquesta resposta:

    A) És perfecta perquè és breu i clara
    B) No cal documentar mai incidències de Python
    C) Hauria de anar acompanyada d'una factura
    D) Es penalitzaria per ser massa genèrica, sense passos de reproducció, missatge d'error concret ni causa detectada

**Resposta: D**

**31.** En el model SaaS, l'usuari:

    A) Té control total sobre la infraestructura
    B) No té cap control sobre l'aplicació, la plataforma ni la infraestructura
    C) Té control parcial sobre la plataforma
    D) Ha d'instal·lar el sistema operatiu

**Resposta: B**

**32.** Quin tipus de programari empresarial es caracteritza per adaptar-se perfectament a les necessitats de l'empresa però té una implementació llarga i propensa a errors?

    A) Programari a mida
    B) Aplicacions genèriques
    C) Programari estàndard
    D) Sistemes ERP

**Resposta: A**

**33.** Per què es considera que el tipus de software empresarial "programari a mida" té un cost de manteniment potencialment elevat?

    A) Perquè és programari ja provat i estandarditzat
    B) Perquè qualsevol canvi implica modificar el programari fet expressament per a l'empresa, sense poder-lo reutilitzar d'una base ja provada
    C) Perquè no es pot instal·lar en local
    D) Perquè sempre requereix un ERP addicional

**Resposta: B**
