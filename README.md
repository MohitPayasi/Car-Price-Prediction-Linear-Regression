# Car-Price-Prediction-Linear-Regression
![Uploading image.png…]()

## Problem Statement

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

    - Which variables are significant in predicting the price of a car
    
    - How well those variables describe the price of a car
    
## Business Goal

You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Feature Elimination using RFE (Recursive Feature Elimination)

Recursive feature elimination (RFE) is a feature selection method that fits a model and removes the weakest feature (or features) until the specified number of features is reached. Features are ranked by the model’s coef_ or feature_importances_ attributes, and by recursively eliminating a small number of features per loop, RFE attempts to eliminate dependencies and collinearity that may exist in the model.

## Inference 

    -R-sqaured and Adjusted R-squared (extent of fit) - 0.925 and 0.920 - 90% variance explained.
    
    -F-stats and Prob(F-stats) (overall model fit) - 183.2 and 1.99e-70(approx. 0.0) - Model fir is significant and explained 90% variance is just not by chance.
    
    -p-values - p-values for all the coefficients seem to be less than the significance level of 0.05. - meaning that all the predictors are statistically significant.
