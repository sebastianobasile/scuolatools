# 🏫 ScuolaTools — Strumenti digitali per la scuola italiana

![License](https://img.shields.io/badge/Licenza-CC%20BY--NC--SA%204.0-blue)
![HTML](https://img.shields.io/badge/HTML-Single%20File-red?logo=html5)
![Scuole italiane](https://img.shields.io/badge/Destinatari-Scuole%20italiane-red)
![GitHub stars](https://img.shields.io/github/stars/sebastianobasile/scuolatools)
![GitHub forks](https://img.shields.io/github/forks/sebastianobasile/scuolatools)

Raccolta di **strumenti web gratuiti** per la gestione della documentazione scolastica italiana. Ogni strumento è un **singolo file HTML** — nessuna installazione, nessun server, nessun database. Si apre direttamente nel browser, funziona offline e salva i dati in locale.

Sviluppato da **Sebastiano Basile** — [superscuola.com](https://www.superscuola.com)

---

[![Contributo volontario](https://img.shields.io/badge/Offrimi_un_caffè_☕-PayPal-blue)](https://paypal.me/superscuola)

Se questi strumenti ti sono utili, puoi supportarne lo sviluppo con un piccolo contributo volontario. Grazie! ☕

---
## 🔗 Demo e utilizzo live
 
| Pagina | Link |
|---|---|
| 🆙 Area Segreteria Docenti Famiglie | <a href="https://www.superscuola.com/puiacapuanadeamicis/?folder=%3E%3E%3EP.U.I.A._Strumenti_co-progettati_con_il_supporto_della_I_A%2F%3E%3E%3EArea_Segreteria_Docenti_Famiglie">Visita e utilizza online</a> |
 
> Le demo sono quelle dell'installazione reale presso l'I.C. Capuana-De Amicis di Avola (SR). L'accesso e il suo utilizzo è libero a tutti.
 
---


## 🗂️ Strumenti disponibili

| Strumento | Cartella | Descrizione |
|---|---|---|
| 📋 Dichiarazione o Richiesta generica | [`dichiarazione-generica/`](dichiarazione-generica/) | Genera dichiarazioni e richieste generiche per genitore/tutore indirizzate al Dirigente Scolastico |
| 📄 Dichiarazione Sostitutiva di Autocertificazione | [`autocertificazione/`](autocertificazione/) | Autocertificazione ai sensi del D.P.R. 445/2000 con supporto firma sostitutiva |
| 👤 Individuazione Personale Scolastico | [`ips/`](ips/) | Genera il documento ufficiale di individuazione del personale a tempo determinato da graduatoria d'istituto |
| 📢 Richiesta Convocazioni Genitori | [`convocazioni-genitori/`](convocazioni-genitori/) | Modulo per i docenti che richiedono la convocazione dei genitori degli alunni |
| ⚠️ Segnalazione Dispersione Scolastica | [`dispersione/`](dispersione/) | Segnalazione all'ufficio di segreteria delle assenze prolungate degli alunni |
| 📉 Segnalazione Insufficienze Alunni | [`insufficienze/`](insufficienze/) | Comunicazione alle famiglie delle insufficienze disciplinari con motivazioni e suggerimenti |

---

## ✨ Caratteristiche comuni a tutti gli strumenti

- 👁️ **Anteprima in tempo reale** del documento finale (layout A4)
- 📥 **Esportazione PDF** diretta dal browser tramite html2pdf
- 💾 **Salvataggio automatico** nel browser (localStorage)
- 🔁 **Reset rapido** dei campi con conferma
- ⚧ **Accordo grammaticale** automatico maschile/femminile dove previsto
- ✍️ Supporto **firma sostitutiva** ai sensi dell'art. 3 c. 2 D.Lgs. n. 39/93
- ⚙️ **Configurazione istituto** tramite variabili CSS nel blocco `:root`

---

## 🚀 Utilizzo

Per ciascuno strumento:

1. **Scarica** la cartella o il singolo file `index.html` che ti interessa
2. **Aprilo** con qualsiasi browser moderno (consigliato: Chrome o Edge)
3. **Compila** il pannello laterale — il documento si aggiorna in tempo reale
4. Clicca **"SCARICA PDF"** per generare il documento ufficiale

> Tutti gli strumenti funzionano **offline**, senza connessione internet.

---

## ⚙️ Personalizzazione per il proprio istituto

Ogni file ha un blocco `:root` in cima allo stile con le variabili dell'istituto:

```css
:root {
    --nome-scuola: "NOME DEL TUO ISTITUTO";
    --ds-nome: "PROF. NOME COGNOME";
    /* ... altri campi ... */
}
```

Aprire il file con un editor di testo (VS Code, Blocco Note, ecc.), modificare i valori e salvare. La personalizzazione è permanente per tutte le sessioni.

---

## 📁 Struttura del repository

```
scuolatools/
├── README.md
├── LICENSE
├── .gitignore
├── dichiarazione-generica/
│   └── index.html
├── autocertificazione/
│   └── index.html
├── ips/
│   └── index.html
├── convocazioni-genitori/
│   └── index.html
├── dispersione/
│   └── index.html
└── insufficienze/
    └── index.html
```

---

## 🔒 Privacy e dati

Tutti i dati inseriti vengono salvati **esclusivamente nel browser locale** (localStorage). Nessun dato viene trasmesso a server esterni. Il tasto **"Pulisci campi"** / **"Pulisci tutto"** li rimuove completamente.

---

## 📄 Licenza

Distribuito con licenza **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.

- ✅ Puoi usarli, modificarli e ridistribuirli liberamente
- ✅ Devi mantenere l'attribuzione all'autore originale
- ❌ Non puoi usarli per scopi commerciali
- ❌ Le versioni modificate devono usare la stessa licenza

Consulta il file [LICENSE](LICENSE) per il testo completo.

---

## 🤝 Contribuire

Segnalazioni di bug e suggerimenti tramite le **Issues** di GitHub.
Per modifiche al codice, aprire una **Pull Request**.

---

## 👤 Autore

**Sebastiano Basile**
🌐 [superscuola.com](https://www.superscuola.com)

[![Contributo volontario](https://img.shields.io/badge/Offrimi_un_caffè_☕-PayPal-blue)](https://paypal.me/superscuola)
