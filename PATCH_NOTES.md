# VIRUZ Field Desk patch

Copy these files over the matching paths in `Froztorr/Viruz_codex`:

- `index.html` — player-first main briefing with Nyx Vale, phone feature status, tutorials and reading order
- `bestiary.html` — journalist-style player scan report; removed implementation notes such as pre-scaling and `spawnAntiviruz()` references
- `README.md` — updated player-facing project description
- `assets/journalist.svg` — transparent, reusable portrait used by the main briefing
- `assets/journalist-clean.png` — transparent PNG source for reuse in the game client/tutorial teacher

The existing shared stylesheet is preserved; the two rewritten pages carry their focused layout styles inline.
