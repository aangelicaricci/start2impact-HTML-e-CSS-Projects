# Angelica Ricci | Portfolio & CV

Sito personale sviluppato in **HTML, SCSS e Bootstrap**, realizzato come progetto del corso **HTML e CSS** del master in AI e Agenti AI per il Business di **start2impact**.

🔗 **Sito live:** [aangelicaricci.github.io/angelicaricci.github.io](https://aangelicaricci.github.io/angelicaricci.github.io/)

---

## 📋 Indice

- [Descrizione](#-descrizione)
- [Pagine del sito](#-pagine-del-sito)
- [Tecnologie utilizzate](#-tecnologie-utilizzate)
- [Funzionalità principali](#-funzionalità-principali)
- [Struttura del repository](#-struttura-del-repository)
- [Come eseguire il progetto in locale](#-come-eseguire-il-progetto-in-locale)
- [Autrice](#-autrice)

---

## 📖 Descrizione

Questo progetto è un sito personale pensato per presentare il mio profilo professionale come **Business Intelligence Specialist**, i progetti realizzati durante il master in AI e Agenti AI per il Business e il mio curriculum vitae. Il sito è **100% responsive**, ottimizzato per i motori di ricerca (SEO) e pubblicato tramite **GitHub Pages**.

## 📄 Pagine del sito

| Pagina | File | Descrizione |
|---|---|---|
| Home | `index.html` | Presentazione personale e navigazione verso le altre sezioni |
| Portfolio | `portfolio.html` | Galleria dei progetti realizzati durante il master |
| CV | `cv.html` | Curriculum vitae completo in formato HTML, con download del PDF |
| Contatti | `contatti.html` | Form di contatto per parlare di dati e AI |

## 🛠 Tecnologie utilizzate

- **HTML5** — struttura semantica delle pagine
- **SCSS (Sass)** — fogli di stile modulari, variabili e funzioni per una gestione D.R.Y. del codice
- **Bootstrap 5** — grid system, componenti UI (navbar, card) e utility responsive
- **Bootstrap Icons** — iconografia
- **Google Fonts (Inter)** — tipografia
- **EmailJS** — invio del form di contatto direttamente dal frontend, senza backend dedicato
- **GitHub Pages** — hosting e pubblicazione del sito

## ✨ Funzionalità principali

- 📱 **Design 100% responsive**, con approccio mobile-first e media query dedicate
- 🧭 **Menu sticky** con navbar collassabile su mobile
- 🎨 **Palette e tipografia coerenti** grazie a variabili SCSS centralizzate
- 🖱️ **Micro-interazioni**: hover sulle card dei progetti, transizioni fluide, backdrop blur sull'header
- 📬 **Form di contatto** con validazione nativa HTML e invio via EmailJS
- 🔍 **SEO e Open Graph**: meta tag ottimizzati per il posizionamento sui motori di ricerca e per la condivisione sui social
- 🖼️ Layout realizzati con **CSS Grid** (es. griglia del CV, griglia dei progetti) e **Flexbox** (es. header del CV, skill list)

## 📁 Struttura del repository

```
start2impact-HTML-e-CSS-Projects/
├── index.html
├── portfolio.html
├── cv.html
├── contatti.html
└── assets/
    ├── css/
    │   └── main.css        # CSS compilato da SCSS
    ├── img/                # Immagini e favicon
    └── pdf/                # PDF dei progetti e del CV scaricabile
```

> Il file sorgente `main.scss` (con relative partial come `_variables.scss`) è mantenuto separatamente e compilato in `assets/scss/main.css` prima della pubblicazione.

## 💻 Come eseguire il progetto in locale

1. Clona il repository:
   ```bash
   git clone https://github.com/aangelicaricci/angelicaricci.github.io.git
   ```
2. Entra nella cartella del progetto:
   ```bash
   cd angelicaricci.github.io
   ```
3. Apri `index.html` nel browser (o usa un'estensione come *Live Server* di VS Code per una preview con hot-reload).

Se modifichi il file `.scss`, ricordati di ricompilarlo in CSS prima di visualizzare le modifiche (ad esempio con `sass main.scss assets/css/main.css` o con l'estensione Live Sass Compiler di VSCode).

## 👩‍💻 Autrice

**Angelica Ricci** — Augmented BI Specialist

- 💼 [LinkedIn](https://www.linkedin.com/in/angelica-ricci-a9808a1b0/)
- 💻 [GitHub](https://github.com/aangelicaricci)
- 📩 Contattami tramite il [form dedicato](https://aangelicaricci.github.io/angelicaricci.github.io/contatti.html)

---

*Progetto sviluppato nell'ambito del master in AI e Agenti AI per il Business di [start2impact](https://www.start2impact.it/).*
