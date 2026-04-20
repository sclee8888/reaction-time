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

## Notes on iPad

- The iPad silent switch mutes Web Audio — disable it in Control Center before running sound trials.
- Tap **🔊 Test sound** once to unlock audio before your first run.
