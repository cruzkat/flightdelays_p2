# Project 2: Predicting Flight Delays

In my second project, I chose to look at flight data. As a frequent traveler, I have a disdain for delayed flights and missing connecting flights. I wanted to take a look at the available transport data and see if I am able to predict flight delays. I also wanted to look at the most delayed flight carriers and origin airports so that I can use this analysis when purchasing future tickets. 

I used data from from the [Bureau of Transportation](https://www.transtats.bts.gov/). They have downloadable CSVs with domestic flight data. I chose to look at flight data for 2017 and 2018.

### 1. Exploratory Data Analysis (flightdelays_EDA)
Initially opening data from 2017 and 2018 for all carriers, I narrowed down the number of carriers and origin airports to just those from San Francisco, San Jose, and Los Angeles. This is due to size of data as well as my personal flying habits.

### 2. Regression Modeling (flightdelays_regression)
Using my categorical features created from the EDA notebook, I ran regression modeling, regularization, and predictions for delays. After seeing poor predictions with regression, I turned to time series modeling. 

### 3. Time Series Modeling (flightdelays_timeseries)
This notebook goes through model tuning for SARIMAX time series.   

### 4. Final Prediction (flightdelys_finalprediction)
This notebook has my final SARIMAX model prediction.