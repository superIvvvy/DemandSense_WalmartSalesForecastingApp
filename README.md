# DemandSense_WalmartSalesForecastingApp
# TimeSries Forecast

This notebook demonstrates an MVP for DemandSense — a lightweight, interpretable, and accurate demand forecasting tool for Walmart suppliers, category managers, and inventory planners. It uses the **M5 Forecasting (Walmart) dataset** and implements:
- Kaggle API integration (to download data reproducibly)
- Data prep & feature engineering
- EDA and holiday/promo effect exploration
- Baselines (Naive, Seasonal-Naive)
- Classical models (Auto-ARIMA)
- ML model (LightGBM; Prophet optional)
- Rolling-origin backtesting with metrics (MAPE, RMSE)
- Business insights + story for the pitch

> **Use Case:** Predict daily SKU x store demand to reduce stockouts, cut overstocks, and optimize promotions/holidays planning.

> **Kaggle Data:** https://www.kaggle.com/competitions/m5-forecasting-accuracy/overview


## Instructions
1. Run the Setup cell to install libraries and authenticate with Kaggle (you'll upload your `kaggle.json`).  
2. Run Data Download & Load cells — all M5 files will be downloaded and unzipped.  
3. Proceed through EDA, Modeling, and Backtesting.  
4. Customize as needed (e.g., choose SKUs/stores, adjust model parameters).

> Runtime note: The full M5 dataset is large. For fast iteration in class, we sample a manageable subset (e.g., a few stores x a few categories). You can scale up later.
