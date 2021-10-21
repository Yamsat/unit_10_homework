# A Yen for the future
Prediction of USD/JPY exchange rate futures price

## Tools for prediction
・Time series analysis - **ARMA**, **ARIMA**, **GARCH**,<br />
・Machine learning - **Linear regression**

## Time Series Analysis
ARMA model forecasts the price will decline over next five days while ARIMA model forecasts the opposite.
However, as the p-value for both models are not significant, these models do not seem to be very reliable.
GARCH indicates that the volatility will increase for next five days. The p-value is significant except for the second AR lag.
This infers that prediction of near term future volatility may be reliable.
Withe predicted increase volatitiy and opposite outcomes for ARMA and ARIMA, I would not buy the Yen.

## Linear regression
The model works better on out-of-sample data compared to in-sample data.
Yet, whether the date is out-of-sample or in-sample, the root mean squred error for the model is significant. Thus the model does not work well with the data.
This suggests that the return for USD/JPY exchange rate futures is not autoreggresive. 
