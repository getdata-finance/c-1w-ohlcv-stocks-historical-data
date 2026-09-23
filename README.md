# C 1w OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-286_rows-blue)](https://getdata.finance/datasets/c) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/c)

### -> [**Download the full C dataset on getdata.finance**](https://getdata.finance/datasets/c)

**C 1w OHLCV stocks historical data** — ultra high-quality 1w OHLCV for **Citigroup**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **Citigroup** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/c) · **286** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `C_1w.csv` (106 rows, `2024-09-12` -> `2026-09-17`, 10.64 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/c)** — **286** `1w` rows (full `1m`: 526,299), **11 timeframes**, `2021-04-01` -> `2026-09-17`.

## Download sample

**[C_1w.csv](https://github.com/getdata-finance/c-1w-ohlcv-stocks-historical-data/blob/main/C_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/c-1w-ohlcv-stocks-historical-data/main/C_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/c-1w-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/c-1w-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/c-1w-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/c](https://getdata.finance/datasets/c)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/c))** |
|---|--:|---|
| Instrument | Citigroup · US stocks | Citigroup · US stocks |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 106 | **286** |
| Size | 10.64 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/c) |
| Period | `2024-09-12` -> `2026-09-17` | `2021-04-01` -> `2026-09-17` |
| File | `C_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/c) |
| Coverage report | — | [C coverage](https://getdata.finance/coverage/c) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/c)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/c) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`C_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-12T00:00:00+00:00 | 57.19 | 60.84 | 56.78 | 59.84 | 140784 |
| 2024-09-19T00:00:00+00:00 | 59.84 | 63.12 | 59.84 | 60.34 | 109620 |
| 2024-09-26T00:00:00+00:00 | 60.34 | 62.6 | 60.34 | 61.98 | 133705 |
| 2024-10-03T00:00:00+00:00 | 61.98 | 64.21 | 60.87 | 64.08 | 99249 |
| 2024-10-10T00:00:00+00:00 | 64.08 | 66.98 | 62.48 | 64.19 | 118755 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 132.81 | 136.8 | 129.46 | 133.54 | 67022 |
| 2026-08-27T00:00:00+00:00 | 133.54 | 136.07 | 129.91 | 134.17 | 76603 |
| 2026-09-03T00:00:00+00:00 | 134.17 | 138.42 | 133.71 | 137.79 | 54535 |
| 2026-09-10T00:00:00+00:00 | 137.79 | 141.05 | 130.93 | 132.87 | 96909 |
| 2026-09-17T00:00:00+00:00 | 132.87 | 135.59 | 130.18 | 132.31 | 75165 |

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

df = pd.read_csv('C_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('C_1w.csv', parse_dates=['datetime'])
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

df = pd.read_csv('C_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **C** archive on **[getdata.finance](https://getdata.finance/datasets/c)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **286** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full C dataset on getdata.finance](https://getdata.finance/datasets/c)**

---
*GetData · C 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/c)*
