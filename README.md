# Store Sales - Time Series Forecasting (Kaggle)

An end-to-end retail sales forecasting baseline built using XGBoost to predict store sales across various product families in Ecuador.

## 📊 Baseline Benchmark & Scores
* **Validation Strategy:** Chronological split (final 60 days of training data)
* **Local Validation RMSE:** 308.9290
* **Kaggle Public Leaderboard RMSLE:** 0.96364

## 🛠️ Data & Features Included
* **Store Metadata:** Store type, cluster
* **Economic Data:** Daily oil prices (interpolated)
* **Calendar:** National and regional holiday flags
* **Promotions:** Daily item `onpromotion` counts

## 🚀 Next Steps / Future Enhancements
- [ ] Feature engineering for time lags (7-day, 14-day historical sales)
- [ ] Calendar features (day of week, payday flags on 15th and month-end)
- [ ] Hyperparameter tuning and LightGBM model comparison
