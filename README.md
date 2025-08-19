AI-Based Lumber Futures Trading Bot

A Python-based trading system that predicts lumber commodity price movements and executes simulated trades using machine learning–driven signals. The model leverages an LSTM neural network trained on diverse market features, including U.S. housing starts, mills’ operating margins, futures curve structure, and seasonal curve patterns. These inputs are combined into a predictive framework that generates trade signals, backtests performance, and reports key metrics such as Sharpe ratio, CAGR, and drawdowns.

Features:
- Automated data collection from (FRED, Quandl, Yahoo Finance, and Nasdaq)
- Feature engineering for commodity market signals (moving averages, volatility, sentiment data if applicable)
- Predictive modeling (e.g., LSTM, random forest, logistic regression)
- Backtesting engine with Sharpe ratio, drawdown, and PnL reporting
- Position sizing & risk management logic
- Visualization of buy/sell signals

Model & Methodology
- Algorithm Type: LSTM neural network for time series forecasting
- Training Window: 5 years of historical data
- Evaluation Metrics: Sharpe ratio, accuracy, win rate, Compounded Annual Growth Rate

Example Output
<img width="912" height="542" alt="Screenshot 2025-08-15 at 5 49 00 PM" src="https://github.com/user-attachments/assets/e4e5e8e6-9a8b-48cc-b394-154203b2325e" />
