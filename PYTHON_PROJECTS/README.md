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
