# Wine_Quality_Prediction

## Objective:
Build a regressional model that will predict the rating of wine, which are collected from wineenthusiast.com

## Approach:
The features used in the model were price, vintage, bottle size (ml), alcohol percentage, appellation(country), and type of wine. Also, price of the wine applied with log was included in the model, along with interactions of appellation and country made from feature engineering. The model to predict the ratings were, linear regression and LASSO regression models, which were trained using training data set and evaluated using test data set. Features as is and scaled versions were used in models and used R2 to evaluate the performance of the model.

## Tools & Techniques:
- Beauifulsoup and requests for web scraping
- Scikit-learn for feature engineering and extraction
- Linear Regression
- Supervised Learning
- LASSO

## Data
Data were randomly collected from [wineenthusiast.com](https://www.wineenthusiast.com).

## Result
Ordinary Linear regressional model with standard scaled features was selected. Features were selected using LASSO regressional model with features that did not have 0.0 coefficients. The model had R2 of 0.42 on test set.
