# Laky Development — Portfolio

Portfolio personale e vetrina dei servizi di **Laky Development**.  
Web Developer & WebApp Creator — *Insert coin to start your project.*

![Preview](./assets/preview.png)

## Demo

[lakydevelopment.com](https://lakydevelopment.com)

---

## Stack

- **HTML5** — struttura semantica e accessibile
- **CSS3** — design system con custom properties, layout con Grid e Flexbox
- **JavaScript (vanilla)** — SPA router, animazioni, logica interattiva
- **GSAP 3** — animazioni fluide (pixel decor, scroll hint)
- **Three.js** — canvas hero in background
- **Google Fonts** — Press Start 2P, Rajdhani, Inter, VT323

Nessun framework, nessun bundler. Zero dipendenze npm.

---

## Funzionalità

- **Boot screen** con barra di caricamento pixel-style
- **SPA** — navigazione client-side senza reload (hash routing)
- **Pixel decorations** — icone SVG pixel art flottanti con GSAP organic float
- **CRT scanlines** — overlay retro via CSS
- **Scroll HUD** — barra di progresso lettura
- **Achievement toast** — notifiche stile arcade al cambio pagina
- **Konami Code** easter egg (`↑ ↑ ↓ ↓ ← → ← → B A`)
- **Typewriter effect** — animazione titolo hero
- **Counter animation** — stats numerici animati
- **Form contatto** — integrazione Web3Forms
- **Dark theme** — palette neon su sfondo scuro
- **Responsive** — mobile first, breakpoint a 768px e 480px
- **Accessibilità** — `prefers-reduced-motion` rispettato, landmark ARIA

---

## Struttura
```
lakyDevelopment/
├── index.html          # Tutta l'app in un unico file
├── assets/
│   ├── logo.png
│   ├── og-image.png
│   └── projects/       # Screenshot progetti
├── CNAME
└── README.md
```
---

## Pagine

| Pagina | Contenuto |
|---|---|
| **Home** | Hero, Stack tecnologico, Workflow, Testimonianze |
| **About** | Bio, Esperienza, Tech stack, Approccio |
| **Services** | Pacchetti / prezzi, FAQ |
| **Projects** | Portfolio con filtri per categoria |
| **Contact** | Form contatto, info |

---

## Avvio locale

Non richiede installazione. Apri `index.html` direttamente nel browser o usa un server locale:

```bash
# Con VS Code
# Installa l'estensione "Live Server" e clicca "Go Live"

# Con Python
python -m http.server 8080

# Con Node.js
npx serve .
