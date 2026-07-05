# Portfolio Optimization - Time Series Forecasting

Time series forecasting and portfolio optimization project for GMF Investments.
Covers data extraction, EDA, ARIMA/LSTM forecasting, Modern Portfolio Theory
optimization, and strategy backtesting for TSLA, BND, and SPY.

## Project Structure

```
portfolio-optimization/
├── data/processed/       Processed data files
├── notebooks/            Jupyter notebooks for each task
├── src/                  Reusable source modules
├── tests/                Unit tests
├── scripts/              Standalone scripts
```

## Setup

1. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/Scripts/activate
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Tasks

- Task 1: Data extraction, cleaning, EDA, stationarity testing
- Task 2: ARIMA/SARIMA and LSTM forecasting models
- Task 3: Future forecast generation and trend analysis
- Task 4: Portfolio optimization using Modern Portfolio Theory
- Task 5: Strategy backtesting against a benchmark

## Data

Historical daily data for TSLA, BND, and SPY from January 1, 2015 to
June 30, 2026, sourced via the yfinance library.
