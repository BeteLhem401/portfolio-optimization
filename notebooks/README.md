# Notebooks

- task1_eda.ipynb: Data extraction, cleaning, EDA, stationarity testing, risk metrics
- task2_forecasting_models.ipynb: ARIMA/SARIMA and LSTM model development
- task3_future_forecast.ipynb: Future forecast generation and trend analysis
- task4_portfolio_optimization.ipynb: Efficient Frontier and portfolio recommendation
- task5_backtesting.ipynb: Strategy backtest vs benchmark
## Task 1 Status: Complete

Data fetched for TSLA, BND, SPY (2015-01-02 to 2026-06-29, 2888 rows each,
no missing values). Completed:

- Data extraction via yfinance, combined into long-format DataFrame
- Cleaning (dtype check, missing value check, forward-fill)
- Summary statistics per asset
- Daily returns, 30-day rolling mean/std
- EDA visualizations: closing price, daily returns, rolling volatility
- Outlier detection (3-std threshold): TSLA 46, BND 33, SPY 39 outlier days
- Top/bottom return days for TSLA
- ADF stationarity test on prices (all non-stationary) and returns
  (all stationary) - confirms ARIMA differencing parameter d=1
- Risk metrics: VaR (95%) and annualized Sharpe Ratio per asset
- Key insights summary written up with actual figures