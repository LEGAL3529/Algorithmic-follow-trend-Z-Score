# Z-Score Mean-Reversion Strategy on NQ Futures
This repository explores a mean-reversion trading strategy based on the Z-score of price deviations from a moving average, applied to Nasdaq (NQ) futures.

## 📈 Strategy Logic
- **Signal:** Long when Z-score < -threshold, Exit when Z-score > 0
- **Calculation:** Z = (Price - Rolling Mean) / Rolling Std
- **Window size:** Adjustable for testing (e.g., 20-day mean and std)

## 🔍 What’s Inside
- Z-score calculation using pandas rolling stats
- Signal generation and position tracking
- Backtesting engine: log returns, strategy returns
- Equity curve and performance metrics
