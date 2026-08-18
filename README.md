# Event-camera FOV calculator

Static HTML/JS page to estimate field of view from pixel pitch, array size, and lens focal length. Camera presets match [jAER](https://github.com/SensorsINI/jaer) chip classes.

Open [`index.html`](index.html) in a browser (no server needed).

## URLs (after you create the GitHub repo and enable Pages)

| | |
|--|--|
| Source | https://github.com/SensorsINI/lensFOV |
| Pages | https://sensorsini.github.io/lensFOV/ |

This repo is a sibling of `jaer` (`Dropbox/GitHub/SensorsINI/jaer` and `.../lensFOV`). It does **not** use jAER’s GitHub Pages URL (`https://sensorsini.github.io/jaer/`).

## Publish

1. On GitHub: **SensorsINI → New repository → `lensFOV` → Public**. Create it **empty** (no README, no `.gitignore`).
2. Locally: `git push -u origin master`
3. In **this** repo: **Settings → Pages → Source: GitHub Actions**. Do **not** click **Configure** on the suggested Jekyll/Static HTML templates (this repo already has `.github/workflows/pages.yml`).
4. Wait for the Actions run to go green. The calculator is at `https://sensorsini.github.io/lensFOV/`.

Optional later: a custom host such as `fov.jaerproject.org` is a CNAME on **this** repo, not on `jaer`.
