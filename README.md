# PEAK web port

This repository contains a small browser game inspired by a mountain-climbing challenge: a single-page HTML/JavaScript version of PEAK that runs in any modern browser.

## Run locally

Because this is a static site, you can either:

- open `index.html` directly in your browser, or
- serve the folder locally:

```bash
cd PEAKweb
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls

- `A` / `D` or `←` / `→`: move
- `W` / `↑` / `Space`: jump

## Goal

Reach the flag near the summit. The game includes a simple score, lives, and restart flow.
