# XAGUSD 1m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_980_054_rows-blue)](https://getdata.finance/datasets/xagusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xagusd)

### -> [**Download the full XAGUSD dataset on getdata.finance**](https://getdata.finance/datasets/xagusd)

**XAGUSD 1m OHLCV metals historical data** — ultra high-quality 1m OHLCV for **Silver / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Silver / US Dollar** (Metals)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xagusd) · **5,980,054** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `XAGUSD_1m.csv` (179,847 rows, `2026-03-26` -> `2026-09-25`, 16.13 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xagusd)** — **5,980,054** `1m` rows (full `1m`: 5,671,224), **11 timeframes**, `2009-02-24` -> `2026-09-25`.

## Download sample

**[XAGUSD_1m.csv](https://github.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/blob/main/XAGUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/main/XAGUSD_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xagusd-1m-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xagusd-1m-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xagusd](https://getdata.finance/datasets/xagusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xagusd))** |
|---|--:|---|
| Instrument | Silver / US Dollar · Metals | Silver / US Dollar · Metals |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 179,847 | **5,980,054** |
| Size | 16.13 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Period | `2026-03-26` -> `2026-09-25` | `2009-02-24` -> `2026-09-25` |
| File | `XAGUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Coverage report | — | [XAGUSD coverage](https://getdata.finance/coverage/xagusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xagusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/xagusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAGUSD_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:28:00+00:00 | 77.034 | 77.051 | 76.926 | 76.981 | 967 |
| 2026-03-26T02:29:00+00:00 | 76.981 | 77.004 | 76.937 | 76.959 | 662 |
| 2026-03-26T02:30:00+00:00 | 76.959 | 77.24 | 76.91 | 77.164 | 1729 |
| 2026-03-26T02:31:00+00:00 | 77.164 | 77.174 | 77.065 | 77.113 | 1285 |
| 2026-03-26T02:32:00+00:00 | 77.113 | 77.148 | 77.004 | 77.033 | 1057 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T20:40:00+00:00 | 64.09 | 64.1 | 64.087 | 64.1 | 29 |
| 2026-09-25T20:41:00+00:00 | 64.1 | 64.108 | 64.096 | 64.105 | 30 |
| 2026-09-25T20:42:00+00:00 | 64.105 | 64.12 | 64.105 | 64.11 | 40 |
| 2026-09-25T20:43:00+00:00 | 64.11 | 64.122 | 64.11 | 64.113 | 22 |
| 2026-09-25T20:44:00+00:00 | 64.113 | 64.126 | 64.113 | 64.114 | 39 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('XAGUSD_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAGUSD_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('XAGUSD_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **XAGUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xagusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **5,980,054** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAGUSD dataset on getdata.finance](https://getdata.finance/datasets/xagusd)**

---
*GetData · XAGUSD 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xagusd)*
