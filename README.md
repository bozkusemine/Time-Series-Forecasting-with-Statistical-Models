# Time Series Forecasting with Statistical Models
Time series forecasting refers to the process of predicting future values of a time-dependent variable based on past observations. It is widely used in various industries, such as finance, economics, and weather forecasting, to make informed decisions and improve overall planning and strategy.

![image](https://user-images.githubusercontent.com/58263509/216998134-93943157-ae69-41be-9520-2124bbd51f41.png)

Statistical models are one of the most common approaches used in time series forecasting. These models are mathematical representations of the underlying relationships between the variables in a time series and are used to make predictions about future values. There are several types of statistical models that can be used for time series forecasting, including:

## Autoregressive (AR) Model: 
The autoregressive model is another common method for time series forecasting. It is based on the assumption that the future value of a time series is a linear combination of past values and a white noise error term. The number of past values used in the calculation is referred to as the "order" of the model. The larger the order, the more information is used in the prediction, but the more complicated the model becomes.

## Moving Average (MA) Model: 
The moving average model is a simple and straightforward method for forecasting time series data. It involves calculating the average of a set of past observations and using that average as the prediction for future values. The number of past observations used in the calculation is referred to as the "window size". The larger the window size, the smoother the forecast, but the less responsive it will be to changes in the underlying trends.

## ARMA (Auto-Regressive Moving Average): 
The ARMA is one of the most commonly used methods to model univariate time series. ARMA(p,q) combines two components: AR(p), and MA(q).

## Autoregressive Integrated Moving Average (ARIMA) Model: 
The autoregressive integrated moving average (ARIMA) model combines the moving average and autoregressive models to produce a more sophisticated time series forecasting method. It can handle both linear and non-linear relationships between the variables in a time series, making it a powerful tool for time series analysis. The order of the autoregression and moving average components of the model, as well as the order of integration, are parameters that must be specified in order to fit the model to the data.

## Seasonal Autoregressive Integrated Moving Average (SARIMA) Model: 
The seasonal autoregressive integrated moving average (SARIMA) model is an extension of the ARIMA model that takes into account seasonality in the data. Seasonality refers to patterns in the data that repeat at regular intervals, such as daily, weekly, or yearly patterns. The SARIMA model adds an additional set of parameters that capture the seasonal patterns in the data, allowing for more accurate forecasting of time series with strong seasonality
