# Canada Per Capita Income Prediction - Linear Regression

This project demonstrates the use of **Linear Regression** to predict Canada's per capita income based on historical data.

## Project Description
The goal is to model and understand how Canada's per capita income has changed over time and to use that model to predict future values.

## Files Included
- **year.csv:** Contains the input feature data (`Year`).
- **canada_per_capita_income.csv:** Contains historical `Year` and `Per Capita Income (USD)` used for training.
- **predicted_per_capita_income.csv:** Contains the predicted per capita income for each year generated by the trained model.

## How It Works
- The historical data is used to train a simple linear regression model.
- The model finds the best-fit line to represent the relationship between `Year` and `Per Capita Income`.
- Once trained, the model predicts the per capita income for the given years.
- The output predictions are saved to a new CSV file.
- The results can be visualized to compare the historical data and the model's predictions.

## Theory - Linear Regression
Linear Regression is a fundamental supervised learning algorithm that models the relationship between a dependent variable (per capita income) and an independent variable (year). It assumes a linear relationship, meaning it tries to draw a straight line through the data points that best represents this relationship.

## Requirements
- Python 3.x
- Libraries: pandas, scikit-learn, matplotlib

## Output
- A CSV file containing predicted income values.
- A visualization showing the historical trend and the model's prediction.

## Author
**Your Name**  
**Date:** YYYY-MM-DD

