# lake-erie-time-series
Time Series Analysis of Lake Erie Water Levels from 1921-1970

Programming language: R

Time Series analysis is performed using SARIMA (seasonal autoregressive integrated moving average) and Holt-Winters forecasting modelling.
It is always good practice to build different models because quality of results vary depending on the data and goal.
Sometimes, one modelling type doesn't work while others do and vice-versa.

The SARIMA jupyter notebook contains the following:

- Time series plots
- Differencing (seasonal or non-seasonal)
- Autocorrelation Function (ACF) -> Moving Average Order MA(q)
- Autocorrelation Function (ACF) -> Seasonal Moving Average Order SMA(Q)
- Partial Autocorrelation Function (PACF) -> Autoregressive Order AR(q)
- Partial Autocorrelation Function (PACF) -> Seasonal Autoregressive Order SAR(Q)
- Fitting models
- Akaike Information Criteria (AIC)
- Sum Squared Error (SSE)
- The parsimony priniple: preferebly p+d+q+P+D+Q<=6
- Residuals
- Ljung-Box test
- Forecasting


The Holt-Winters jupyter notebook contains the following:
- Time series plot
- Determing Trend and Seasonality
- Holt-Winters forecasting
- Smoothing Breakdown
- Forecasting for April 1972
