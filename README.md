# VIRUZ Field Desk

The **VIRUZ Field Desk** is the player-first codex for **MalwareZ**: a journalist's guide to the phone, the VIRUZ you raise, the virtual worlds you enter, and the hostile programs you meet there.

Open [`index.html`](index.html) for the main briefing. Nyx Vale, the field journalist, introduces the phone and points players to the right report instead of exposing implementation notes.

## Player reports

- `index.html` — main briefing, phone features, what is live, and the recommended reading order
- `species.html` — raise VIRUZ: attributes, species, Habits and evolution lines
- `bestiary.html` — scan enemies: regional threats, security packages and bosses
- `world.html` — worlds: zones, level ranges, safe spots, waves and rewards
- `systems.html` — loadout: gear, crafting, items, skill trees and the Tech Lab
- `combat.html` — combat & care: battle flow, hacking, raids, ailments, loyalty and care

## Visual direction

`assets/journalist.svg` is the cleaned, transparent-background portrait of Nyx Vale. It is used on the main briefing and is intentionally a standalone asset so the game can reuse the same tutorial teacher later.

## Updating the codex

This is plain static HTML/CSS with no build step. Keep copy player-facing: explain what a feature does, where to find it, what it costs, and why it matters. Leave engine implementation details out of the reports. When game data changes, update the relevant table and keep the main briefing's feature status accurate.
