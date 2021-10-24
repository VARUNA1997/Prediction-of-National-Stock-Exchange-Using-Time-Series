# Prediction-of-National-Stock-Exchange-Using-Time-Series

### Objectives of the project
1.Data Preparation

2.Data Visualization

3.Building a time series model

### Dataset Details
## Description of columns in the file:
Date — Date of trade

Open — The open is the starting period of trading on a securities exchange or organized over-the-counter market.

High — Highest price at which a stock traded during the course of the trading day.

Low — Lowest price at which a stock traded during the course of the trading day.

Close — The close is a reference to the end of a trading session in the financial markets when the markets close for the day.

Volume — It is the amount of a security that was traded during a given period of time

Turnover -It is a measure of sellers versus buyers of a particular stock. It is calculated by dividing the daily volume of a stock by the “float” of a stock, which is the number of shares available for sale by the general trading public.

## Distribution of stock measures
Let’s witness the histogram distribution of the stock measures such as open,close,high,low.
![image](https://user-images.githubusercontent.com/89696170/138592926-db42f7dc-f9ec-4846-afcf-ff8fa38718e7.png)

## Insights:
There are many outliers in our dataset as we can see the max at the 75th percentile
The standard deviation and other statistical measurements is more or less equal among all the features
![image](https://user-images.githubusercontent.com/89696170/138593012-f25db17e-3347-4d62-a27d-fafaa2b17097.png)

## Decompose with multiplicative model
![image](https://user-images.githubusercontent.com/89696170/138593070-b8bdab14-1d2d-41ed-bb9f-a32675e75ac5.png)

## Moving average analysis
Moving average is a smoothing technique applied to time series to remove the fine-grained variation between time steps.The hope of smoothing is to remove noise and better expose the signal of the underlying causal processes. Moving averages are a simple and common type of smoothing used in time series analysis and time series forecasting
![image](https://user-images.githubusercontent.com/89696170/138593144-8f8666fd-5dcd-4e8c-a84c-d5a7abaef4b4.png)

## Plotting Histogram for residuals
![image](https://user-images.githubusercontent.com/89696170/138593173-c20ba207-1e4c-4d21-be03-2c1def898b47.png)


## Plot comparision Actual, Model Values & Residuals
![image](https://user-images.githubusercontent.com/89696170/138593190-682d8628-667e-4b9e-9a07-b46dbfa3a443.png)

## AUTO ARIMA:- 
Although ARIMA is a very powerful model for forecasting time series data, the data preparation and parameter tuning processes end up being really time consuming. Before implementing ARIMA, you need to make the series stationary, and determine the values of p and q using the plots we discussed above. Auto ARIMA makes this task really simple for us as it eliminates steps like converting stationarity and getting values of p,q from acf and pacf plots.

## Plotting the forecasted values with the actual data
Let’s plot the results and compare them with actual values
![image](https://user-images.githubusercontent.com/89696170/138593274-c2ffbaed-9ce2-4f9b-998d-c667144e232c.png)

## Prediction of future values
We have predicted the values for all the dates and even the 2021 dates.  Let’s look at the plot to get a better understanding.
![image](https://user-images.githubusercontent.com/89696170/138593327-dbf8b510-c221-4820-a70f-08d5dc970d5b.png)

