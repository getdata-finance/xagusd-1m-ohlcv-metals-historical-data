# XAGUSD 1m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_638_575_rows-blue)](https://getdata.finance/datasets/xagusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xagusd)

### -> [**Download the full XAGUSD dataset on getdata.finance**](https://getdata.finance/datasets/xagusd)

**XAGUSD 1m OHLCV metals historical data** — ultra high-quality 1m OHLCV for **Silver / US Dollar**. Global spot sessions — Asia, Europe and US coverage for precious metals trading. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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
- **Global spot sessions — Asia, Europe and US coverage for precious metals trading**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/xagusd) · **5,638,575** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `XAGUSD_1m.csv` (177,423 rows, `2026-02-01` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/xagusd)** — **5,638,575** `1m` rows (~425.78 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2009-02-24` -> `2026-07-30`.

## Download sample

**[XAGUSD_1m.csv](https://github.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/blob/main/XAGUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/main/XAGUSD_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/xagusd-1m-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xagusd-1m-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xagusd-1m-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xagusd](https://getdata.finance/datasets/xagusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xagusd))** |
|---|--:|---|
| Instrument | Silver / US Dollar · Metals | Silver / US Dollar · Metals |
| Timeframes | `1m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 177,423 | **5,638,575** |
| Size | 15.37 MB | ~425.78 MB |
| Period | `2026-02-01` -> `2026-07-31` | `2009-02-24` -> `2026-07-30` |
| File | `XAGUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Coverage report | — | [XAGUSD coverage](https://getdata.finance/coverage/xagusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xagusd)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/xagusd) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAGUSD_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-01T23:01:00+00:00 | 84.429 | 84.429 | 80.451 | 80.859 | 368 |
| 2026-02-01T23:02:00+00:00 | 80.859 | 82.851 | 80.616 | 82.841 | 538 |
| 2026-02-01T23:03:00+00:00 | 82.841 | 83.274 | 81.714 | 82.361 | 792 |
| 2026-02-01T23:04:00+00:00 | 82.361 | 82.755 | 81.478 | 82.145 | 991 |
| 2026-02-01T23:05:00+00:00 | 82.145 | 82.276 | 81.062 | 81.274 | 543 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T20:40:00+00:00 | 60.17445 | 60.17945 | 60.16245 | 60.17845 | 84 |
| 2026-07-31T20:41:00+00:00 | 60.17845 | 60.18545 | 60.17445 | 60.18445 | 101 |
| 2026-07-31T20:42:00+00:00 | 60.18445 | 60.18445 | 60.15445 | 60.15445 | 55 |
| 2026-07-31T20:43:00+00:00 | 60.15445 | 60.15545 | 60.12945 | 60.14345 | 72 |
| 2026-07-31T20:44:00+00:00 | 60.14345 | 60.14345 | 60.09945 | 60.12945 | 76 |

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
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
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

The complete **XAGUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xagusd)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **5,638,575** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAGUSD dataset on getdata.finance](https://getdata.finance/datasets/xagusd)**

---
*GetData · XAGUSD 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xagusd) · 2026-08-04 UTC*
