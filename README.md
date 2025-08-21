## Project Overview

This project uses Multiple Linear Regression to predict a continuous target variable (house prices) based on multiple independent features. The main objective was to understand how regression can be extended from a single predictor to multiple predictors and analyze model assumptions.

## Dataset

Dataset with numerical predictors such as house size, number of rooms, and year of construction.

Target variable: House Price.


## Methodology

1. Explored the dataset with summary statistics and correlation checks.


2. Applied preprocessing (removing outliers, handling missing values).


3. Built a Multiple Linear Regression model using scikit-learn.


4. Evaluated model performance using:

R² Score

Adjusted R²

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)



5. Checked assumptions of regression (multicollinearity, residual plots, normality of errors).



## Results

The regression model was able to explain a significant portion of variance in house prices.

Adjusted R² showed how adding features impacted predictive power.

Detected multicollinearity in some features, which reduced interpretability.


## What I Learned

The difference between R² and Adjusted R².

How to evaluate residuals for checking regression assumptions.

How multiple predictors interact in influencing the target.


Future Work

Apply Ridge, Lasso, and ElasticNet regression to reduce multicollinearity.

Use feature engineering to improve prediction accuracy.

