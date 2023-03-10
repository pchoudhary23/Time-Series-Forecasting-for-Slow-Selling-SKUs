# Time-Series-Forecasting-for-Slow-Selling-SKUs

This project was result of MSA Project Week competition completed along with 3 other batchmates: Manoj Parmar, Sunil Ravilla, and Yash Bhole.

The problem statement was to forecast daily sales of slow selling SKUs for a retailer. The slow selling SKUs do not have sales for each day and thus traditional time series techniques usually do not work well. Train data available was of 5 years and had ~850K records for 575 SKUs.

After inital exploration and feature engineering, multiple techniques such as Croston, LGBM, XGB, ARIMA and Moving Average were evaluated.

The champion model utilized a novel methodology where we predicted daily sales by predicting weekly sales and also forecasting sales proportion for the day of the week for any SKU. The resultant daily sales would be a product of predicted weekly sales and day of the week forecasted proportion.
