# Pasquale Clarizio
## Software Developer

### Sommario
#### Lavoro
Sviluppatore python con esperienza nello sviluppo di applicazioni web tramite django e conoscenza base di django rest framework per la creazione di API. Competenze nell’analisi dei dati con le librerie python: pandas, numpy, scipy e nello sviluppo di modelli predittivi di base con XgBoost. Esperienza in documentazione e testing (frontend e API) con Playwright e k6 per test end-to-end e performance. Sviluppo di soluzioni per la domotica tramite QuickApp in LUA.

#### Competenze personali
API RESTful (o un Web Service) per la consultazione di dati geografici e amministrativi italiani.
Nello specifico, la tua piattaforma funge da endpoint di backend che permette di navigare gerarchicamente lungo la struttura territoriale italiana:
Gerarchia dei dati: Il sistema segue il flusso logico Regioni → Province (Città) → Comuni (Paesi).
Lookup Inverso: Permette la ricerca partendo dal CAP per identificare i comuni associati.
Formato Standard: L'uso del JSON la rende pronta per essere integrata in applicazioni web o mobile (ad esempio per popolare menu a tendina dinamici in un form di registrazione).
Identificazione univoca: Restituisce metadati essenziali come il Codice ISTAT (per fini statistici/amministrativi) e il CAP (per fini postali).

[API REGIONI](https://www.pasqualeclarizio.it/api_regioni/)

[Endpoint API Regioni](https://www.pasqualeclarizio.it/api_regioni/index.php?regione=Puglia)

[Endpoint API CAP](https://www.pasqualeclarizio.it/api_regioni/index.php?cap=70010)

Motore di Calcolo e Validazione del Codice Fiscale Italiano.
Nello specifico, ho progettato due funzionalità logiche distinte:
Generatore Deterministico con Spiegazione (Reverse Engineering Assistito):
Non ti limiti a fornire il risultato, ma esponi la logica algoritmica (estrazione consonanti/vocali da nome e cognome, conversione della data, recupero del codice catastale del comune e calcolo del carattere di controllo/omocodia).
L'output JSON lo rende perfetto per tool educativi o di debug per sviluppatori.
Validatore e Decodificatore (Parser):
Esegui il processo inverso per verificare la coerenza formale del codice.
Estrai i dati "incorporati" nel codice (data di nascita, sesso, comune di nascita) per confrontarli con database esterni (come quello della tua "1^ piattaforma").

[Codice Fiscale con API](https://www.pasqualeclarizio.it/progetti/cf)

[Endpoint API CF](https://www.pasqualeclarizio.it/progetti/cf/api/)

Microservizio di Generazione Documentale Dinamica (PDF-as-a-Service).
E' stato realizzato un Sistema Gestionale (ERP) modulare basato su API. Ecco cosa caratterizza questa terza parte:
Motore di Templating Dinamico: L'API non si limita a "pescare" file pronti, ma agisce come un generatore on-the-fly che trasforma dati grezzi (parametri URL) in documenti formali pronti per la validazione legale o commerciale.
Astrazione della Memorizzazione: Fornendo un URL di download all'interno di un oggetto JSON, separi la logica di creazione (backend) dalla fruizione dell'utente (frontend), permettendo al sistema di gestire file temporanei o archivi cloud.
Versatilità di Business: Coprendo l'intero ciclo di vendita, dal preventivo (pre-vendita) all'ordine (operativo), fino alla fattura/ricevuta (contabile).
Al momento è gratuito per una questione di mia convenzione! Non ha il servizio Token

[API Pdf as service](https://www.pasqualeclarizio.it/progetti/pdf/)

[Endpoint Pdf as service](https://www.pasqualeclarizio.it/progetti/pdf/api/api.php)

[Guida API per gestire il servizio fatture, ricevuta](https://www.pasqualeclarizio.it/progetti/pdf/guida_api.php)

Degli esempi:

[Crea un PDF con il preventivo e il nome del Cliente](https://www.pasqualeclarizio.it/progetti/pdf/api/api.php?tipo=preventivo&cliente=Pasquale Clarizio)

L'Api risponderà con un JSON in cui c'è il relativo PDF generato

Tutto questo è sempre in continua evoluazione


### Competenze tecniche
1. Sviluppo Backend e API Design
Architettura RESTful: Ovvero, come strutturare endpoint logici (index.php?parametro) per manipolare risorse (regioni, codici fiscali, documenti).
Gestione dei Dati: Capacità di strutturare e restituire dati nel formato standard JSON, fondamentale per l'interoperabilità tra sistemi diversi.
Logica Algoritmica Complessa: Ho implementato il calcolo del Codice Fiscale, che richiede la gestione di stringhe, estrazione di pattern (consonanti/vocali) e l'applicazione di algoritmi di controllo (carattere di verifica).
2. Manipolazione e Generazione di Documenti
PDF Generation: Ho applicato la trasformazione di dati dinamici (input dell'utente) in documenti statici formattati (PDF), gestendo con TCPDF e wordphp.
Automazione dei Processi: Ho automatizzato il ciclo di vita del documento: dalla ricezione dei parametri alla creazione fisica del file, fino alla generazione di un URL di download univoco.
3. Integrazione di Sistemi (Ecosistema Digitale)
Modularità: Non mi sono solo dedicato a creare un unico blocco monolitico, ma tre microservizi indipendenti che possono comunicare tra loro.
Data Validation: Ho cercato di estendere le mie competenze nella validazione e nel parsing di dati sensibili, garantendo che le informazioni (come il CF o i dati ISTAT) siano formali e coerenti.
4. Competenze di Business Logic
Dominio Fiscale/Amministrativo: Conoscenza delle gerarchie territoriali italiane e le regole della fatturazione/preventivazione, trasformando requisiti burocratici in soluzioni digitali.

### Formazione
* **Laurea in Informatica e Tecnologie per la Produzione del Software** ([ L-31 ])
  * Università degli Studi di [Bari]

### Interessi
* Sviluppo web, machine learning, open source.

### Contatti
* **Email:** [pascalclarizio@gmail.com]
