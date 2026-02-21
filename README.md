# EarningsEdge

**Earnings & Fundamentals Dashboard for Momentum Traders**

A Chrome extension that replaces ten browser tabs with one fast dashboard. Built for traders who study Qullamaggie, Stockbee, and Minervini-style setups — episodic pivots, earnings breakouts, and catalyst-driven momentum.

🌐 [Landing Page](https://earningsedgedev.github.io/earningsedge/) · ☕ [Support on Ko-fi](https://ko-fi.com/earningsedge)

---

## What You Get

### Stock Dashboard (8 tabs)
Search any US stock ticker and get instant access to:

- **Earnings** — 8 historical quarters + 4 forward estimates. Annual data: 5+ years + 4 forward. EPS, Revenue, %Change, %Surprise — all color-coded.
- **Analysts** — Consensus card (buy/hold/sell breakdown, price targets) + detailed ratings table with analyst names, firms, and actions.
- **Insiders** — Transaction table with cost basis, value, and position % calculations.
- **Short Interest** — Summary card + biweekly history (~24 data points, 1 year). Shares short, change, % of float, days to cover.
- **Funds** — Institutional ownership %, accumulation/distribution signal, net inflow, and top 15 recent filings.
- **Chart** — TradingView interactive chart.
- **News** — Aggregated from multiple sources. Sortable by date, filterable by source.

### ETF Dashboard (4 tabs)
Search an ETF ticker (SMH, XLK, GDX, etc.) and EarningsEdge auto-detects it:

- **Overview** — Performance across 9 timeframes (Daily through 5Y). Top 15 holdings with weight % and price changes. Click any holding to load its stock dashboard. Hover for chart preview.
- **Chart** — TradingView interactive chart.
- **News** — Aggregated news for the ETF.
- **Seeking Alpha** — News and analysis articles.

Key stats bar: AUM, Expense Ratio, Dividend Yield, Holdings count.

### Scans
- **Themes** — ETF theme scanner. Top-performing non-leveraged ETFs across 5 timeframes, tagged by sector (semiconductors, energy, gold miners, shipping, etc.). Sortable, filterable by AUM, volume, and tags. Great for finding what's working in the market right now.

### Other Features
- **Earnings Calendar** — Weekly view with BMO/AMC grouping, market cap filter, sortable columns.
- **Hover Chart Preview** — Hover any ticker in Calendar, Themes, or ETF Holdings to see a weekly candlestick chart (2 years) with volume and EMAs. Three size options.
- **Keyboard shortcuts** — Space/⌘K to search, 1-8 for tabs, Ctrl+R to refresh, C for calendar.
- **3 density modes** — Compact (default), Normal, Large.
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
| **Space** | Focus search bar |
| **⌘K / Ctrl+K** | Focus and select search bar |
| **1–8** | Switch stock tabs (1–4 for ETF tabs) |
| **Ctrl+R / ⌘R** | Force refresh current view |
| **C** | Open earnings calendar |
| **Escape** | Close settings / unfocus search |

Number keys only work when the search bar is not focused.

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
