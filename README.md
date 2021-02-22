# Analysis_&_Prediction_of_covid-19_using_Python

Coronavirus disease 2019 (COVID-19) time series listing confirmed cases, reported deaths and reported recoveries. Data is disaggregated by country (and sometimes subregion). Coronavirus disease (COVID-19) is caused by the [Severe acute respiratory syndrome Coronavirus 2 (SARS-CoV-2)][sars2] and has had a worldwide effect. On March 11 2020, the World Health Organization (WHO) declared it a pandemic, pointing to the over 118,000 cases of the Coronavirus illness in over 110 countries and territories around the world at the time.

[covid]: https://en.wikipedia.org/wiki/Coronavirus_disease_2019
[sars2]: https://en.wikipedia.org/wiki/Severe_acute_respiratory_syndrome_coronavirus_2

This dataset includes time series data tracking the number of people affected by COVID-19 worldwide, including:

- confirmed tested cases of Coronavirus infection
- the number of people who have reportedly died while sick with Coronavirus
- the number of people who have reportedly recovered from it

## Data

Data is in CSV format and updated daily. It is sourced from [this upstream repository](https://github.com/CSSEGISandData/COVID-19) maintained by the amazing team at [Johns Hopkins University Center for Systems Science and Engineering](https://systems.jhu.edu/) (CSSE) who have been doing a great public service from an early point by collating data from around the world.

## Prediction using fbprophet

Prophet is an open source time series forecasting algorithm designed by Facebook for ease of use without any expert knowledge in statistics or time series forecasting.Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.
