# Calcetto Team Manager (El_Clasico_TM)

> Una semplice web app per gestire i giocatori di calcetto, selezionarli per le partite (5v5, 6v6, 8v8, 11v11) e generare squadre equilibrate automaticamente. Ideale per organizzare partite amichevoli senza discussioni sulla composizione dei team!

## Funzionalità Principali

*   **Gestione Giocatori:**
    *   Aggiungi nuovi giocatori specificando nome, ruolo e diverse abilità (Difesa, Attacco, Velocità, Scatto, Pressing, Determinazione, Robustezza, Peso, Altezza).
    *   Modifica i dati dei giocatori esistenti.
    *   Elimina giocatori dalla lista.
*   **Impostazione Partita:**
    *   Seleziona il tipo di partita (Calcio a 5, Calcio a 6, Calciotto, Calcio a 11) per determinare il numero di giocatori necessari.
*   **Selezione Giocatori:**
    *   Apri un modal per selezionare facilmente i giocatori "convocati" per la partita corrente.
    *   Controllo automatico per selezionare il numero esatto di giocatori richiesti.
*   **Generazione Squadre Equilibrate:**
    *   Algoritmo per bilanciare le squadre basato su un punteggio calcolato per ogni giocatore (derivato dalle sue statistiche).
    *   Cursore di "Imprevedibilità" per aggiungere un fattore casuale controllato al bilanciamento, rendendo le squadre meno prevedibili.
    *   Visualizzazione chiara delle due squadre generate con i rispettivi punteggi medi (calcolati internamente per il bilanciamento).
*   **Persistenza dei Dati:**
    *   I giocatori e il tipo di partita selezionato vengono salvati automaticamente nel `localStorage` del tuo browser, così non perdi i dati chiudendo la pagina (ma sono legati al dispositivo e al browser specifico).

## Demo / Accesso Live

Puoi accedere e utilizzare l'applicazione direttamente dal tuo browser (anche su smartphone) tramite GitHub Pages al seguente link:

**[LINK ALLA TUA GITHUB PAGE VERRÀ QUI]**

*(Ricorda di sostituire `[LINK ALLA TUA GITHUB PAGE VERRÀ QUI]` con l'URL effettivo una volta che avrai attivato GitHub Pages per questo repository - ti spiego come fare dopo)*

## Come Usare

1.  **Accedi** al link della demo qui sopra.
2.  **Crea Giocatori:** Usa il form "Nuovo Giocatore" per aggiungere tutti i tuoi amici/compagni di squadra, inserendo le loro caratteristiche.
3.  **Gestisci Giocatori:** Modifica o elimina giocatori se necessario dalla lista "Giocatori Disponibili".
4.  **Imposta Partita:** Scegli il formato della partita (es. "Calcio a 5").
5.  **Seleziona Convocati:** Clicca su "Seleziona Giocatori", scegli i giocatori che parteciperanno (il numero esatto richiesto dal formato) e conferma.
6.  **Genera Squadre:** Regola (opzionalmente) il livello di "Imprevedibilità" e clicca su "Crea Squadre Equilibrate".
7.  **Visualizza:** Le due squadre bilanciate appariranno in fondo alla pagina.

## Tecnologia Utilizzata

Questa è una Single Page Application (SPA) contenuta in un unico file HTML, resa possibile da:

*   HTML5
*   CSS3 (stili incorporati con approccio mobile-first)
*   JavaScript (ES6+)
*   **React (v18)** caricato via CDN
*   **ReactDOM (v18)** caricato via CDN
*   **Babel Standalone** (per la compilazione JSX al volo nel browser)
*   **LocalStorage Web API** (per salvare i dati dei giocatori localmente)

Non richiede processi di build o installazioni complesse.

---
