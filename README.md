# Kalshi perps: volume, incentives and liquidity

Materials for the working paper **"Incentives at Play: Fee-Induced Volume on a Regulated Perpetual Futures Venue"** (preliminary draft).

## Contents

- **Working paper (PDF):** [`kalshi_working_paper_25_09_orderbook.pdf`](kalshi_working_paper_25_09_orderbook.pdf)
- **Interactive dashboard:** <https://andreguettler.github.io/kalshi_perps/>
  The dashboard (`index.html`) is a self-contained snapshot. It has no external dependencies and also works when opened locally.

## What the dashboard shows

- **Fixed-size trades:** the share of daily dollar volume in repeated trade sizes, around the rebate cut, the press flag and the end of the volume incentive program on 13 October 2026.
- **Turnover:** daily volume relative to open interest on Kalshi versus Binance, and against maximum leverage.
- **Liquidity and costs:** order-book spreads, depth and sweep costs from 23 September to 23 October 2026, and the round-trip cost of a $250k trade.
- **Benchmark:** CME bitcoin futures open interest and turnover.

## Data sources

Kalshi API (candlesticks, public trades, margin API), Binance USD-M public data archive and API, Hyperliquid API, an order-book collector for Kalshi and Binance (BTC, ETH, gold, silver), and CFTC Commitments of Traders (CME). The dashboard reflects data up to 24 October 2026.

## Status and citation

Preliminary work in progress; figures and conclusions may change.

**Andre Guettler**, Ulm University
