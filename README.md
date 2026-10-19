# Base Set Unlimited Card List

One-page scroll gallery of all **102** English Pokémon Base Set Unlimited cards.

**Live site:** https://swishish.github.io/Base-Set-Unlimited-Cheatsheet/

- Cards-per-row control: 2–5 columns
- ☐ Owned checkboxes (saved in the browser via `localStorage`)
- HKD prices (FX USD×7.85) with PriceCharting and TCGPlayer links
- Holo/Rare **NM** loads live from [Box EV `cheatsheet.json`](https://swishish.github.io/Pokemon-Box-EV/data/market-vintage/cheatsheet.json) (`printings.base-unlimited`); LP / PSA 10 stay on the embedded snapshot. Offline/cache falls back to that snapshot. Machamp #008 shows **缺口** when `usd` is missing.

Self-contained `index.html` (card images are embedded). Serve with GitHub Pages from **`main` / `/(root)`** — Settings → Pages → Deploy from a branch.
