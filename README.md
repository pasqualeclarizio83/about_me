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

È stato sviluppato un servizio di calcolo e validazione codici fiscali italiano con architettura client-server.
Il sistema implementa un motore di calcolo algoritmico backend che, tramite endpoint RESTful, espone due funzionalità 
principali:

    Generazione codice fiscale da parametri anagrafici tramite richiesta GET parametrica

    Validazione e reverse-lookup di codici fiscali esistenti

L'interfaccia frontend incorpora un sistema di autocompletamento dinamico (type-ahead) per i comuni tramite richieste 
AJAX asincrone, migliorando l'UX durante l'immissione dati. L'architettura prevede la persistenza dei dati anagrafici 
comunali su database MySQL, mentre la logica di calcolo è interamente gestita server-side in PHP, garantendo coerenza e sicurezza nei risultati.

Il servizio funziona sia come tool standalone tramite interfaccia web, sia come API provider per sistemi terzi 
attraverso contratti JSON standardizzati.

[Codice Fiscale con API](https://www.pasqualeclarizio.it/progetti/php_all/base/cf/)


### Competenze tecniche
* **Linguaggi:** C, Java, Pascal, Python, Javascript, PHP
* **Framework:** Laravel e Django
* **Database:** MySQL
* **Strumenti:** Git

### Formazione
* **Laurea in Informatica e Tecnologie per la Produzione del Software** ([ L-31 ])
  * Università degli Studi di [Bari]

### Interessi
* Sviluppo web, machine learning, open source.

### Contatti
* **Email:** [pascalclarizio@gmail.com]
