# Stock Price Prediction using Economic Indicators - SC14 Group 1

## About

This is a Mini-Project for Nanyang Technological University Singapore's SC1015 module (Introduction to Data Science and Artificial Intelligence). We chose to explore different machine learning models to test their reliability in predicting stock prices. 
<br>
<br>
We would also like to thank our teaching assistant Song Nan for her constant guidance and encouragement throughout the project. This project would not have been possible without her valuable feedback and expertise in the field of Data Science.

## Problem Statement
Current state of the art:
- extremely complex predictive models (e.g. LSTM) are popularly used to predict stock prices
- many financial firms and organisations rely on these models for risk management and profit maximisation

Are these models really reliable? Do they have any weaknesses?
Can we produce more reliable predictions using alternative models?

## The Team 
| Name              |                     Area of Focus                     |GitHub Acount|
|---|:---:|---|
| Tey Kai Seong |        Data Preparation, EDA, Presentation Slides, GitHub Repository        |@RowenTey|
| Horstann Ho Rui Yao  |     Machine Learning, Problem Definition, Data Visualisation, Statistical Inference     |@Horstann|
| Julian Wong Wei Sheng |       Data Preparation, EDA, Video Presentation, Analytic Visualisation        |@DarkDestiny26|

## How to Start
The flow of our project is as follows:
1. Data Sampling, Preparation, Exploratory Data Analysis and Analytic Visualisation, found in [Pre-Model.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/Pre-Model.ipynb)
2. Data Modelling for Multiple Polynomial Regression, found in [Polynomial Regression.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/Polynomial%20Regression.ipynb)
3. Data Modelling for Long Short-Term Memory (LSTM), found in [LSTM.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/LSTM.ipynb)
4. Post Model Analysis, Statistical Inference and Intelligent Decision, found in [Post-Model.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/Post-Model.ipynb)
5. Results of our project, found in [results/](https://github.com/RowenTey/sc1015-project/tree/main/results)

## Models Used

1. Long short-term memory (LSTM)
2. Multiple polynomial regression 

## Conclusion

- Our regression model's mean-square-error was 64.6% less than the LSTM's on average.
- Based on our MSE samples, our regression model ourperformed LSTM at a staggering 99% confidence level.
- From these results, we see that economic indicators are a better indicator of stock price than past trends.
- We recommend developing a model that takes both current economic indicators and past trends as predictors for even better results.

## What did we learn from this project?

- Completely unrelated time series data can have very strong correlations if they have similar trends, so it's important to detrend
- Using plotly as a tool for interactive visualisations
- Handling LSTM & multiple polynomial regression models
- The relationships between economic indicators and stock price, alongside their volatility
- How to use GitHub
- Use simpler models whenever possible. They consume less time and resources, so we are able to run more tests on the model e.g. in our case, we could run 1000 regressions in less than 15sec, but 20 LSTMs already took 20-30min. Being able to run more tests allows us to better assess and refine the model e.g. our good old regression ended up outperforming LSTM by a large margin.

## References

- SP500 Data - https://stooq.com/q/d/?s=%5Espx&c=0&i=m   
- LSTM Model - https://thinkingneuron.com/predicting-stock-prices-using-deep-learning-lstm-model-in-python/   
- FRED API - https://fred.stlouisfed.org/docs/api/fred/   
- De-Trending - https://www.svds.com/avoiding-common-mistakes-with-time-series/   
- Hypothesis Testing - https://www.statisticshowto.com/welchs-test-for-unequal-variances/ & https://www.statology.org/welch-t-test-python/
