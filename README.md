# React Starter Pack

Per creare un nuovo progetto react tramite `create-react-app` è necessario seguire diversi step.

### 1) Creare il progetto:

    npx create-react-app nome-progetto

### 2) Entrare nella cartella appena creata

    cd nome-progetto
    
### 3) Avviare l'applicazione

    npm start

## Struttura del progetto

Dopo aver creato un nuovo progetto React con Create React App, troverai diversi file e cartelle nella directory del progetto. Ecco una descrizione semplice dei file e delle cartelle principali:

### Directory node_modules

**node_modules/**: Questa cartella contiene tutti i pacchetti e le dipendenze installate tramite npm. Viene creata automaticamente e non dovresti modificarla manualmente.

### File nella directory public

**public/**: Questa cartella contiene file statici che verranno serviti direttamente dal server. Alcuni dei file principali qui sono:
 -   **index.html**: Questo è il file HTML principale della tua applicazione. Contiene un  `<div id="root"></div>`  che è dove il tuo app React verrà inserita.
 -   **favicon.ico**: L'icona che appare nella scheda del browser.
 -   **manifest.json**: Configura come la tua app appare quando viene aggiunta alla schermata principale su dispositivi mobili.
 - **robots.txt**: Questo file viene utilizzato per fornire indicazioni ai motori di ricerca su quali pagine o file della tua applicazione web dovrebbero o non dovrebbero essere scansionati e indicizzati. Ad esempio, puoi usare `robots.txt` per impedire ai motori di ricerca di indicizzare alcune sezioni del tuo sito web.

### File nella directory src

**src/**: Questa è la cartella principale per il codice sorgente della tua applicazione React. Alcuni file principali includono:

 - **App.css**: File CSS associato al componente App. Puoi aggiungere gli stili specifici per il componente App qui.
 - **App.js**: Il componente principale della tua applicazione. Qui puoi iniziare a scrivere il tuo codice React.
 - **App.test.js**: File per i test del componente App usando Jest. Puoi scrivere test per assicurarti che il tuo componente funzioni correttamente.
 - **index.css**: File di stile globale per la tua applicazione. Puoi definire regole CSS che saranno applicate a tutto il progetto.
 - **index.js**: Il punto di ingresso dell'applicazione. Questo file monta il componente `App` sull'elemento DOM con id "root".
 - **reportWebVitals.js**: Questo file è utilizzato per misurare le metriche di performance dell'applicazione. Puoi configurarlo per inviare dati sulle prestazioni a un servizio di analisi o semplicemente per loggarli in console.
 - **setupTests.js**: Configura l'ambiente di test. Questo file è caricato automaticamente da Jest prima di eseguire i test. Può essere usato per impostare configurazioni globali o importare librerie di test.

### File nella directory principale

-   **.gitignore**: Questo file specifica quali file e cartelle dovrebbero essere ignorati da Git.
    
-   **package.json**: Contiene metadati rilevanti per il progetto, come il nome del progetto, la versione, le dipendenze e gli script di npm. Questo file è fondamentale per la gestione del progetto con npm.
    
-   **package-lock.json**: Questo file blocca le versioni esatte delle dipendenze installate. Aiuta a garantire che tutti gli sviluppatori del progetto utilizzino le stesse versioni delle dipendenze.
    
-   **README.md**: Un file di documentazione che contiene informazioni sul progetto. Quando crei un nuovo progetto con Create React App, questo file contiene istruzioni su come eseguire e costruire l'applicazione.


