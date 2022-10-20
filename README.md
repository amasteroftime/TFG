# TFG - Evolució de les actuacions policials a través de les dades de cossos de l’Estat
Treball de Final de Grau d'Enginyeria Informàtica, en l'especialitat d'Enginyeria del Software, a la FIB (UPC), consistent en la integració de fonts de dades obertes de cossos policials per a la seva visualització i anàlisi amb dashboards. Es fa especial ènfasi en com la pandèmia de Covid-19 ha pogut influir en el canvi de les dades.

El conjunt d'eines emprat per la elaboració del projecte, de les quals s'han fet servir les versions Open Source o s'ha cedit una versió lliure, han estat:
- Eina de dashboarding: [Metabase](https://www.metabase.com/)
- Base de dades: [PostgreSQL](https://www.postgresql.org/)
- Eina d'integració: [Pentaho Data Integration](https://sourceforge.net/projects/pentaho/files/Data%20Integration/)
- Hosting: [Departament d'Enginyeria de Serveis i Sistemes d'Informació - ESSI (UPC)](https://www.essi.upc.edu/ca)


A continuació es proporciona accés als dashboards creats per cada publicador de dades obertes (cal tenir accés a la [VPN de la UPC](https://serveistic.upc.edu/ca/upclink)):

## Mossos d'Esquadra (2011-2020)
Font: [Generalitat de Catalunya. Policia de la Generalitat - Mossos d'Esquadra](https://mossos.gencat.cat/ca/els_mossos_desquadra/indicadors_i_qualitat/dades_obertes/). (Última actualització: abril de 2021).
### [Fets delictius Generals i de Trànsit](http://wolverine.essi.upc.edu:8080/public/dashboard/a5381609-1ef2-45b2-afbf-41952ad85f5d#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Dades delinqüencials:**
  - Fets penals coneguts, fets coneguts resolts i detencions

- **Trànsit i mobilitat:**
  - Fets penals relatius al trànsit coneguts, fets coneguts resolts i detencions
  - Atestats d'accidents de trànsit

- **Activitat policial:**
  - Mitjana diària de patrulles policials

### [Fets delictius i Víctimes de Violència Masclista i Domèstica](http://wolverine.essi.upc.edu:8080/public/dashboard/37782f63-fd1f-4c46-8e4a-1f9233c1ad38#theme=night)
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

### [Denúncies tramitades a través d'Internet](http://wolverine.essi.upc.edu:8080/public/dashboard/2dbfb4df-51a6-4e47-a232-efab707a6a8f#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Dades delinqüencials:**
  - Denúncies per internet

- **Activitat policial:**
  - Temps espera per interposar denúncia

## Policía Municipal de Madrid (2014-2020)
Font: [Ayuntamiento de Madrid. Policía Municipal de Madrid](https://datos.madrid.es/sites/v/index.jsp?vgnextoid=bffff1d2a9fdb410VgnVCM2000000c205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD). (Última actualització: març de 2021).
### [Fets delictius Generals i de Trànsit](http://wolverine.essi.upc.edu:8080/public/dashboard/4fc13b4c-0977-4012-b69f-363c461b5d4d#theme=night)
Integra i creua dades de les següents fonts del catàleg:
- **Dades delinqüencials:**
  - Detinguts i investigats per motius (inclou Violència Masclista i Domèstica)
  - Detinguts i investigats per districtes
  - Incidències de Seguretat ciutadana

- **Trànsit i mobilitat**
  - Atestats d'accidents
  - Detinguts i investigats per controls d'alcoholèmia

### [Fets delictius relacionats amb l'Oci](http://wolverine.essi.upc.edu:8080/public/dashboard/23125a97-7989-4036-b28c-b421de0c8ce8#theme=night)
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
