# Project title: GESCOVID19
La piattaforma **GESCOVID19** è un composito di applicazioni create per gestire tutta la fase dell'emergenza pandemica del virus covid-19, dal momento della segnalazione di un sospetto positivo, passando per la presa in carico fino alla guarigione, monitorando tutto il decorso del paziente covid-positivo.  
E' stata realizzata dal CSI-Piemonte con tecnologie open source, commissionata e finanziata dalla Regione Piemonte.  
  
# Getting started  
I moduli attualmente disponibili sono:  
  
| Componente | Descrizione |  
| ---------: | :---------- |  
| **AdminConsole** | Consente al gestore del servizio di amministrare le utenze e i profili di accesso agli applicativi |  
| **AdminUtenti** | Console di amministrazione utenti/profili del sistema |  
| **Dataview** | Visualizzatore dati per prefettura e forze dell'ordine |  
|**EsitoTampone** | Inserimento manuale esito tampone e data esito |  
| **AdmimRicoveri** | Gestione pazienti ricoverati / dimessi dalla strutture sanitarie |  
| **GestStrutture** | Gestione strutture e posti letto |  
| [**DashPostiLetto**](https://github.com/regione-piemonte/gescovid19-pazientiweb) | Dashboard sull'occupazione dei posti letto |  
|[**GestPazientiWeb**](https://github.com/regione-piemonte/gescovid19-gestionepazientiweb) | Inserimento dati anagrafici paziente e richiesta tampone |  
| [**VisuraMMGWeb**](https://github.com/regione-piemonte/gescovid19-pazientiweb) | Gestione pazienti covid-positivi o sospetti tali per Medici di base |  
| [**VisuraPazientiWeb**](https://github.com/regione-piemonte/gescovid19-pazientiweb) | Visura pazienti covid-positivi per i sindaci dei comuni |  
| **Acquisti** | Sistema di controllo unificato del fabbisogno di DPI, acquisto centralizzato, magazzino e logistica della distribuzione alle ASL |  
| **HRPersSanitASR** | HR - Inserimento fabbisogni personale sanitario per le Aziende Sanitarie |  
| **Assmedici** | Censimento personale sanitario assente per covid19 |  
| [**USCA**](https://github.com/regione-piemonte/gescovid19-uscammgapi) | Gestione degli USCA e interazioni con MMG |  
| **EsitiCollector**| Collettore esiti provenienti dal FSE. Raccoglie esiti tampone e sierologici in transito su FSE e li sposta sulla piattaforma GESCOVID19. Un batch esegue gli abbinamenti automatici degli esiti alle richieste tampone. |  
| **RSA** | Gestione delle RSA (posti letto, dipendenti, degenti, ...) |  
  
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
- pl-pg/sql  
  
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
