# Hill Climb Racer

A 2D side-scrolling driving game with physics, in the style of Hill Climb Racing. It is a single self-contained file, `index.html`, written with HTML, CSS and vanilla JavaScript on a canvas. No build step or dependencies.

## How to play

Open `index.html` in a browser.

| Control | Action |
|---|---|
| `→` or `D` | Accelerate (uses fuel) |
| `←` or `A` | Brake / reverse |
| On-screen ◀ ▶ buttons | Same controls on touch devices |

- Drive as far as you can. The HUD shows **distance**, **coins**, **speed** and a **fuel** bar.
- Pick up **coins** (10 points each) and **fuel** cans along the way.
- The run ends when you flip the car over (tilt past about 2.3 radians), or when you run out of fuel and come to a stop.
- On the Game Over screen you can restart, or spend 50 coins on an upgrade: **speed** (more acceleration) or **fuel tank** (+25 capacity, refilled).

## How it works

- Vehicle physics with gravity, wheel traction on the terrain angle, rotation and a speed cap.
- Procedurally generated terrain, coins and fuel pickups.
- Sound effects generated in the browser.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole game |
| `PROMPT.md` | The text prompt that describes the game's requirements |
