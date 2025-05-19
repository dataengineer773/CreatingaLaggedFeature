We want to create a feature that is lagged n time periods, Use pandas’ shift, Very often data is based on regularly spaced time periods (e.g., every day, every hour, every three hours)
and we are interested in using values in the past to make predictions (this is often called lagging a
feature). For example, we might want to predict a stock’s price using the price it was the day before.
With pandas we can use shift to lag values by one row, creating a new feature containing past values.
In our solution, the first row for previous_days_stock_price is a missing value because there is no
previous stock_price value.
