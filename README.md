# Flag Signal

A tiny, neon-lit country-flag quiz. Read the flag, pick its country, and keep your streak alive for bonus points.

## Play

Open `index.html` in a modern browser. For a local server, run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` from this folder. No build step, packages, account, or network connection is required.

Each run has 10 flags chosen from a pool of 30 countries. Pick with a click/tap or keys **1–4**. A correct answer is worth 100 points, with a 20-point bonus for each answer in the current streak. Your personal-best score and longest streak are saved only in your browser using `localStorage`.

## Project files

- `index.html` — the complete game, including styles and game logic.

The flag symbols use the browser/device emoji font. GitHub Pages can serve this static page if you choose to enable Pages for the repository.
