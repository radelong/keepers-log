# The Keeper's Log

A first-person 3D mystery horror game that runs in the browser.

October 1931. No one on Merrow Island has answered the wireless in eleven days, yet every night passing ships still see the light turning. You are the relief keeper. The boat will not come back for you until dawn.

Everything you need to solve the island is written down somewhere on it.

## Play

Open `index.html` in a desktop browser. Headphones and a dark room recommended.

- The page loads three.js (r160) from jsDelivr on first run, so it needs an internet connection.
- Fonts come from Google Fonts and fall back to system serif fonts offline.
- Mouse look uses pointer lock. If your browser refuses it, click and drag to look instead.
- Basic touch controls exist, but it is built for mouse and keyboard.

## Controls

| Input | Action |
|-------|--------|
| Mouse | Look (click to capture the mouse) |
| W A S D | Walk; Shift to hurry |
| E or click | Examine, take, open |
| F | Torch on/off |
| J | Your papers (reread any document) |
| T | Pocket watch |
| Esc | Pause and see what still needs doing |

## What to expect

- Seven connected deduction puzzles. Most require cross-referencing two or three documents: letters, station logs, a barograph trace, a tide table, a list of lights, a lens plan, and the Board's instructions.
- A timed finale. Mistakes cost time rather than ending the game; failure lets you retry from the start of the finale.
- Progress saves automatically to the browser's localStorage.
- Roughly 30 to 60 minutes, depending on how carefully you read.

No solutions are included here. Read everything.

## Technical notes

Single self-contained HTML file. All geometry, textures, and audio are generated in code: three.js for rendering, canvas for textures, and the Web Audio API for sound. Nothing else is downloaded.
