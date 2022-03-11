# datasci_salaries-R

## About

A simple Dash-R app deployed on Heroku which shows the distribution of data science salaries for different countries. The dashboard can be found [here](https://datasci-r-wenjia-ia2.herokuapp.com/).

## Data

Data for this project was obtained from [Kaggle Data Scientists Salaries Around the World](https://www.kaggle.com/ikleiman/data-scientists-salaries-around-the-world/data). Specifically, the files `conversionRates.csv` and `multipleChoiceResponses.csv` are used in this project.

The data is processed using `src/data_cleaning.R` to mainly remove observations that do not have salary data, and to convert all salaries to USD.

## Description of app

The app has a single landing page which shows one plot. By default, the plot shows the median salary salaries and a heatmap of the salary in data science industry. One widget are provided to specify the country to view data science salaries for.


Default page            |  Canada`
:-------------------------:|:-------------------------:
<img src="https://github.com/PANDASANG1231/datasci_individual_r/blob/master/media/dashboard.png" width=400> |  <img src="https://github.com/PANDASANG1231/datasci_individual_r/blob/master/media/dashboard_canada.png" width=400>
