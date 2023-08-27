### Prediction Model of Time Series for Knowing the Number of Taxi Company Orders

A taxi company called `Sweet Lift` has collected historical data (`time series`) about taxi orders at the airport. To attract more drivers during busy hour, it is necessary to predict the number of taxi orders for the next `one hour`. The company only has historical data from `March` to `August` of 2018. We will create some `machine learning` models to predict the number of orders along with testing those models, where the `RMSE metric` in *test set* `does not may be more than 48`. Here are some steps to solve the problem on this project:
1. Perform *resampling* data in one hour.
2. Analyzing dataset to obtain `insights` in the form of `time series` features such as `trend`, `seasonality` and `residue` analysis.
3. Train a `different` `model` with `different` hyperparameters. Here we will determine that the `test` sample is `10%` of the dataset.
4. Testing the `RMSE metric` on `all models` using `test` data.
5. Make prediction for `september` in 2018 using the `best model`.

| Project | Description | Library |
| ------- | ------- | ------- |
| [Prediction Model of Time Series in Taxi Company]() | Comparison of `machine learning` models for predicting `order amount` of taxi company using `time series dataset` to get `RMSE` scores that are `not greater than 48` | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *XGBoost*, *time*, *LightGBM*, *statsmodels* |