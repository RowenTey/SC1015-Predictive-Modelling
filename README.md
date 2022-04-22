# Stock Prediction Analysis

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence). We focused on making predictions on black's first move, based on a chess game dataset containing over 20,000 chess games from LiChess, and can be found [here](https://www.kaggle.com/datasnaek/chess).

## Problem Statement
Given the following constraints:
- White's first move
- White and Black's chess ratings
- Rating difference
- Number of turns taken

What are the next five most probable moves for black?

## Notebook Order
The flow of our project is as follows:
1. Initial exploratory data analysis (EDA), found under [Pre Model Analysis.ipynb](https://github.com/Junius00/chess-predictions/blob/master/Pre%20Model%20Analysis.ipynb)
2. Data preparation and modelling, found under [MLR Model.ipynb](https://github.com/Junius00/chess-predictions/blob/master/MLR%20Model.ipynb)
3. Post model analysis and graphing, found under [Post Model.ipynb](https://github.com/Junius00/chess-predictions/blob/master/Post%20Model.ipynb)

## Models Used

1. Multinomial Logistic Regression

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
