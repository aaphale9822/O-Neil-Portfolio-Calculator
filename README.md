# CAN SLIM Multi-Portfolio Stock Analyzer & Signal Calculator

An advanced single-page stock screening and risk-management web application modeled on **William J. O'Neil's** *The Successful Investor* and the **CAN SLIM** investment system, upgraded with **multi-portfolio management**.

## Key Features

- **Multiple Portfolios:** Create, rename, switch between, and delete multiple independent portfolios (e.g., *Tech Growth Watchlist*, *Long-Term Dividend Core*, *Speculative Plays*), each with its own total capital pool.
- **Dynamic Stock Management per Portfolio:** Add any US stock ticker to your active portfolio, with automated live quote fetching via a free **Finnhub.io** API key.
- **Traffic-Light Signal Engine (Green / Yellow / Red):** Automatically evaluates CAN SLIM rules (`M`, `C`, `A`, `N`, `S`, `L`, `I`) for whichever stock you select in your portfolio list.
- **Automated Risk & Position Sizing:** Calculates exact share allocation based on your portfolio capital and target position weight, alongside your **-7.5% hard stop-loss** and **+20% to +25% profit targets**.
- **Dual Interactive Charts:** Instant radar chart benchmark comparison and 3:1 reward-to-risk price map powered by Chart.js.
- **Persistent Local Storage:** All portfolios and custom tickers are automatically saved in your browser's `localStorage`.

## Quick Start (GitHub Pages)

1. Upload `index.html` and `README.md` to your GitHub repository.
2. Go to **Settings -> Pages** and enable GitHub Pages on the `main` branch.
3. Open your live URL and paste your free [Finnhub.io](https://finnhub.io) API key at the top to fetch live US equity quotes.
