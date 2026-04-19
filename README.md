# alpha-trend-ema

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-trend-ema/blob/main/notebooks/alpha_trend_ema.ipynb)

> EMA trend-following alpha signal

> A simple but durable trend-following signal: long when the 50-day EMA is above the 200-day EMA (uptrend), short when the 50-day is below the 200-day (downtrend). This captures the broad directional regime for each ticker and acts as a foundation for cross-strategy analysis.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | L1/S1 signal generation |
| 4 | Returns & performance |
| 5 | Per-ticker breakdown |
| 6 | Parameter sensitivity (fast/slow EMA spans) |
| 7 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

