# Tidebreaker

Realistic AI-generated game.

Made by **Pedro** with Claude.

- Play (Claude Artifact): https://claude.ai/artifact/FmodwunEeQCt8FfJSeVkiB
- Source: `index.html` + `vendor/` (three.js 0.170.0 and fonts, all local — no CDNs)

## Run it on your computer
Browsers block game modules opened straight from a file, so start a tiny local server in this folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## What's in vendor/
- `vendor/three/` — three@0.170.0 from npm (MIT, see `vendor/three/LICENSE`)
- `vendor/fonts/` — Big Shoulders Display, Barlow, IBM Plex Mono woff2 from @fontsource (SIL OFL 1.1)

## Rules for this repo
This repo is Pedro's only. Keep all work on this game here — never in Dad's work repos (beija, money, Arborium, Salsa, Gymgosh, etc.).
