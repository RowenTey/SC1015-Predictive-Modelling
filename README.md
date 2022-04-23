# Stock Prediction Analysis - SC14 Group 1

## About

This is a Mini-Project for Nanyang Technological University Singapore's SC1015 module (Introduction to Data Science and Artificial Intelligence). We chose to explore several popular machine learning models to test their reliability in predicting stock prices. 

## Problem Statement
Given the following constraints:
- White's first move
- White and Black's chess ratings
- Rating difference
- Number of turns taken

What are the next five most probable moves for black?

## The Team 
| Name              |                     Area of Focus                     |GitHub Acount|
|---|:---:|---|
| Tey Kai Seong |        Data Preparation, EDA, Presentation Slides, GitHub Repository        |@RowenTey|
| Horstann Ho Rui Yao  |     Machine Learning, EDA, Problem Definition, Statistical Inference     |@Horstann|
| Julian Wong Wei Sheng |       Data Preparation, EDA, Video Presentation,  Analytic Visualisation        |@DarkDestiny26|

## Where to Start
The flow of our project is as follows:
1. Data Sampling, Preparation, Exploratory Data Analysis and Analyitic Visualisation, found in [Pre-Model.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/Pre-Model.ipynb)
2. Data Modelling for Multiple Polynomial Regression, found in [Polynomial Regression.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/Polynomial%20Regression.ipynb)
3. Data Modelling for Long Short Term Memory (LSTM), found in [LSTM.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/LSTM.ipynb)
4. Post Model Analysis, Statistical Inference and Intelligent Decision, found in [Post-Model.ipynb](https://github.com/RowenTey/sc1015-project/blob/main/Post-Model.ipynb)
5. Results of our project, found in [results/](https://github.com/RowenTey/sc1015-project/tree/main/results)

## Models Used

1. Long short-term memory (LSTM)
2. Multiple polynomial regression 

## Conclusion

- The model attains a final evaluative score of 22.5/100 on average.
- Although the model may not be able to accurately predict the next black move, it is able gives a possible idea of the move.
- Chess games that are played by humans are still largely unpredictable.
- Perhaps the model should not be used to attempt to accurately predict black’s first move; rather, to see what other players would do in the same situation.

## What did we learn from this project?

- Transformation of DataFrames in Pandas (e.g., conversion of categorical to numeric values)
- Using MLR modelling
- 3D graphing techniques
- How to use GitHub

## References

- SP500 Data - https://stooq.com/q/d/?s=%5Espx&c=0&i=m   
- LSTM Model - https://thinkingneuron.com/predicting-stock-prices-using-deep-learning-lstm-model-in-python/   
- FRED API - https://fred.stlouisfed.org/docs/api/fred/   
- De-Trending - https://www.svds.com/avoiding-common-mistakes-with-time-series/   
- Hypothesis Testing - https://www.statisticshowto.com/welchs-test-for-unequal-variances/ & https://www.statology.org/welch-t-test-python/
