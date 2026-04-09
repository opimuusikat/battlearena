# Battle Arena

A single-file browser game built with HTML5 Canvas. Pick fighters, draft perks, and watch them battle across themed arenas — supports 2–8 players and full tournament brackets.

## Play

Open `battle.html` in any browser. No server, no install, no dependencies.

## Fighters

25 fighters across 5 categories:

| Category | Fighters |
|----------|----------|
| ⚔ Weapons | Knight, Berserkr, Ninja, Reaper, Paladin |
| ✦ Magic | Storm, Void, Necro, Chrono, Phantom |
| ✦ Nature | Plague, Swamp, Fungus, Briar, Echo |
| ◆ Cursed | Rogue, Golem, Spectre, Mirror, Titan |
| ★ Eldritch | Wraith, Siphon, Herald, Rift, Prism |

Each fighter has unique abilities — orbiting weapons, projectiles, area pulses, clones, life leech, overcharge, and more.

## Synergies

Stack 3+ fighters from the same category to unlock category bonuses:
- **Weapons** — increased orbit speed
- **Magic** — reduced ability cooldowns
- **Nature** — passive HP regen
- **Cursed** — bonus armor
- **Eldritch** — expanded orbit range

## Arenas

6 themed arenas, each with a unique hazard that spawns after 30 seconds:

| Arena | Hazard |
|-------|--------|
| Dungeon | Spike traps |
| Volcano | Expanding lava eruptions |
| Cyber | Sweeping laser beams |
| Cosmos | Gravity well |
| Dojo | Collapsing walls |
| Ice | Frost zones (freezes + slows) |

## Game Modes

- **Free-for-all** — 2–8 fighters, last one standing wins
- **Tournament** — 4 or 8-player single-elimination bracket with left/right symmetric layout
- **Perk draft** — before each fight, each fighter picks one of three random perks

## Features

- Real-time ability combat with orbiting weapons, projectiles, rings, and clouds
- Environmental hazards, sudden death, and power-ups
- Kill feed, damage numbers, screen shake, and hit stop
- Leaderboard tracked in localStorage
- Post-match stat card (time, damage dealt, hits landed)
- Speed controls: 1×, 2×, 4×
- Fully self-contained — one HTML file, ~3900 lines
