# Quantitative Strategy Pipeline

A Python-based framework for S&P 500 trend-following analysis.

## Project Structure
- **Data Engine**: Downloads and cleans OHLCV data.
- **Feature Engineering**: Calculates log returns, volatility, and SMA ratios.
- **Backtester**: Evaluates Golden Cross performance metrics.
- **Monitor**: Real-time signal generation for high-Sharpe candidates.

## How to Use
1. Run the data engine to sync tickers.
2. Run feature engineer to process raw Parquet files.
3. Use the Backtester to generate the performance leaderboard.