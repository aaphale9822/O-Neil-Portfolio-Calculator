# CAN SLIM Stock Analyzer & Portfolio Signal Calculator

An interactive, single-page stock screening and risk-management calculator modeled on **William J. O'Neil's** *The Successful Investor* and the **CAN SLIM** investment system.

## Features

- **Traffic-Light Buy/Sell/Wait Engine (Green / Yellow / Red):** Automatically evaluates market direction (`M`), quarterly & annual earnings growth (`C` & `A`), chart breakout timing (`N`), volume surges (`S`), relative strength (`L`), and institutional sponsorship (`I`).
- **Live Stock Quote Integration (Finnhub.io):** Enter any US stock ticker (`NVDA`, `MSFT`, `J`, `AAPL`, etc.) along with a free [Finnhub.io](https://finnhub.io) API key to pull live prices, 52-week highs, quarterly/annual EPS growth, and Return on Equity (ROE).
- **Automated 3:1 Risk-Reward Position Sizing:** Calculates exact share count, your mandatory **-7.5% hard stop-loss**, and your **+20% to +25% profit-taking zone**.
- **Interactive Visualizations:** Includes a **CAN SLIM Benchmark Radar Chart** and a **Price & Risk-Reward Map** powered by Chart.js.
- **Persistent Custom Watchlist:** Save custom tickers directly to your browser's `localStorage`.

## Quick Start (GitHub Pages)

1. Upload `index.html` and `README.md` to a new GitHub repository.
2. Go to **Settings -> Pages** in your repository.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` (or `master`) and `/ (root)`, and click **Save**.
4. Open your live GitHub Pages URL and paste your free Finnhub API key into the top bar to fetch live US equity quotes.

## Disclaimer

This tool is provided for educational and informational purposes only and does not constitute financial or investment advice.
