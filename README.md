# Offline Budget Tracker

A free, offline-first personal budget tracker that runs entirely in your browser — no account, no server, no internet required. Track income and expenses, organize them into categories, set budgets per category and period, and visualize spending with built-in charts.

## Features

- **Add transactions** — record income and expense transactions with amount, category, and date
- **Custom categories** — create income/expense categories with custom colors
- **Budgets** — set budget limits per category and period (weekly / monthly / yearly)
- **Budget overview dashboard** — see at a glance how much of each budget is spent vs remaining
- **Spending charts** — bar chart visualization of spending with a color-coded legend
- **Transaction history** — full list of all transactions with edit/delete support
- **100% offline** — single self-contained HTML file; all data stored in the browser via IndexedDB
- **Privacy-first** — your data never leaves your device; clear-data option built in

## Tech stack

- Vanilla HTML + CSS + JavaScript — zero dependencies, no build step
- IndexedDB for local persistence
- Canvas-based charts (no chart library needed)

## Quick start

Open `index.html` in any modern browser — that's it. No server, no install.

```bash
# optionally serve locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

To publish: this repo is a plain static site and is deployed via GitHub Pages.

## Project structure

```
Offline-Budget-Tracker/
├── index.html                  # the entire app (single file, no dependencies)
├── "Offline Budget Tracker html"  # original single-file source
├── README.md
└── LICENSE
```

## Data & storage

All records (transactions, categories, budgets) live in your browser's IndexedDB under this site's origin. Nothing is uploaded anywhere. Use the in-app **Clear Data** option to wipe everything.

## Roadmap / ideas

- [ ] Export / import data (CSV / JSON backup)
- [ ] Recurring transactions
- [ ] Multi-currency support
- [ ] Monthly summary reports

## 👤 Author & Maintainer

**Built by Girish Lade**  
- GitHub: [@girishlade111](https://github.com/girishlade111)
- Portfolio: [ladestack.in](https://ladestack.in)
