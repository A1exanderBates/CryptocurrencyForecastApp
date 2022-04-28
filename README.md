# DS4PH-BME Capstone Project

[Crypto Forecast App](https://steadygrow99.shinyapps.io/CryptoForecastApp/)

This is a cryptocurrency forecasting app for some of the top performing currencies in 2021. It includes different types of forecasting models to predict the performance of various cryptocurrencies, a supervised learning algorithm to predict closing bitcoin price, and analysis of fluctuations in a cryptocurrency's history to determine whether it has a stationary or non-stationary cycle.

## Forecasting model 1: Prophet Model
A forecasting model that considers daily, monthly, and yearly seasonality. Predicts up to one year in advance.

## Forecasting model 2: Random Walk (Type of ARIMA model)
This model is included in R-studio's "forecast" package. Random walk is predicted as a stochastic model with time dependency based on the previous point in time.

## Prediction Algorithm: Random Forest
The random forest algorithm builds an ensemble of decision trees based upon the fluctuations in Bitcoin's closing price. It allows the user to input high, low, open, close, volume, and marketcap to predict Bitcoin's closing price for the next day.

## Trend Analysis: ACF and PACF
The auto-correlation and partial auto-correlation plots are useful to determine the cyclicality of each of the cryptocurrencies.

## Additional info
I was responsible the idea, finding the data, and for constructing the first version, which had the prophet model and the plotlys. In addition, I helped write the 'about' page.   

The app was created using flexdashboard in R studio. Packages required to construct the app can be found in the rmd file provided.
