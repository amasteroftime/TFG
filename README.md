# TFG - Evolució de les actuacions policials a través de les dades de cossos de l’Estat
Treball de Final de Grau d'Enginyeria Informàtica, en l'especialitat d'Enginyeria del Software, a la FIB (UPC), consistent en la integració de fonts de dades obertes de cossos policials per a la seva visualització i anàlisi amb dashboards. Es fa especial ènfasi en com la pandèmia de Covid-19 ha pogut influir en el canvi de les dades.

El conjunt d'eines emprat per la elaboració del projecte, de les quals s'han fet servir les versions Open Source o s'ha cedit una versió lliure, han estat:
- Eina de dashboarding: [Metabase](https://www.metabase.com/)
- Base de dades: [PostgreSQL](https://www.postgresql.org/)
- Eina d'integració: [Pentaho Data Integration](https://sourceforge.net/projects/pentaho/files/Data%20Integration/)
- Hosting: [Virtech - Gentilesa de l'InLab de la FIB (UPC)](https://inlab.fib.upc.edu/es/servicio-de-cloud-docente-de-la-fib-virtech)


A continuació es proporciona accés als dashboards creats per cada publicador de dades obertes:

## Mossos d'Esquadra (2011-2020)
Font: [Generalitat de Catalunya. Policia de la Generalitat - Mossos d'Esquadra](https://mossos.gencat.cat/ca/els_mossos_desquadra/indicadors_i_qualitat/dades_obertes/). (Última actualització: abril de 2021).
### [Fets delictius Generals i de Trànsit](http://nattech.fib.upc.edu:40340/public/dashboard/30e41269-da10-4061-b334-7d4f42c6ad6b#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Dades delinqüencials:**
  - Fets penals coneguts, fets coneguts resolts i detencions

- **Trànsit i mobilitat:**
  - Fets penals relatius al trànsit coneguts, fets coneguts resolts i detencions
  - Atestats d'accidents de trànsit

- **Activitat policial:**
  - Mitjana diària de patrulles policials

### [Fets delictius i Víctimes de Violència Masclista i Domèstica](http://nattech.fib.upc.edu:40340/public/dashboard/379d8ae8-62ab-4646-9887-331256a33831#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Violència masclista i domèstica:**
  - Víctimes violència masclista - Àmbit familiar
  - Víctimes violència masclista - Àmbit parella
  - Víctimes violència masclista - Àmbit social/comunitari-violència sexual
  - Víctimes de violència domèstica
  - Fets, denúncies i trencaments de condemna per violència masclista
  - Fets, denúncies i trencaments de condemna per violència domèstica

- **Dades delinqüencials:**
  - Fets penals coneguts, fets coneguts resolts i detencions

- **Trànsit i mobilitat:**
  - Fets penals relatius al trànsit coneguts, fets coneguts resolts i detencions

### [Denúncies tramitades a través d'Internet](http://nattech.fib.upc.edu:40340/public/dashboard/e97c26b2-d884-4154-878d-09620ba91e04#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Dades delinqüencials:**
  - Denúncies per internet

- **Activitat policial:**
  - Temps espera per interposar denúncia

## Policía Municipal de Madrid (2014-2020)
Font: [Ayuntamiento de Madrid. Policía Municipal de Madrid](https://datos.madrid.es/sites/v/index.jsp?vgnextoid=bffff1d2a9fdb410VgnVCM2000000c205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD). (Última actualització: març de 2021).
### [Fets delictius Generals i de Trànsit](http://nattech.fib.upc.edu:40340/public/dashboard/37d1a7f4-5b69-4af8-9f10-ec449ae21ffc#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Dades delinqüencials:**
  - Detinguts i investigats per motius (inclou Violència Masclista i Domèstica)
  - Detinguts i investigats per districtes
  - Incidències de Seguretat ciutadana

- **Trànsit i mobilitat**
  - Atestats d'accidents
  - Detinguts i investigats per controls d'alcoholèmia

### [Fets delictius relacionats amb l'Oci](http://nattech.fib.upc.edu:40340/public/dashboard/e90c4c77-8aae-4be7-9085-3c26414e280d#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Dades delinqüencials:**
  - Detinguts i investigats per motius
  - Detinguts i investigats per districtes
  - Consum d'alcohol a la via pública
  - Actes i denúncies per venda ambulant
  - Inspeccions i actuacions a locals d'espectacles públics i activitats recreatives

- **Trànsit i mobilitat**
  - Atestats d'accidents
  - Detinguts i investigats per controls d'alcoholèmia
