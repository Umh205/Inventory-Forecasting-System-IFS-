### Inventory Forecasting using Machine Learning Project

Inventory forecasting involves predicting future customer demand within a specific timeframe. By analyzing historical data and understanding demand drivers, organizations can make informed decisions to optimize production, manage supply needs effectively, and minimize waste.

Traditional Approaches:
Organizations often rely on well-established forecasting techniques, including but not limited to:

- Auto ARIMA (Auto-Regressive Integrated Moving Average): Automatically determines the best parameters for ARIMA models.
- SARIMA (Seasonal ARIMA): Extends ARIMA to account for seasonality in data.
- Simple Moving Average: Calculates average demand over a fixed time window to smooth fluctuations and forecast future demand.
- Exponential Smoothing: Assigns exponentially decreasing weights to past observations for trend prediction.
- Holt-Winters Method: Captures level, trend, and seasonality in the data for more precise forecasting.
These algorithms provide foundational insights but may need enhancements or integration with modern techniques for real-world complexities.

Application Scope:
The goal is to align inventory levels with actual customer needs, improve cost efficiency, and reduce overproduction. Inventory forecasting is crucial in sectors such as manufacturing, retail, and food production.

## Table of Contents
```bash
Goal
Workflow
Required Packages
Goal
````
Due to the recent boost in AI world, companies have started researching the possibility of using machine learning/Neural Networks in place of tranditional approach.

Tuning traditional algorithms takes a significant amount of efforts and domain expertise as well.

In this repo, we are trying to figure out a way of predict the same using machine learning algorithms.

## Data
The dataset comprised of units sold on a daily basis along with details regarding the sales, eg. SKU(product id), Store, price etc.

record_ID, week, store_id, sku_id, total_price, base_price, is_featured_sku, is_display_sku, units_sold

## Workflow
```bash
Handling missing values
Feature selection
Converting dataset into time series format to apply supervised learning approach.
Regression Modeling
Random Forest
XGBoost
SVM (future scope)
Hyperparameter Tuning
Result
```

### Required Packages
```bash
numpy
pandas
sklearn
easypreprocessing
seaborn
matplotlib
xgboost
```
