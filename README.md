# 🌍 Global Markets Explorer — MSCI 2023

An interactive, single-page educational dashboard comparing four major MSCI equity indices: **USA**, **Europe**, **AC Asia**, and **Brazil**. Built for an introductory business finance course to make index data accessible and visually engaging.

---

## 📖 Overview

This project turns raw MSCI Index Factsheet data (January 2023) into a tabbed, browser-based dashboard with live charts. No frameworks, no database, no build step — just one HTML file you can open anywhere.

The goal is to help students without a finance background understand:
- What stock market indices are and what they represent
- How sector composition reflects a real economy
- How to interpret risk-adjusted returns (Sharpe ratio, volatility, drawdown)
- The difference between growth and value markets (P/E, dividend yield)

---

## 📊 Data Covered

| Index | Region | Companies | Market Cap |
|-------|--------|-----------|------------|
| MSCI USA | North America | 625 | ~$36.1T |
| MSCI Europe | 15 European countries | 425 | ~$10.0T |
| MSCI AC Asia | 11 Asian markets | 1,422 | ~$9.4T |
| MSCI Brazil | Latin America | 48 | ~$355B |

> Data sourced from MSCI Inc. Index Factsheets — January 2023.

---

## 🗂 Sections

| Tab | Contents |
|-----|----------|
| 📖 The Documents | What MSCI indices are, market introductions, key concept glossary |
| 📏 Market Scale | Total cap, company count, largest vs. median size comparisons |
| 🏭 Sector Breakdown | Stacked bar, radar chart, full comparison table with inline bars |
| ⚡ Risk & Performance | Sharpe ratio, volatility, risk-reward scatter, max drawdown |
| 💰 Valuation | P/E (trailing & forward), dividend yield, growth vs. value bubble map, P/BV |
| 🎓 Key Takeaways | 6 numbered findings connecting data back to core finance concepts |

---

## 🚀 Usage

No installation required.

```bash
# Just open the file in any modern browser
open msci_explorer.html
```

Or host it anywhere static — GitHub Pages, Netlify, a university file server.

---

## 🛠 Tech Stack

- **Pure HTML/CSS/JS** — zero dependencies, zero build step
- **[Chart.js 4.4.1](https://www.chartjs.org/)** — loaded via CDN for all charts
- **[Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)** — via Google Fonts
- All data is hard-coded in the file — no API calls, no backend

> Charts load lazily per tab, so the page is fast even with 13 charts total.

---

## 📁 File Structure

```
/
└── msci_explorer.html   # Entire app — one self-contained file
└── README.md
```

---

## ⚠️ Disclaimer

This dashboard is for **educational purposes only**. Data is sourced from MSCI Inc. factsheets dated January 2023. Past performance is not indicative of future results. Return figures across indices use different methodologies (Gross / Price / Net) and are not directly comparable — this is noted explicitly in the Risk & Performance section.

---

## 📄 License

For academic and educational use only. MSCI index data is the property of MSCI Inc.
