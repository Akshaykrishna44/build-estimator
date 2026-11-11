# Buildwise · Construction Estimator

A single-page web app that estimates construction cost, materials, man-hours, skilled workers per trade and water needs, from foundation to finish. Rates follow the Tamil Nadu PWD Schedule of Rates 2025-26 where marked; all other rates and work norms are illustrative.

No build step and no dependencies: everything is in `index.html`.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.

## Deploy
A GitHub Pages workflow is included. After pushing, go to **Settings → Pages → Source: GitHub Actions**.

## Notes
- Indicative estimates only; not a quotation or engineering advice.
- Edits made under **Customize** are stored in the browser (localStorage), not in the repo.
