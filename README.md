# Build Estimator

React + Vite app: construction cost, materials (base to finished), man-hours, workers per trade and water needs, plus Projects, Measurements, PWD rate references, Documents and Reports screens.

```bash
npm install
npm run dev       # http://localhost:5173
npm run build     # static output in dist/
```

## Structure
- `src/engine/calc.js` pure estimating function (no DOM); `src/data/` rates, norms and project-type multipliers.
- `src/views/` one component per screen; `src/styles.css` single neutral light theme.
- State is saved in the browser (localStorage). Push to `main` to deploy via the GitHub Pages workflow (Settings → Pages → Source: GitHub Actions).

Indicative estimates only. Rates marked TN PWD SOR follow the Schedule of Rates 2025-26; all other rates and norms are illustrative.
