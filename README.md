# A Yen for the future
## Prediction of USD/JPY exchange rate futures price

## Tools for prediction
・Time series analysis - ARMA, ARIMA, GARCH
・Machine learning - Linear regression

## Time Series Analysis
ARMA model forecasts the price will decline over next five days while ARIMA model forecasts the opposite.
However, as the p-value for both models are not significant, these models do not seem to be very reliable.
GARCH indicates that the volatility will increase for next five days. The p-value is significant except for the second AR lag.
This infers that prediction of near term future volatility may be reliable.

## Linear regression
The root mean squred error for the model is significant. Thus the model does not work well with the data.
This suggests that the return for USD/JPY exchange rate futures is not autoreggresive. 
