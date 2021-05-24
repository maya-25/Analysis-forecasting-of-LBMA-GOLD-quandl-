# Analysis-forecasting-of-LBMA-GOLD-quandl (London Bullion Market Association/GOLD)

* Using various libraries
* Quandl, tsibble, ggplot2, quantmod, tseries, PerformanceAnalytics, dplyr, tibbletime, urca, forecast, fable, feasts (feature extraction and statistics)
* forescasting the log_return of LBMA/GOLD using ARIMA(3,0,4) model and naive forecast for the later 1 year.
* Used dickey fuller test to check whether the time series is having trend or is stationary.
* converting weekly time series into monthly using mutate function of dplyr and yearmonth()
* plotted the Auto correlationa and partial aoutocorrelation and analyzed the autoregressive and moving average terms in time series
* check the residuals by Ljung-box test 
