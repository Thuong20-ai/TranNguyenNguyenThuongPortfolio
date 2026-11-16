# Thuong OS — Interactive Portfolio

Desktop-style portfolio of Tran Nguyen Nguyen Thuong (Digital Marketing, RMIT).
Single `index.html` + `img/` folder. No build step, no dependencies (fonts load from Google Fonts).

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## Publish on GitHub Pages
1. Create a new repo (e.g. `portfolio`) and upload everything in this folder (keep `index.html` at the root and the `img/` folder next to it).
2. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
3. After ~1 minute the site is live at `https://<username>.github.io/<repo>/`.

## Edit content
Open `index.html` and search for the data arrays `SKILLS`, `P` (projects), `XP` (experience) and `TOUR`.
