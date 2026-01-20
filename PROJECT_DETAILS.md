# Stock Market Predictive Modeling & Forecasting Project

## Project Overview
A machine learning-based forecasting system using **XGBoost** to predict stock market prices with high accuracy and interpretability.

## Key Challenges Addressed
- **Traditional Models Limitations**: ARIMA and Moving Averages fail to handle real-time fluctuations and nonlinear patterns
- **Deep Learning Trade-offs**: LSTM models are resource-heavy, slow to train, and act as "black boxes" (hard to interpret)
- **Solution**: XGBoost with feature engineering for speed, clarity, and multi-feature flexibility

## Core Features
1. **XGBoost Algorithm**: Efficient, interpretable, and scalable
2. **Feature Engineering**:
   - Lag values (past prices)
   - Percentage returns
   - Moving averages (MA5, MA10)
   - Volatility patterns
   - Raw data: Open, High, Low, Close, Volume (via yfinance API)

3. **Performance Metrics**:
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Square Error)
   - R² Score (model fit quality)

4. **System Capabilities**:
   - Plug-and-play architecture (works with any stock symbol)
   - Multivariate data handling
   - Real-time updates without retraining
   - Live data integration
   - Clear feature importance and transparency

## Technical Stack
- **ML Framework**: XGBoost
- **Data Source**: yfinance API
- **Metrics**: MAE, RMSE, R² Score
- **Architecture**: Real-world ready, scalable

## Future Enhancements
- Sentiment analysis from financial news
- Macroeconomic indicators integration
- Alert systems for high-risk movements
- Portfolio optimization
- Multi-stock forecasting

## Team
- Madhu Priyaa S (910622104058)
- Nivetha R S (910622104068)
- Guide: Ms. R. Nivethitha, Assistant Professor 2
- Institution: K.L.N. College of Engineering, Anna University, Chennai
