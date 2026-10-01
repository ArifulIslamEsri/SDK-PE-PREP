# ArcGIS Maps SDK for JavaScript — PE Prep App

A fully offline practice app for the **ArcGIS Maps SDK for JavaScript Product Engineer** role at Esri.

No API key. No login. No internet required after first load (except for Google Fonts).

## What's inside

- **7 debug challenges** — real bug patterns from PE support work, with hints and answers
- **Flashcard decks** — Core concepts, Async & timing, Renderers & symbols, Queries
- **Quick rules reference** — correct vs wrong patterns at a glance
- **8-week study plan** — full PE prep roadmap
- **Mindset guide** — how to build confidence, break the shortcut habit, read code systematically

## How to use

1. Download or clone this repo
2. Open `index.html` in any browser
3. Your progress saves automatically in localStorage

## Deploy to GitHub Pages

1. Push to a GitHub repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app will be live at `https://yourusername.github.io/repo-name`

## Topics covered

| Bug category | What goes wrong |
|---|---|
| view.layers vs map.add | Layer added to view instead of map — silent invisible |
| Popup disabled: true | Popup system off — template never reads |
| GraphicsLayer vs FeatureLayer | Wrong layer type — crashes on queryFeatures |
| Async timing | layer.fullExtent read before server loads |
| Field name case | HEIGHT vs Height — silent empty query results |
| Symbol in renderer | Plain {} object instead of new SimpleMarkerSymbol() |

## Built with

Pure HTML, CSS, and vanilla JavaScript. Zero dependencies. Zero build step.
