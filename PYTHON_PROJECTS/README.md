# PYTHON PROJECTS

# Project 1 : Finding temperature anomalies in istanbul in 2019 by using Python:
## Project Summary
This project analyzes approximately 13 years of daily weather data to detect heat anomalies days in the year 2019.
By calculating the long-term average and standard deviation of daily temperatures for each calendar day, the project identifies which dates in 2019 had unusuall temperatures compared to historical patterns.
## Technologies used
* python 3x
* matplotlib ( for data visualization)
* pandas ( for data manipulation)
* numpy ( for statistics )
## About data
* dataset includes daily maximum and minimum temperatures in istanbul for 10 years and dates
* data is taken from kaggle = https://www.kaggle.com/datasets/vonline9/weather-istanbul-data-20092019/data
## Project workflow
1. Load the dataset
2. explore data by head and tail methods make observations
3.  Determine null values in dataset
4.  Change format of Datetime column for time series analysis
5.  Create two dataframes that includes mean and standard deviation values for maximum and minimum values.
6.  add these columns into original dataframe
7.  Calculate z score for each day
8.  identify days with z score higher than 2 and put them into two dataframes
9.  visualize results

# Project 2 : Multi-Stock Price Analysis Project
## Project Summary
In this project, 5 years of closing price data (2020–2025) for Tesla and Apple are analyzed to calculate cumulative returns, volatility, and return-to-risk ratios. The results are visualized to support clear comparisons between the stocks.
## About data
* dataset includes closing prices of apple and tesla stocks for 5 years . Data is taken from yfinance through their python API.
* original dataset does not require any cleaning
## Project worklow
1. import libraires
2. load data using yfinace API of python
3. superficial observaitons to understand data
4. visualize stock prices
5. calculate daily and cumulative returns of stocks visualize results
6. calculate volatlilty for 30 day windows visualize result
7. calculate cumulative returns for 30 day windows to align with volatility better
8. calculate return to risk ratio using cumulative return and volatility
9. visualize return to risk ratio for 2024

