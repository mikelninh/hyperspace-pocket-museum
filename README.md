# HYPERSPACE Pocket Museum

**Discover → learn → keep → share.**

Pocket Museum is an open-source collectible learning experiment: tiny digital objects that are delightful to collect and each teach one memorable thing about the real world.

## EARTH_001

The first collection contains eight wonders:

1. Obsidian
2. Labradorite
3. Amethyst
4. Malachite
5. Pyrite
6. Opal
7. Bismuth
8. Meteorite

## What works

- all 8 wonders are playable
- mystery discovery + reveal
- science separated from culture / folklore
- persistent local collection
- collection cabinet
- Telegram sharing
- X sharing
- native device sharing / copy
- source links
- responsive mobile-first UI
- zero backend and zero build step
- the approved 2.5D pixel-diorama art packed into a repository-local atlas, so the visuals do not depend on ChatGPT sandbox paths

## Run locally

```bash
python -m http.server 8000
```

Then visit:

```
http://localhost:8000
```

## Deploy

This is a static site and can be deployed directly with GitHub Pages.

See [docs/DEPLOY.md](docs/DEPLOY.md).

## Product loop

```
DISCOVER
   ↓
LEARN
   ↓
KEEP
   ↓
COLLECT
   ↓
SHARE
   ↓
A FRIEND DISCOVERS
```

## Principles

- the object should be lovable before the label is read
- scientific claims and belief / folklore are never presented as the same thing
- meaningful free discovery should remain part of the museum
- future paid packs, if built, must use transparent probabilities and supply
- no dark patterns or fake urgency
- open-source the core experience where practical

## Roadmap

- [x] complete 8-object collection engine
- [x] approved 2.5D art restored as the visual source of truth
- [x] public open-source repository
- [ ] 12/10 final pixel / 2.5D production art
- [ ] dedicated visual share cards
- [ ] Telegram Mini App
- [ ] Discover Together
- [ ] GitHub Pages public release
- [ ] Telegram contest adaptation
- [ ] transparent supporter packs later

See [docs/MASTERPLAN.md](docs/MASTERPLAN.md) and [docs/ART_DIRECTION.md](docs/ART_DIRECTION.md).

## Licence

Code is MIT licensed. Prototype artwork is included for development and experimentation; define the final art licence before a commercial release.
