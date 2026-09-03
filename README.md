# XAGUSD 1m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_955_593_rows-blue)](https://getdata.finance/datasets/xagusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xagusd)

### -> [**Download the full XAGUSD dataset on getdata.finance**](https://getdata.finance/datasets/xagusd)

**XAGUSD 1m OHLCV metals historical data** — ultra high-quality 1m OHLCV for **Silver / US Dollar**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Silver / US Dollar** (Metals)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xagusd) · **5,955,593** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `XAGUSD_1m.csv` (55,440 rows, `2026-07-07` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/xagusd)** — **5,955,593** `1m` rows, **11 timeframes**, `2009-02-24` -> `2026-09-02`.

## Download sample

**[XAGUSD_1m.csv](https://github.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/blob/main/XAGUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/main/XAGUSD_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xagusd))** |
|---|--:|---|
| Instrument | Silver / US Dollar · Metals | Silver / US Dollar · Metals |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **5,955,593** |
| Period | `2026-07-07` -> `2026-09-02` | `2009-02-24` -> `2026-09-02` |
| File | `XAGUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Coverage report | — | [XAGUSD coverage](https://getdata.finance/coverage/xagusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xagusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`XAGUSD_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T18:56:00+00:00 | 60.624 | 60.624 | 60.484 | 60.563 | 905 |
| 2026-07-07T18:57:00+00:00 | 60.563 | 60.563 | 60.474 | 60.507 | 877 |
| 2026-07-07T18:58:00+00:00 | 60.507 | 60.557 | 60.49 | 60.525 | 607 |
| 2026-07-07T18:59:00+00:00 | 60.525 | 60.548 | 60.451 | 60.481 | 593 |
| 2026-07-07T19:00:00+00:00 | 60.481 | 60.52 | 60.379 | 60.379 | 1643 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 63.354 | 63.371 | 63.281 | 63.296 | 584 |
| 2026-09-02T01:57:00+00:00 | 63.296 | 63.312 | 63.251 | 63.256 | 573 |
| 2026-09-02T01:58:00+00:00 | 63.256 | 63.276 | 63.199 | 63.213 | 545 |
| 2026-09-02T01:59:00+00:00 | 63.213 | 63.266 | 63.213 | 63.23 | 593 |
| 2026-09-02T02:00:00+00:00 | 63.23 | 63.251 | 63.186 | 63.201 | 389 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full XAGUSD archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full XAGUSD dataset on getdata.finance](https://getdata.finance/datasets/xagusd)**
