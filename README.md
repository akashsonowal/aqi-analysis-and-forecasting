# Air Quality Index Analysis and Forecasting

## Objective: 

To analyse the impact of COVID'19 in Air Quality Index of major cities in India and also forecast India's Average AQI for 2021. 

## Approach:

- Calculated the correlation of different pollutants with AQI, studied AQI trend during Covid-19 lockdown of major polluted cities.
- Checked for stationarity, trend and seasonality of India's Average AQI using ADF-test (Augmented Dickey-Fuller) with 95% confidence & Decompose Plot.
- Used ACF, PACF plots to determine the parameters of final SARIMA(p=0,d=1,q=2)x(P=1,D=0,Q=1,s=12) model. 

## Result:
- Achieved RMSE of 12.5 in the test data and forecasted AQI for the year 2021.

## [Data](https://www.kaggle.com/rohanrao/air-quality-data-in-india) description:

    - city: cities of India
    - date: date of readings
    - PM 2.5: Particulate Matter 2.5-micrometer in ug/m3
    - PM 10: Particulate Matter 10-micrometer in ug/m3
    - NO: Nitric Oxide in ug/m3
    - NO2: Nitric Dioxide in ug/m3
    - NOx: Any Nitric x-oxide in ppb
    - NH3: Ammonia in ug/m3
    - CO: Carbon Monoxide in mg/m3
    - SO2: Sulphur Dioxide in ug/m3
