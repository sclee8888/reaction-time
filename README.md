# Reaction Time Tester

A single-page web app for a science project measuring reaction time to **light**, **sound**, or **movement** stimuli — plus a **mixed** mode that randomizes across all three.

**Live app:** https://sclee8888.github.io/reaction-time/

## Features

- Four stimulus modes: light flash, sound beep, runner motion, and mixed (random across the three)
- Participant profile: name, age range (<10 / 10–20 / 21–35 / >35), gender, plays sports, plays video games
- Randomized 1.5–4s delay before each signal, with false-start detection
- Tap the stage or press **SPACE** to react (works on iPad/phone)
- Results persist in browser `localStorage`
- Reporting section with filters and breakdowns by every profile dimension
- CSV export for analysis

## How to run

Just open [`index.html`](index.html) in any modern browser. No build step, no server.

## Bonus game: Sheep Kart 64 🐑

A Mario-Kart-style racing game where everyone is a sheep, in the same N64 low-poly style. Lives in [`sheepkart.html`](sheepkart.html) — separate from everything else.

**Play it:** https://sclee8888.github.io/reaction-time/sheepkart.html (or just open `sheepkart.html` in a browser)

- **Modes:** Single Race, **Grand Prix** (3 races, championship points), and **Team Race** (red vs blue)
- **1 or 2 players** (2P is split-screen) plus **AI competitors** filling an 8-sheep field, with rubber-banding
- 3 tracks: Woolly Meadows, Sunset Dunes, Snowy Summit — boost pads, item boxes, minimap, 3 laps
- **Items:** 💨 zoomies boost, 🟤 homing mud ball, 🛡️ wool shield, ✂️ shears (everyone else gets sheared and slows down!)
- P1: **WASD** + **SPACE**/**F** for items — P2: **Arrow keys** + **ENTER**/**Right Shift**
- Engine bleats, baaas, countdown, checkered flag — all raw WebGL + WebAudio, no libraries

## Bonus game: Super Soccer 64 ⚽

A separate 4-a-side soccer game with N64-style low-poly 3D graphics lives in [`soccer.html`](soccer.html) — it doesn't touch the reaction-time app.

**Play it:** https://sclee8888.github.io/reaction-time/soccer.html (or just open `soccer.html` in a browser)

- **1 or 2 players**: press **1** on the menu for 1P vs CPU, **2** (or Enter) for 2 players
- 4-a-side teams: you control one player (marked with a colored ring) while **AI teammates** and an **AI goalkeeper** cover the rest
- Player 1 (Red): **WASD** move, **SPACE**/**F** kick, **E**/**Q** switch player
- Player 2 (Blue): **Arrow keys** move, **ENTER**/**Right Shift** kick, **/** or **.** switch player
- 2-minute match, arena walls (no throw-ins), and a **penalty shootout** if tied — aim with left/right (loft with up/down), and the defending player picks the keeper's dive
- Rendered with raw WebGL: flat-shaded low-poly models, low-res pixelated framebuffer, blob shadows, crowd, and chiptune-style sound effects

## Notes on iPad

- The iPad silent switch mutes Web Audio — disable it in Control Center before running sound trials.
- Tap **🔊 Test sound** once to unlock audio before your first run.
