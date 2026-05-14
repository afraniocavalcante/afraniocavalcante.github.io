# afranio.pm

Personal portfolio of Afrânio Cavalcante, Product Manager — hosted at [afranio.pm](https://afranio.pm) via GitHub Pages.

## Overview

A handcrafted, fully responsive portfolio built in vanilla HTML, CSS and JavaScript — no frameworks, no build tools, no dependencies. Designed with a focus on typography, subtle motion and editorial detail.

## Features

- **Parallax hero** — canvas-based data visualization with mouse-driven layer depth
- **i18n** — full PT/EN translation system via `translations.js`, persisted in `localStorage`
- **CV download** — language-aware: serves the correct PDF based on active language
- **Scroll spy** — active nav link updates as user scrolls through sections
- **Reveal on scroll** — IntersectionObserver-based entrance animations
- **Custom cursor** — desktop-only, with hover state expansion
- **Case studies** — three detailed product cases with stats, callouts and structured narrative

## Structure

```
/
├── index.html                        # Main portfolio page
├── translations.js                   # Centralized i18n for all pages
├── cv-afranio-cavalcante.pdf         # CV in Portuguese
├── cv-afranio-cavalcante-en.pdf      # CV in English
├── CNAME                             # afranio.pm
├── images/
│   ├── afranio.jpg
│   ├── Weni-chats.webp
│   ├── insights.png
│   └── quarkrh.png
└── cases/
    ├── weni-chats.html
    ├── weni-insights.html
    └── quark-rh.html
```

## Responsiveness

Built with four breakpoints and fluid `clamp()`-based typography and spacing throughout:

| Breakpoint | Target |
|---|---|
| `< 420px` | Small mobile |
| `< 700px` | Mobile |
| `< 900px` | Tablet |
| `≥ 1600px` | Ultrawide |

Additional details: `100svh` for mobile viewport, `(hover: hover)` media query for cursor/touch detection, DPR-aware canvas rendering, `loading="lazy"` on all images, and `44px` minimum touch targets on interactive elements.

## Tech

Vanilla HTML · CSS · JavaScript · GitHub Pages
