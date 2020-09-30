# Project title: GESCOVID19

La piattaforma **GESCOVID19** è composta da un gruppo di applicazioni create per gestire in tempo reale i processi di richiesta tamponi e di consultazione del relativo esito, la presa in carico dei pazienti in ospedale, le loro dimissioni e i trasferimenti a domicilio o in altre strutture per il post-ricovero, divulgare le segnalazioni in arrivo da MMG/PLS, gestire le acquisizioni straordinarie di personale, gestire il ciclo di approvvigionamento di servizi e presidi medici, tenere sotto controllo lo stato di occupazione dei letti suddivisi, per ogni struttura, tra terapia intensiva, sub-intensiva e ordinaria, nonché la consultazione dei casi positivi da parte dei sindaci, Prefettura e forze dell'ordine.
Un sistema gestionale completo e flessibile, realizzato dal CSI Piemonte con soluzioni tecnologiche open source in cui le informazioni sono fruibili
facilmente anche in mobilità e con dispositivi diversi.

# Getting started  
I moduli attualmente disponibili sono:  
  
| Componente | Descrizione |  
| ---------: | :---------- |  
| [**Admin Console**](https://github.com/regione-piemonte/gescovid19-adminconsole) | Consente al gestore del servizio di amministrare le utenze e i profili di accesso agli applicativi |  
| [**Admin Utenti**](https://github.com/regione-piemonte/gescovid19-adminutenti) | Console di amministrazione utenti/profili del sistema |  
| [**Dataview**](https://github.com/regione-piemonte/gescovid19-dataview) | Visualizzatore dati per Prefettura e Forze dell'Ordine |  
| [**Esito Tampone**](https://github.com/regione-piemonte/gescovid19-esitotampone) | Inserimento manuale esito tampone e data esito |  
| [**Admim Ricoveri**](https://github.com/regione-piemonte/gescovid19-adminricoveri) | Gestione pazienti ricoverati / dimessi dalla strutture sanitarie |  
| [**Gestione Strutture**](https://github.com/regione-piemonte/gescovid19-gestionestrutture) | Gestione strutture e posti letto |  
| [**Dashboard Posti Letto**](https://github.com/regione-piemonte/gescovid19-pazientiweb) | Dashboard sull'occupazione dei posti letto in tempo reale |  
|[**Gestione Pazienti Web**](https://github.com/regione-piemonte/gescovid19-gestionepazientiweb) | Inserimento dati anagrafici paziente, gestione della richiesta tampone, gestione del decorso della malattia, visualizzazione delle segnalazioni in arrivo da MMG/PLS |  
| [**Visura MMG Web**](https://github.com/regione-piemonte/gescovid19-pazientiweb) | Gestione degli assistiti di un MMG covid-positivi. Gestisce la segnalazione dei sospetti positivi al SISP/USCA territorialmente competente|  
| [**Visura Pazienti Web**](https://github.com/regione-piemonte/gescovid19-pazientiweb) | Visura pazienti covid-positivi per i sindaci dei Comuni |  
| [**Acquisti UDC**](https://github.com/regione-piemonte/gescovid19-acquistiudc) | Sistema di controllo unificato del fabbisogno di DPI. Gestisce l'acquisto centralizzato, il magazzino e logistica della distribuzione alle ASL |
| [**Acquisti API**](https://github.com/regione-piemonte/gescovid19-acquistiapi) | API di gestione acquisti centralizzati, magazzino e logistica della distribuzione alle ASL|
| [**HR Personale Sanitario ASR**](https://github.com/regione-piemonte/gescovi19-hrperssanitasr) | HR - Inserimento fabbisogni personale sanitario per le Aziende Sanitarie |
| [**HR Personale Sanitario UDC**](https://github.com/regione-piemonte/gescovid19-hrauthudc) | HR - Approvazione fabbisogni di personale |
| [**HR Personale Sanitario Dett**](https://github.com/regione-piemonte/gescovid19-hrinsdettpers) | HR - Inserimento figure professionali richieste |
| **Assenza medici** | Censimento personale sanitario assente per covid19 |  
| [**USCA**](https://github.com/regione-piemonte/gescovid19-uscammgapi) | Gestione degli USCA e interazioni con MMG. Gestisce il diario clinico del paziente |    
| [**RSA**](https://github.com/regione-piemonte/gescovid19-rsa) | Gestione delle RSA (posti letto, dipendenti, degenti, ...) |
| **HR Rilevazione** | Sistema di raccolta delle informazioni legate alle attività svolte dal personale delle ASL sul territorio come richiesto dagli indicatori ministeriali |
  
# Prerequisites  
## Software  
- [PHP 7.1](https://www.php.net)  
- [RedHat JBoss 6.4 GA](https://developers.redhat.com/products/eap/download)  
- [OpenJDK 8](https://openjdk.java.net/install/) o equivalenti  
- [PostgreSQL 9.6](https://www.postgresql.org/download/)  
- [Apache 2.4](https://www.apache.org)  
  
I linguaggi di programmazione utilizzati sono:  
  
### Front-end web:  
  
- VUE.js per le PWA (progressive webapp) adattive sui diversi dispositivi (mobile, web, ...)  
- PHP  
- PHPRunner (RAD per lo sviluppo rapido di applicazioni PHP)  
  
### API/rest:  
  
- Java/JDK 1.8  
  
### Batch:  
  
- Java  
- Pentaho  
- pl/pgsql  
  
Si rimanda ai file README.md delle singole componenti di prodotto per i dettagli specifici.  
  
# Configurations  
Nei file README.md delle singole componenti sono fornite informazioni per la configurazione  
  
# Installing  
Nei file README.md delle singole componenti sono fornite informazioni per la compilazione e installazione  
  
# Versioning  
Per la gestione del codice sorgente può essere utilizzata qualsiasi piattaforma di source versioning (p.es GIT, Subversion, ...) . Per il versionamento del codice sono utilizzate le regole del [Semantic Versioning](http://semver.org/).
  
# Authors  
Gli autori della piattaforma GESCOVID19 sono:  
  
- Paolo Arvati  
- Annalina Vitelli  
- Carlo Fortunato  
- Guido Coutandin  
- Alessandro Trombotto  
- Fabrizio Corsanego  
- Alessandro Franceschetti  
- Claudio Parodi  
- Davide Portinaro  
- Giuliano Iunco  
- Lorita Mansueto  
- Giuseppe Vezzetti  
- Alessandro Elia  
- Giuseppe Marino  
- Davide Corallo  
- Aura Malandra  
- Angela Carzedda  
- Barbara Tomassetti  
- Giovanni Tosto  
- Davide Elia  
- Simone Ferraris  
- Claude Nelson Ngwaka Ekango  
- Silvio Andrighetti Formaggini  
- Giovanni Pennone  
- Luca Maglione  
- Alessandro Napoli  
- Andrea Borrelli  
- Egidio Bosio  
- Raffaela Montuori
