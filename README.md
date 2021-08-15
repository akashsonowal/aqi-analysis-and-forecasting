# Air Quality Index Analysis and Forecasting

## Objective: 

To analyse the impact of COVID'19 in Air Quality Index of major cities in India and also forecast India's Average AQI for 2021. 

## Approach:

- Calculated the correlation of different pollutants with AQI, studied AQI trend during Covid-19 lockdown of major polluted cities.
- Checked for stationarity, trend and seasonality of India's Average AQI using ADF-test (Augmented Dickey-Fuller) & Decompose Plot.
- Used autoarima to find the parameters of SARIMA model. 

## Result:
- Achieved RMSE of 12.5 in the test data and forecasted AQI for the year 2021.

## [Data](https://www.kaggle.com/rohanrao/air-quality-data-in-india) description:

    - city: cities of India
    - date: date of readings
    - PM 2.5: Particulate Matter 2.5-micrometer in ug/m<sup>3</sup>
    - PM 10: Particulate Matter 10-micrometer in ug/m<sup>3</sup>
    - NO: Nitric Oxide in ug/m<sup>3</sup>
    - NO<sub>2</sub>: Nitric Dioxide in ug/m<sup>3</sup>
    - NO<sub>x</sub>: Any Nitric x-oxide in ppb
    - NH<sub>3</sub>: Ammonia in ug/m<sup>3</sup>
    - CO: Carbon Monoxide in mg/m<sup>3</sup>
    - SO<sub>2</sub>: Sulphur Dioxide in ug/m<sup>3</sup>
