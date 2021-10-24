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
