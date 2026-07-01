# Real_estate_price_estimator

## Overview

This project uses machine learning to predict residential property prices using the Ames Housing dataset. The project covers the complete machine learning workflow, from data exploration and preprocessing to model training, evaluation and prediction.

The aim was to understand which housing features have the greatest influence on sale price and build a model capable of estimating property values.

## Dataset
- Ames Housing Dataset
- Nearly 3,000 residential property records
- Multiple features including property size, quality, number of bedrooms, bathrooms and year built

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Exploratory Data Analysis

The dataset was explored to understand the relationships between different housing features and sale price.
The analysis included:
- Distribution of house prices
- Living area vs sale price
- Overall quality vs sale price
- Bedrooms vs sale price
- Average sale price by neighbourhood
- Correlation heatmap

These visualisations helped identify the features that were most useful for predicting house prices.

## Machine Learning

A Linear Regression model was trained using the following features:

- Overall Quality
- Living Area
- Garage Area
- Full Bathrooms
- Bedrooms
- Year Built

The dataset was split into training and testing sets before fitting the model.

## Model Performance

| Metric | Result |
|---------|--------|
| Mean Absolute Error (MAE) | 26,881 |
| Root Mean Squared Error (RMSE) | 41,578 |
| R² Score | 0.784 |

The model explained approximately **78% of the variation** in house prices, showing that the selected features were strong predictors of property value.

## Key Takeaways

- Property quality and living area were among the strongest predictors of house price.
- House prices varied considerably across neighbourhoods.
- Linear Regression provided a baseline model for price prediction.

## Future Improvements

- Try Random Forest Regressor
- Try XGBoost
- Perform feature engineering
- Tune model hyperparameters
