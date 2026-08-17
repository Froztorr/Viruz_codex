# Viruz_codex

The **MalwareZ Codex** — a static, illustrated player's reference for the
[Viruz](../viruz) game (MalwareZ). Everything is sourced from the live game
data (`src/data.js`, `src/galaxy*.js`, `src/dnd.js`, etc.) and the art assets
in that repo, so it stays a faithful companion to whatever's actually live.

## Read it

Open `index.html` (or enable GitHub Pages: **Settings → Pages → Deploy from
branch → `main` / root**, same as the main game). Once Pages is on, the book
icon in the phone's top bar (top-left corner) in the main Viruz game links
straight here.

## Structure

```
index.html      cover + table of contents + quick-start tips
species.html    attributes, team synergy, the Habit color/type system,
                rarity ladder, and all 14 VIRUZ species with their
                evolution chains
bestiary.html   every wild AntiviruZ by region, raid Security Guard
                tiers, and the wandering region bosses
world.html      every map and zone: Verdant Realm, Infernal Realm,
                the Galaxy hub + 4 sub-maps, the Tabletop Realm
systems.html    equipment slots/grades, Payload effects, crafting,
                eggs/items/potions, the 4 attribute skill trees, and
                the True Form / stage-2 mutation evolution system
combat.html     stats, damage formula, ailments, the Hack/Raid
                minigame, loyalty tiers, care minigames, and tips
assets/         curated sprite/map art copied from the Viruz repo,
                plus the shared style.css
```

## Updating

This is plain static HTML/CSS — no build step. When the game's data
changes (new species, rebalanced numbers, a new map), update the
relevant table by hand and, if new art exists, drop it into
`assets/monsters/`, `assets/species/` or `assets/maps/` and reference it.
