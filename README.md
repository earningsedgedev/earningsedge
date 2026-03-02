# EarningsEdge

**Earnings & Fundamentals Dashboard for Momentum Traders**

A Chrome extension that replaces ten browser tabs with one fast dashboard. Built for traders who study Qullamaggie, Stockbee, and Minervini-style setups — episodic pivots, earnings breakouts, and catalyst-driven momentum.

🌐 [Landing Page](https://earningsedgedev.github.io/earningsedge/) · ☕ [Support on Ko-fi](https://ko-fi.com/earningsedge)

---

## What You Get

### Stock Dashboard (7 tabs)
Search any US stock ticker and get instant access to:

- **Earnings** — Side-by-side layout: TradingView chart (left, 55%) + earnings data (right, 45%). Chart loads eagerly at search. Quarterly: 8 historical + 4 forward estimates. Annual: 5+ years + 4 forward. EPS, Revenue, %Change, %Surprise — all color-coded.
- **News** — Aggregated from multiple sources. Sortable by date, filterable by source.
- **Analysts** — Consensus card (buy/hold/sell breakdown, price targets) + detailed ratings table merging data from multiple sources. Analyst names, firms, actions, and price targets.
- **Insiders** — Corporate insider transactions with cost basis, value, position %, and SEC filing links. Includes congressional/politician trades (tagged with party affiliation and state).
- **Funds** — Institutional ownership %, accumulation/distribution signal, net inflow, and top 15 recent filings.
- **Short Interest** — Summary card + biweekly history (~24 data points, 1 year). Shares short, change, % of float, days to cover.
- **Analysis** — In-depth articles, earnings call transcripts, and press releases.

**Key stats bar** — 7×2 grid: Price, Mkt Cap, P/E, P/S, Avg Vol, Rel Vol, 52W High | Earnings, ADR%(20), Float, Short Float, Days to Cover, Inst Own, Perf YTD. ADR% uses Qullamaggie's formula. 52W High color-coded green when within 10% (Minervini zone).

**Optional Chart tab** — Setting in ⚙️ (default OFF). When enabled, adds a separate full-width Chart tab while the Earnings tab reverts to a side-by-side Quarterly/Annual layout.

### ETF Dashboard (4 tabs)
Search an ETF ticker (SMH, XLK, GDX, etc.) and EarningsEdge auto-detects it:

- **Overview** — Performance across 9 timeframes (Daily through 5Y) + TradingView chart.
- **Holdings** — Top 15 holdings with weight %, daily/weekly/monthly price changes. Click any holding to load its stock dashboard. Hover for chart preview.
- **News** — Aggregated news for the ETF.
- **Analysis** — News and analysis articles.

Key stats bar: AUM, Expense Ratio, Dividend Yield, Holdings count.

### Scanners
- **Movers** — Biggest gainers and losers across three sessions: Pre-Market, Market Hours, After-Hours. 200 tickers per direction. Columns include Mkt Cap, Chg%, ADR%, Volume, Float, Short%, Days to Cover, and News links. Earnings date badges for tickers reporting yesterday/today/tomorrow. Filterable by market cap, volume, change %, and ADR%.
- **Stock Themes** — 40 themes, 268 sub-themes. Two views: Themes (grouped, collapsible) and Sub-themes (flat sortable). 8 timeframes. Expandable sub-themes show individual ticker performance.
- **Theme ETFs** — Top-performing non-leveraged ETFs across 5 timeframes. Tagged by sector (semiconductors, energy, gold miners, shipping, etc.). Sortable, filterable by AUM, volume, and tags.
- **Industry RS** — Sector and industry relative strength rankings. Two views: Sectors (grouped with expandable industries) and Industries (flat sortable). RS score badges, breadth bars, trend arrows, and leader tickers. Hover chart on tickers.

### Earnings Calendar
Weekly view with BMO/AMC grouping, market cap filter, ADR% column, and sortable columns. Adaptive price column: PM Chg% (pre-market), Chg% (market hours), AH Chg% (after-hours) — auto-detected by session. Hover any ticker for a chart preview. Lazy per-day loading for fast open times.

### Other Features
- **Command Palette** — ⌘K / Space / click search bar to open. Autocomplete for US tickers, recent searches with relative time, navigation to Calendar/Movers/Themes/Sector RS. Keyboard-driven: ↑↓ to navigate, Enter to select, Esc to close.
- **Hover Chart Preview** — Hover any ticker in Calendar, Themes, Industry RS, ETF Holdings, Theme ETFs, or Movers to see a weekly candlestick chart (2 years) with volume and EMAs. Three size options.
- **Keyboard shortcuts** — Space/⌘K for command palette, 1-7 for stock tabs (1-4 for ETF tabs), Ctrl+R to refresh.
- **2 density modes** — Compact (default) and Normal.
- **4 date formats** — ISO, US, EU, US Written.
- No API keys required. No account needed. Install and go.

---

## Install

Installation takes under a minute.

### Step 1: Download
Go to the [Releases](https://github.com/earningsedgedev/earningsedge/releases) page and download the latest `.zip` file.

### Step 2: Unzip
Extract the zip file. You'll get a folder called `EarningsEdge-Extension`.

### Step 3: Load in Chrome
1. Open `chrome://extensions` in your browser
2. Enable **Developer mode** (toggle in the top right corner)
3. Click **Load unpacked**
4. Select the `EarningsEdge-Extension` folder

### Step 4: Pin it
Click the puzzle piece icon in Chrome's toolbar and pin EarningsEdge for quick access.

That's it. Click the icon and start searching tickers.

---

## Update

1. Download the new release zip from [Releases](https://github.com/earningsedgedev/earningsedge/releases)
2. Unzip and replace the old `EarningsEdge-Extension` folder with the new one
3. Go to `chrome://extensions` and click the **reload** button (↻) on EarningsEdge

Your settings (density, date format, chart size) are preserved across updates.

---

## Uninstall

1. Go to `chrome://extensions`
2. Find EarningsEdge
3. Click **Remove** and confirm

This removes the extension and all stored data (cache, settings). You can also delete the `EarningsEdge-Extension` folder from your computer.

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| **Space** / **⌘K** | Open command palette |
| **1–7** | Switch stock tabs (1–4 for ETF tabs) |
| **Ctrl+R** / **⌘R** | Force refresh current view |
| **Escape** | Close palette / settings |

Number keys only work when the command palette is not open.

---

## Permissions

EarningsEdge requests the following Chrome permissions:

| Permission | Why |
|-----------|-----|
| **storage** | Save your settings (density, date format, chart size) and cache data locally |
| **scripting** | Inject content scripts to extract data from financial pages |
| **tabs** | Open and manage background tabs for data fetching |
| **Host permissions** | Access financial data sites to fetch earnings, analyst ratings, short interest, and other data |

EarningsEdge does **not** read your browsing history, modify other websites, or access any personal data. All data processing happens locally in your browser.

---

## Privacy

- **No account required** — EarningsEdge works without sign-up or login.
- **No personal data collected** — We don't know who you are.
- **Anonymous usage analytics** — Basic event tracking (searches, page views) via GA4 to understand which features are used. No personally identifiable information. No ticker data is tracked.
- **Local processing** — All data fetching and rendering happens in your browser. There is no central server.

---

## FAQ

**Does this work with non-US stocks?**
Currently optimized for US-listed tickers. Some ADRs work. International exchanges are not supported yet.

**Why manual install instead of the Chrome Web Store?**
This keeps the project independent and avoids Chrome Web Store review overhead during active development.

**Is this free?**
Yes. If you find it useful, you can [support development on Ko-fi](https://ko-fi.com/earningsedge).

**Data seems stale or missing for a ticker?**
Press **Ctrl+R** (or **⌘R** on Mac) to force a fresh fetch. Some tickers with unusual listings may have incomplete data.

**Can I use this on Edge or Brave?**
It should work on any Chromium-based browser (Edge, Brave, Arc, Opera) using the same manual install process. Not tested extensively.

---

## Support

EarningsEdge is built and maintained by a solo developer and active trader. If it saves you time during earnings season, consider buying me a coffee.

☕ [ko-fi.com/earningsedge](https://ko-fi.com/earningsedge)

Bug reports and feature requests: [GitHub Issues](https://github.com/earningsedgedev/earningsedge/issues)

Contact: earningsedge.dev@gmail.com

---

## License

Source code is provided as-is for personal use. See [LICENSE](LICENSE) for details.
