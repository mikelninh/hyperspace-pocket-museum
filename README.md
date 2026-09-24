# HYPERSPACE Pocket Museum — v0.3.1

**Discover → learn → keep → share.**

A static, open-source vertical slice for the first complete `EARTH_001` collection.

## What works

- all 8 wonders are playable
- random or chosen mystery discovery
- separate science vs culture/lore panels
- KEEP adds an object to a persistent local collection
- collection cabinet
- Telegram / X / native / copy sharing hooks
- source links per wonder
- local progress reset
- responsive mobile-first UI
- no backend, account or build step
- all production pages use repository-local image assets

## Run locally

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

> Don’t double-click `index.html` from the filesystem. Serving the folder keeps JSON and asset loading consistent with deployment.

## GitHub Pages

The site is intentionally static and can be served directly from the repository root with GitHub Pages.

## Project structure

```text
.
├── index.html
├── app.js
├── styles.css
├── assets/
│   └── wonders/
├── data/
│   └── wonders.json
├── docs/
│   ├── GITHUB.md
│   ├── MASTERPLAN.md
│   └── SOURCES.md
├── .nojekyll
└── LICENSE
```

## v0.4 target

1. dedicated share-card image renderer
2. stronger unique reveal animation per mineral
3. Telegram Mini App shell
4. `Discover Together` group mechanic
5. accessibility + device testing pass
6. replace prototype board crops with final production assets

## Content rule

Scientific statements and historical/cultural beliefs are displayed separately. Cultural symbolism is not presented as scientific evidence.

## Licence

MIT for code. The current generated prototype art is included for prototyping; define the final art licence before public release.
