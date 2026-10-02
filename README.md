# CodeComic Lab — The Graphic Novel Editor

A client-side web app that styles code like a **graphic novel / comic book** — a playful code editor and playground rendered in a bold comic-book aesthetic. Everything runs in the browser; no backend, no build step.

## Features

- **Comic-book styled code editor** — thick black borders, halftone dot backgrounds, hard offset shadows, and a "Bangers" comic display font
- **Live code playground** — write code in the editor and see output rendered live (pure client-side execution via iframes)
- **Multi-language support** — HTML, CSS, and JavaScript editing with a monospace Fira Code editor font
- **Zero dependencies to install** — single `index.html` file; only external resources are Google Fonts and Font Awesome icons via CDN
- **Fully client-side** — no server calls, no API keys, works offline after first font load

## Tech Stack

- HTML5 + CSS3 (custom comic theme, CSS variables)
- Vanilla JavaScript (editor logic, live preview rendering)
- Google Fonts (Bangers, Fira Code, Roboto) + Font Awesome icons via CDN

## Quick Start

No build step needed — just open the file:

```bash
git clone https://github.com/girishlade111/CodeComic-Lab-The-Graphic-Novel-Editor.git
cd CodeComic-Lab-The-Graphic-Novel-Editor
# open index.html in any browser, or serve it:
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Project Structure

```
CodeComic-Lab-The-Graphic-Novel-Editor/
├── index.html   # Entire app: markup, comic theme CSS, and editor JS in one file
└── README.md    # This file
```

## Deploy

Any static host works — GitHub Pages, Cloudflare Pages, Netlify, Vercel. GitHub Pages is enabled on this repo.

## License

© 2025 Girish Lade. All rights reserved.

---

Built by Girish Lade — [ladestack.in](https://ladestack.in)
