# Project 1. Comments classifications

## Scenario
Online shop decided to launch a new service: users can edit and add product descriptions.
Toxic comments should be found and flagged for moderations. The shop decided that they need to automate this process. 

## Objective  
To facilitate the moderation of comments by automating the assessment of toxicity. This is done by training a model to classify comments into positive and negative.

## Tools
Python, Pandas, Numpy, NLTK, regex, Sklearn, lgbm, logistic regression.

## Result
Thr original dataset contains information if the comment is toxic or not (supervised learning). Dataset was analysed and feature engineering techniques were applied to texts - regex, tokenization, lemmatization of words and vectorization.

Two models were trained - logistic regression and lightgbm regressor. The quality metric F1 = 0.75 was reached with lightgbm regressor after hyperparameter tuning.