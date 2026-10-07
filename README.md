# Pinbrawl

An 8-bit dueling pinball game. Two tables sit side by side: sink your warp to send a ball onto the CPU's table, and snipe it when it drains there. Four themed tables, random chaos events and super attacks.

Everything is in one file, `index.html` — no build step and no dependencies (the only outside request is the Google Fonts pixel font for the touch buttons, with a fallback).

## Play locally
Open `index.html` in any modern browser.

## Deploy to GitHub Pages
1. Create a new repository on GitHub and upload these files (`index.html`, `README.md`, `.nojekyll`) to the root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick `main` and `/ (root)`, then **Save**.
4. After a minute the game is live at `https://<your-username>.github.io/<repo-name>/`.

## Controls
| Key | Action |
|---|---|
| ← → (or Z and /) | Left / right flipper |
| Hold Space | Pull the plunger, release to launch |
| ↑ | Fire your super attack |
| P / Esc | Pause |
| M | Sound on / off |

On phones, on-screen buttons appear automatically.

## Rules in short
- Balls are colored by owner (blue = you, red = CPU) and score for their owner on either table.
- Hit your table's warp to send a ball to the rival table.
- Your ball draining on the rival's table = +10,000 SNIPE.
- Enemy balls fizzle after 18 seconds.
- Highest score when the clock hits 0:00 wins. The last 30 seconds are Fever Time (double points).
