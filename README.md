# EnrollEase — Pitch Deck

A single-page, full-screen HTML presentation website for **EnrollEase**, the startup pitch deck entry of **Team Innovate** for the **Philippine Startup Challenge XI**.

> *A Smarter, Faster, and Paperless Enrollment System for Philippine Schools*

## Run it

Everything lives in [`index.html`](index.html) — no build step, no external dependencies (no CDNs, no web fonts, no icon libraries). Just open the file, or serve the folder:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

To publish on **GitHub Pages**, push this repository and enable Pages from the `main` (or `arena/01a0deb3-presentation`) branch — `index.html` at the repo root is served automatically.

## Features

- **12 full-screen slides** shown one at a time (slideshow/carousel)
- **Navigation**: Previous / Next buttons, keyboard arrows (`←` `→`, also `↑` `↓`, `Space`, `PageUp/Down`, `Home`, `End`), clickable slide dots, and touch swipe on mobile
- **Slide counter** in the form `current / total` plus a top progress bar
- **Smooth fade + slide transitions** between slides
- **Fully responsive** — 4/3/2-column card grids collapse gracefully down to phones; wide tables scroll horizontally
- **Dark theme**: navy/slate background (`#0f172a`), cyan accent (`#22d3ee`), white text
- **Glassmorphism cards**: semi-transparent backgrounds, subtle borders, rounded corners, backdrop blur
- **Modern sans-serif** system font stack (Segoe UI / Inter / system-ui)
- Inline SVG icon sprite, `aria` labelling, and `prefers-reduced-motion` support

## Slides

1. Title — EnrollEase, tagline, Team Innovate, PSC XI badge
2. Executive Summary — Problem / Solution / Key Value
3. Background of the Problem — Long Queues, Slow Processing, Paper Waste, No Visibility
4. Proposed Solution — features + SDG 4 Quality Education callout
5. Objectives — 80% faster, 15 schools, 50,000+ applications, 90%+ CSAT
6. Target Market — B2B customers vs. B2C beneficiaries
7. Value Proposition — Traditional Process vs. EnrollEase comparison table
8. Business Model — revenue flow diagram + 3 revenue streams
9. Market Analysis — TAM 60,000+ / SAM 12,000 / SOM 150, 48-hour deployment advantage
10. Operations Plan — 4-phase, 12-month roadmap
11. Financial Requirement — ₱100,000 budget breakdown
12. Thank You — quote, call to action, contact, Team Innovate footer
