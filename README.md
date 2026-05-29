# Loewfizzle's Bitcoin Dashboard

**Codename:** NEURAL-07 / "Chrome Veil"

A dark, neon-drenched, fully interactive cyberpunk Bitcoin command center that feels like it was ripped straight out of a 2077 megacorp neural interface.

## Features

- **Live Bitcoin Price** — Massive glowing display with real-time 24h change, directional flash animations (green/red), and sats equivalent.
- **Fear & Greed Index** — Beautiful analogue SVG gauge with smooth needle and five cyberpunk color zones.
- **Strategy Bitcoin Reserve** — Animated Saylor holdings tracker with live USD value, average acquisition cost, recent purchases grid, and fully functional "ACQUIRE MORE BTC" button (with confetti and toast).
- **Network Intelligence** — Real-time hashrate, difficulty + adjustment, and precise halving countdown.
- **30-Day Chart** — Cyberpunk-styled interactive Chart.js visualization.
- **Advanced Robustness** — Per-source exponential backoff, staleness indicators, loading states, and graceful degradation with clear "Data Unavailable" messaging.
- **Mobile Optimized** — Fully responsive experience with thoughtful scaling across devices.

## How to Use

Just open `index.html` in any modern browser (Chrome, Firefox, Edge, etc.). No build step or dependencies required.

The dashboard fetches live data from public APIs on load and continues polling in the background.

## Data Sources

- **Price & Chart** — [CoinGecko](https://www.coingecko.com/)
- **Fear & Greed Index** — [Alternative.me](https://alternative.me/crypto/fear-and-greed-index/)
- **Blockchain Data** — [Mempool.space](https://mempool.space/)

## Tech Stack

- Single self-contained HTML file
- Tailwind CSS 3.4 (via CDN)
- Chart.js (via CDN)
- Vanilla JavaScript + Fetch API
- No build tools, no external dependencies at runtime

## Version

**v1.0** — Final Polish Release  
May 2026

## Credits

Built with heavy assistance from Grok (xAI) as an ambitious single-file creative engineering project.

---

*For authorized megacorp personnel only.*