# NAS100 2h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-53_771_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full NAS100 dataset on ork.ad**](https://ork.ad/)

**NAS100 2h OHLCV Stock index historical data** — ultra high-quality 2h OHLCV for **Nasdaq 100**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 2h OHLCV** for **Nasdaq 100** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`2h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **53,771** `2h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `2h` sample updated in sync

> **Sample on GitHub** · `NAS100_2h.csv` (2,295 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **53,771** `2h` rows (~3.11 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-08-19` → `2026-07-03`.

## Download sample

**[NAS100_2h.csv](https://github.com/ork-ad/nas100-2h-ohlcv-index-historical-data/blob/main/NAS100_2h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/nas100-2h-ohlcv-index-historical-data/main/NAS100_2h.csv)) · [GitHub Releases](https://github.com/ork-ad/nas100-2h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/nas100-2h-ohlcv-index-historical-data/](https://ork-ad.github.io/nas100-2h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Nasdaq 100 · Stock index | Nasdaq 100 · Stock index |
| Timeframes | `2h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 2h rows | 2,295 | **53,771** |
| Size | 0.16 MB | ~3.11 MB |
| Period | `2025-10-03` → `2026-07-03` | `2008-08-19` → `2026-07-03` |
| File | `NAS100_2h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`2h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `2h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `2h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NAS100_2h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T16:00:00Z | 24966.186369000003 | 24976.937444000003 | 24744.414194 | 24795.169269 | 212148.0 |
| 2025-10-03T18:00:00Z | 24795.169269 | 24866.05 | 24747.414494 | 24817.54 | 221406.0 |
| 2025-10-03T20:00:00Z | 24817.54 | 24827.54 | 24795.29 | 24806.84 | 12960.0 |
| 2025-10-05T22:00:00Z | 24806.84 | 24917.341485 | 24806.84 | 24897.469498000002 | 29814.0 |
| 2025-10-06T00:00:00Z | 24897.469498000002 | 24908.220573000002 | 24881.337885 | 24906.720423000002 | 29886.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T08:00:00Z | 29649.2 | 29703.55 | 29632.79 | 29675.55 | 66483.0 |
| 2026-07-03T10:00:00Z | 29675.55 | 29712.42 | 29664.3 | 29705.2 | 45286.0 |
| 2026-07-03T12:00:00Z | 29705.2 | 29759.83 | 29680.55 | 29744.2 | 83448.0 |
| 2026-07-03T14:00:00Z | 29744.2 | 29750.6 | 29689.95 | 29711.2 | 79049.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('NAS100_2h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NAS100_2h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('NAS100_2h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='2h')
print(pf.stats())
```

## Download full data

The complete **NAS100** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **53,771** rows at `2h`, plus all other timeframes in the same ZIP.

**[→ Get the full NAS100 dataset on ork.ad](https://ork.ad/)**

---
*GetData · NAS100 2h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*