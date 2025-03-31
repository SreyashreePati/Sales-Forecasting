# # Sales Forecasting Project

## Overview
This project aims to forecast sales using multiple models, including statistical, machine learning, and deep learning techniques. The dataset includes historical sales data along with external factors such as holidays, oil prices, and promotions.

## Models Implemented
- **Naïve Forecasting** (Baseline model)
- **ARIMA** (Time series forecasting model)
- **Random Forest Regressor** (Tree-based ensemble model)
- **XGBoost** (Gradient boosting for accuracy improvement)
- **LSTM** (Deep learning-based time series model)
- **Prophet** (Seasonality-aware forecasting model)

## Dataset Details
- `train.csv`: Historical sales data
- `test.csv`: Data for prediction
- `stores.csv`: Store details
- `oil.csv`: Oil price variations
- `holidays_events.csv`: Holiday and promotional events

## Installation
To run this project, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels xgboost prophet tensorflow
```

## Running the Notebook
1. Open `Wise_Analytics.ipynb` in Jupyter Notebook.
2. Run the data preprocessing steps.
3. Train the models and evaluate performance.
4. Compare the predictions and analyze business insights.

## Model Evaluation Metrics
Each model is evaluated based on:
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Percentage Error (MAPE)**
- **R-Squared Score (R²)**



### Business Insights
- **External factors**: Holidays and promotions significantly impact sales.
- **Inventory Planning**: Improved forecasting helps optimize stock levels.
- **Marketing Strategy**: Targeted promotions based on seasonal trends.
- **Oil Prices**: Fluctuations in oil prices may indirectly affect transportation and logistics costs, impacting sales distribution.



