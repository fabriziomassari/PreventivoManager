# Preventivo Manager (AI Powered)
Serverless, Single-File Quote Editor powered by Google Gemini AI

[Vai alla versione Italiana](#-preventivo-manager-italiano)

## Introduction
**Preventivo Manager** is a serverless, "Single-File Application" (SFA) quote editor. Encapsulated entirely within one HTML file, it runs directly in your browser with no backend or installation required.

It leverages **Google Gemini AI** to generate quote drafts, rewrite text, and organize complex cost structures from simple natural language prompts.

### Key Features
* **Zero Installation:** Just download `PreventivoManager.html` and open it in any modern browser.
* **Magic AI Assistant:** Generate full quotes or rewrite specific text selections using the Google Gemini API.
* **Privacy First:** Data persists only in your browser's `localStorage`. No external database.
* **Secure Export:** Option to save encrypted HTML files (tamper-proof).
* **Smart Print:** CSS optimized for perfect A4 PDF export.
* **Auto-Calculation:** Smart tables handle totals, discounts, and quantities automatically.

### User Guide (Advanced)

#### 1. Backup & Restore
* **Backup:** Saves all your local data (Draft, Templates, Settings, Custom Languages, API Keys) into a single `.json` file. Use this to move your workspace to another browser or computer.
* **Restore:** Loads a previously saved backup file. *Warning: This overwrites your current local data.*

#### 2. Template Management
* **Save as Template:** Saves the current document structure as a reusable template in the library.
* **Default Template:** inside "Templates", you can mark one as "Default". This template will be automatically loaded whenever you click the "New" button.

#### 3. Sections Library
* **Save to Library:** Click the floppy icon near any section (on hover) to save that specific block (e.g., a standard "Terms & Conditions" text or a specific pricing table).
* **Insert:** Use the "Sections" button to drag & drop or insert saved blocks into your current document.

#### 4. File Management (Save/Open)
* **Save HTML:** Exports the quote as a standalone `.html` file that can be sent to clients.
* **Open File:** You can load any previously saved HTML quote back into the editor to modify it. This works even for encrypted files (the app handles decryption internally).

#### 5. Encrypted Saving & Expiry
* Enable **"Encryption"** in Settings.
* When saving, you can set an **Expiration Date**.
* The generated HTML file will be encrypted. If opened after the expiration date, the content will be inaccessible ("Self-destruct" logic), showing only an "Expired" message.

#### 6. Undo / Redo
* The editor keeps track of your last **30 actions**.
* Use the toolbar buttons or standard shortcuts (`Ctrl+Z` / `Ctrl+Y`) to navigate history.

#### 7. Multi-Language System
* **Change Language:** Switch interface language from Settings.
* **Custom Languages:** You can create your own translation file (JSON).
    1. Click "Download Language Template" in Settings.
    2. Translate the values in the JSON file.
    3. Import the file back using the "Import" button.

---

### Quick Start
1.  **Download:** Download the `PreventivoManager.html` file from this repository.
2.  **Open:** Open the file with Chrome, Edge, or Firefox.
3.  **Configure AI (Optional):**
    * Click on **Settings** (gear icon).
    * Enter your [Google Gemini API Key](https://aistudio.google.com/app/apikey).
    * Start using the "Magic AI" button!

### AI Configuration
To enable AI features (Magic Wizard & Rewrite), you need a free API Key from Google.

1.  Get your key here: [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  Open **Settings** in PreventivoManager.
3.  Paste the key in the "Google Gemini API Key" field.
4.  The key is stored locally in your browser.

### Tech Stack
* **Core:** Vanilla JavaScript (ES6+), HTML5, CSS3.
* **AI:** Google Gemini API (Flash Model).
* **Fonts:** Google Fonts (Comfortaa, Montserrat).
* **Icons:** FontAwesome (CDN).

### License
This project is licensed under the MIT License - see the LICENSE file for details.
Created by **Fabrizio Massari**.

---

# Preventivo Manager (Italiano)

## Introduzione
**Preventivo Manager** è un editor di preventivi "Single-File Application" (SFA). Interamente contenuto in un singolo file HTML, funziona direttamente nel browser senza necessità di server, backend o installazioni.

Integra l'intelligenza artificiale di **Google Gemini** per generare bozze di preventivi, riscrivere testi e calcolare strutture complesse partendo da una semplice descrizione testuale.

### Funzionalità Principali
* **Zero Installazione:** Basta scaricare il file `PreventivoManager.html` e aprirlo con Chrome, Edge o Firefox.
* **Magic AI Assistant:** Genera interi preventivi o riscrivi sezioni specifiche usando l'API di Google Gemini.
* **Privacy First:** I dati vengono salvati solo nel `localStorage` del tuo browser. Nessun database esterno.
* **Protezione File:** Possibilità di salvare file HTML cifrati (protetti da modifica manuale).
* **Stampa Smart:** Layout ottimizzato automaticamente per la stampa in PDF A4.
* **Calcoli Automatici:** Tabelle intelligenti che calcolano totali, sconti e quantità in tempo reale.

### Guida Utente (Avanzata)

#### 1. Backup e Restore
* **Backup:** Salva tutti i dati locali (Bozza corrente, Template salvati, Impostazioni, Lingue Custom, API Key) in un unico file `.json`. Utile per trasferire il tuo lavoro su un altro PC o browser.
* **Restore:** Carica un file di backup salvato in precedenza. *Attenzione: Sovrascrive i dati attuali nel browser.*

#### 2. Gestione Template
* **Salva come Modello:** Salva la struttura del documento attuale come modello riutilizzabile nella libreria.
* **Template di Default:** Nel gestore Template, puoi impostare un modello come "Default". Questo modello verrà caricato automaticamente ogni volta che premi il tasto "Nuovo".

#### 3. Libreria Sezioni
* **Salva in Libreria:** Clicca l'icona "salva" (floppy disk) che appare accanto a ogni sezione per salvare quel blocco specifico (es. un testo standard di termini e condizioni o una tabella prezzi).
* **Inserisci:** Usa il pulsante "Sezioni" per trascinare o inserire blocchi salvati nel documento corrente.

#### 4. Gestione File (Salva/Apri)
* **Salva HTML:** Esporta il preventivo come file `.html` autonomo da inviare al cliente.
* **Apri File:** Puoi ricaricare nell'editor qualsiasi preventivo HTML salvato in precedenza per modificarlo. Funziona anche con i file cifrati (il programma gestisce la decifrazione internamente).

#### 5. Salvataggio Cifrato con Scadenza
* Abilita l'opzione **"Cifratura"** nelle Impostazioni.
* Quando salvi, puoi impostare una **Data di Scadenza**.
* Il file HTML generato sarà cifrato. Se aperto dopo la data di scadenza, il contenuto non sarà più visibile ("Autodistruzione"), mostrando solo un messaggio di "Documento Scaduto".

#### 6. Undo / Redo
* L'editor memorizza le ultime **30 azioni**.
* Usa i pulsanti nella toolbar o le scorciatoie da tastiera (`Ctrl+Z` / `Ctrl+Y`) per annullare o ripetere le modifiche.

#### 7. Sistema Multilingua
* **Cambio Lingua:** Cambia la lingua dell'interfaccia dalle Impostazioni.
* **Lingue Custom:** Puoi creare un file di traduzione personalizzato (JSON).
    1. Clicca "Scarica Template Lingua" nelle Impostazioni.
    2. Traduci i valori nel file JSON.
    3. Importa il file tramite il pulsante "Importa".

---

### Guida Rapida
1.  **Download:** Scarica il file `PreventivoManager.html` da questo repository.
2.  **Apri:** Apri il file con il tuo browser preferito.
3.  **Configurazione AI (Opzionale):**
    * Vai su **Impostazioni** (icona ingranaggio).
    * Inserisci la tua [Google Gemini API Key](https://aistudio.google.com/app/apikey).
    * Inizia a usare il pulsante "Magic AI"!

### Configurazione AI
Per abilitare le funzioni AI (Wizard Magico e Riscrittura), è necessaria una API Key gratuita di Google.

1.  Ottieni la chiave qui: [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  Apri le **Impostazioni** in PreventivoManager.
3.  Incolla la chiave nel campo "Google Gemini API Key".
4.  La chiave viene salvata localmente nel tuo browser.

### Stack Tecnologico
* **Core:** Vanilla JavaScript (ES6+), HTML5, CSS3.
* **AI:** Google Gemini API (Modello Flash).
* **Fonts:** Google Fonts (Comfortaa, Montserrat).
* **Icons:** FontAwesome (CDN).

### Licenza
Questo progetto è rilasciato sotto licenza MIT - vedi il file LICENSE per i dettagli.
Creato da **Fabrizio Massari**.
