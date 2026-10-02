# Offline Budget Tracker

A **100% offline, single-file budget tracker** web app — no server, no login, no build step. Track income and expenses, organize spending by category, set budgets, and view monthly reports, all stored locally in your browser.

## Features

- 💰 **Transaction tracking** — log income and expenses with categories and notes
- 📊 **Category budgets** — set spending limits per category with visual progress
- 📈 **Monthly reports** — spending breakdowns and trends by month
- ⚙️ **Settings** — currency and date-format preferences
- 🔒 **Fully offline** — all data stays in `localStorage` on your device; works without internet
- 📱 **PWA-ready** — includes manifest and icon hooks (add your own `manifest.json` + icons)

## Tech Stack

- Single self-contained HTML file (`index.html`)
- Vanilla CSS (custom properties, responsive layout) + vanilla JavaScript
- Web Storage API (`localStorage`) for persistence
- No dependencies, no build tools

## Project Structure

```
index.html   — the entire app (HTML + CSS + JS in one file)
LICENSE      — license
```

## Getting Started

Just open the live site, or run it locally:

```bash
# any static server works, e.g.
npx serve .
```

Or simply double-click `index.html` — it runs offline.

## Deploy Notes

Deployed on **GitHub Pages** (branch `main`, root path). Any static host works — there's no build step.

## License

See [LICENSE](./LICENSE).

---

**Built by [Girish Lade](https://ladestack.in)** — solo founder of [LadeStack](https://ladestack.in).
