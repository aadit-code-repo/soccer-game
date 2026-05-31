# Soccer Sim ⚽

A browser-playable arcade soccer game. Single self-contained HTML file — no build step, no dependencies. Open `index.html` in any modern browser.

## Features

- **Team picker** at startup — choose Argentina or Portugal
- **Top-down 2-on-2** matches (you + AI teammate vs two CPU outfielders + keeper) plus a referee
- **Realistic ball physics** — ground friction, air arcs, Magnus curve from spin, charged kicks
- **Dribble control** — ball sticks to your feet until you kick, get tackled, or jump
- **Bicycle kicks** — whiff a kick, then jump to launch a flipping overhead volley
- **CPU AI** that chases, shoots, passes, tackles, and gets carded for fouls
- **Yellow/red cards** with send-offs, penalty kicks, and full **penalty shootouts** (best-of-5 + sudden death)
- **Outs** — throw-ins, goal kicks, corner kicks (you auto-take corners)
- **Halftime** at 45:00, **full-time** at 90:00 with replay button
- **Goal celebrations** — confetti, screen flash, score pulse, player arm-raise animations
- **Shop** with 30+ gamepasses — speed/power buffs, anti-tackle shield, gamepass currency (coins + premium gems)
- **Persistent save** in `localStorage` — coins, gems, and owned passes survive reloads

## Controls

| Key | Action |
|---|---|
| `W` `A` `S` `D` or arrow keys | Move |
| `Space` (hold) | Charge kick (release to fire) |
| `Shift` | Jump (header high balls) |
| `Q` | Sprint |
| `F` | Slide tackle |
| `Space` (no ball) → `Shift` | Bicycle kick |
| `B` | Open shop |
| `🛡️` button | Toggle anti-tackle shield |

Touch controls (joystick + kick button) appear automatically on mobile.

## Play it

Just open `index.html` — that's the whole game.
