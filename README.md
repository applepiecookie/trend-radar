# Trend Radar · SAFF & Co.

Trend signal radar for fragrance, packaging and consumer behavior, for the Product Development team.

- `index.html` — the website (GitHub Pages).
- `data/trends.json` — all trend signals (adoption stage, strength, Indonesia fit).
- `data/mentions.json` — mention log per source, used to compute momentum.
- `data/brief.json` — today's SAFF brief: takeaways, actions, calendar, competitors, sources.
- `data/portfolio.json` — SAFF product names, scent family and notes (public product information only).
- `data/opportunities.json` — product concepts built on SAFF's line.
- `data/market_share.json` — Shopee perfume market share as published by Compas.
- `data/meta.json` — last update time.

Data is updated automatically every morning by a Claude scheduled task.

## Brand Health (`/brand-health/`)

Daily brand health monitor for SAFF & Co. vs HMNS, Mykonos, Alchemist and Onix: https://applepiecookie.github.io/trend-radar/brand-health/

- `brand-health/index.html` — the page.
- `brand-health/data/ratings.json` — daily Female Daily rating snapshots per brand (top 16 products, review-weighted).
- `brand-health/data/mentions.json` — public mentions with sentiment and experience themes.
- `brand-health/data/marketplace.json` — aggregated totals from Shopee/Tokopedia review exports (Google Drive folder "Brand Health – Marketplace Exports (SAFF & Co.)"). Aggregates only, never buyer names, order IDs or quotes.
- `brand-health/data/brief.json` — headline, insights and recommendations for management.
- `brand-health/data/meta.json` — last update time.

Updated every evening by a Claude scheduled task.
