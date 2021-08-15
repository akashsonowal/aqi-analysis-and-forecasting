# Air Quality Index Analysis and Forecasting

## Objective: 

To analyse the impact of COVID'19 in Air Quality Index of major cities in India and also forecast India's Average AQI for 2021. 

## Approach:

- Checked for stationarity, trend and seasonality using ADF-test (Augmented Dickey-Fuller), KPSS-test & Decompose Plot. 
- Models Applied AR, MA, ARMA, ARIMA. For ARIMA (p,d,q) parameters p and q, PACF-test (Partial Autocorrelation function) and ACF-test (Autocorrelation function) used. 
- Time series made stationary by Differencing (d). 
- RMSE and MAPE used for evaluation metric. 

- Visualise the Time series
- Decomposing into trend, seasonal, cyclical and noise components
- Analyze the seasonality of a Time Series: additive and multiplicative.
- Check stationarity of data - Rolling Mean, ADCF Test(Augmented Dickey–Fuller test)
- Statinarize Time series - first differencing
- Plot ACF/PACF charts and find optimal parameters
- Build Time series models according to data - AR, MA, ARIMA, SARIMA
- Plot Residual distribution
- Make predictions
- MAPE,SMAPE as evaluation metric

## Result:


## Data description:

    - date: The date of sale
    - store: This is the store number
    - item: This is the item number
    - sales: Sales made on that particular day

## References:

- https://towardsdatascience.com/what-is-time-series-decomposition-and-how-does-it-work-9b67e007ae90
- https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/
- http://www.seanabu.com/2016/03/22/time-series-seasonal-ARIMA-model-in-python/
