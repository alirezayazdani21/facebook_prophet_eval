# facebook_prophet_eval
In this brief analysis we run two simple experiments to evaluate predictive power of the FB's Prophet Time Series Forecasting model.

We use Prophet's R interface and compare that against standard models from R forecast package including:
  1) ARIMA model for quarterly unemployment prediction,
  2) TBATS model for Half-hourly electricity demand forecasting.
  
We experiment with both "linear" as well as "logistics" settings of Prophet model but in all cases Prophet seems to underperform other models across a number of time series model evaluation metrics.
