# NEON COURIER

A cyberpunk pixel-art platformer in a single HTML file: plain Canvas and JavaScript, no libraries.

You play a delivery robot crossing three levels of a neon city, ending in a three-phase boss fight against the Overseer.

## Play

Open `index.html` in any browser (double-click it). No server or install needed.

## Controls

| Action | Keys |
|---|---|
| Move | Arrows / A D |
| Jump (hold for higher, press again in the air for a double jump) | Space / Z / W / Up |
| Dash (invulnerable, breaks enemies) | X / Shift / K |
| Pause | P / Esc |
| Mute | M |
| Lighting effects on/off | G |
| Confirm | Enter |

## What's inside

- Fixed-timestep game loop (60 Hz), smooth look-ahead camera, three-layer parallax background
- Variable-height jump, coyote time, jump buffering, double jump and dash
- Three levels with moving and crumbling platforms, walkers, drones, turrets, spikes, timed lasers, data chips, repair kits and checkpoints
- A three-phase boss: spread shots, summons, laser columns, ground slams and shockwaves
- Procedural Web Audio sound effects and step-sequenced music
- All art drawn in code, with a pixel-stepped lighting, bloom and vignette pass

Movement tuning lives in the `PHYS` object at the top of the script.
