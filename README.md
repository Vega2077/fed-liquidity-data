# Fed Liquidity Data Mirror

Public data mirror for the fed-liquidity-monitor dashboard. Auto-updated on weekdays
(07:00 Beijing time) by GitHub Actions from FRED public data (H.4.1 / SOFR / ON RRP etc.).

- `data/liquidity.json` — everything the dashboard needs (net liquidity = total assets − TGA − ON RRP)
- Source project: private. All content here is public-domain FRED data.

The deployed dashboard fetches this file on every page load via jsDelivr/raw.githubusercontent.com.
