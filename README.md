# NAS100 3m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_931_713_rows-blue)](https://getdata.finance/datasets/nas100) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/nas100)

### -> [**Download the full NAS100 dataset on getdata.finance**](https://getdata.finance/datasets/nas100)

**NAS100 3m OHLCV index historical data** — ultra high-quality 3m OHLCV for **NASDAQ 100**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **NASDAQ 100** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/nas100) · **1,931,713** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `NAS100_3m.csv` (60,208 rows, `2026-03-12` -> `2026-09-11`, 5.04 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/nas100)** — **1,931,713** `3m` rows (full `1m`: 5,050,229), **11 timeframes**, `2009-01-02` -> `2026-09-11`.

## Download sample

**[NAS100_3m.csv](https://github.com/getdata-finance/nas100-3m-ohlcv-index-historical-data/blob/main/NAS100_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/nas100-3m-ohlcv-index-historical-data/main/NAS100_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/nas100-3m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/nas100-3m-ohlcv-index-historical-data/](https://getdata-finance.github.io/nas100-3m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/nas100](https://getdata.finance/datasets/nas100)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/nas100))** |
|---|--:|---|
| Instrument | NASDAQ 100 · Index | NASDAQ 100 · Index |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 60,208 | **1,931,713** |
| Size | 5.04 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/nas100) |
| Period | `2026-03-12` -> `2026-09-11` | `2009-01-02` -> `2026-09-11` |
| File | `NAS100_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/nas100) |
| Coverage report | — | [NAS100 coverage](https://getdata.finance/coverage/nas100) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/nas100)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/nas100) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NAS100_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T02:30:00+00:00 | 24734.73 | 24739.11 | 24726.86 | 24731.86 | 3015 |
| 2026-03-12T02:33:00+00:00 | 24731.86 | 24734.48 | 24709.23 | 24711.48 | 3354 |
| 2026-03-12T02:36:00+00:00 | 24711.48 | 24711.48 | 24687.48 | 24691.36 | 4789 |
| 2026-03-12T02:39:00+00:00 | 24691.36 | 24713.36 | 24683.98 | 24708.36 | 4164 |
| 2026-03-12T02:42:00+00:00 | 24708.36 | 24715.86 | 24705.48 | 24710.73 | 3606 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T20:30:00+00:00 | 29361.84 | 29370.84 | 29361.47 | 29370.59 | 743 |
| 2026-09-11T20:33:00+00:00 | 29370.59 | 29370.97 | 29366.47 | 29368.09 | 696 |
| 2026-09-11T20:36:00+00:00 | 29368.09 | 29373.47 | 29366.34 | 29372.59 | 734 |
| 2026-09-11T20:39:00+00:00 | 29372.59 | 29373.59 | 29366.47 | 29367.09 | 768 |
| 2026-09-11T20:42:00+00:00 | 29367.09 | 29369.09 | 29363.34 | 29366.79 | 907 |

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

df = pd.read_csv('NAS100_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NAS100_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('NAS100_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **NAS100** archive on **[getdata.finance](https://getdata.finance/datasets/nas100)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,931,713** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full NAS100 dataset on getdata.finance](https://getdata.finance/datasets/nas100)**

---
*GetData · NAS100 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/nas100)*
