# 📈 Stock Price Prediction using Machine Learning
This project builds a machine learning pipeline to predict short-term stock price movements in the Nifty 500 universe using historical price data and technical indicators.

🔧 Features:
- Data Collection: Fetched OHLCV data for Nifty 500 stocks using the yfinance API.

- Data Preprocessing: Cleaned and aligned data for consistency and removed missing/outlier values.

- Feature Engineering: Calculated a range of technical indicators (momentum, trend, volatility, volume-based) as predictive features.

- Feature Selection: Applied Recursive Feature Elimination with Cross-Validation (RFECV) to identify the most relevant indicators.

# Modeling:

- LSTM Regressor to predict 5-day forward percentage price change.

- LSTM Classifier to predict the probability of a ≥4% price increase over the next 5 days.

# 📊 Output:
- Predicted 5-day returns as continuous values (regression).

- Binary classification signal for significant upside moves.

# 💡 Goal:
To assist in short-term equity decision-making using a blend of deep learning and feature-driven insights.
