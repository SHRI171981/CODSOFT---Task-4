# Sales Prediction from Advertising Spend

## Problem statement

Businesses spend on TV, radio and newspaper advertising and need to know how much each channel contributes to sales, so they can allocate the budget wisely.

## Solution

A Jupyter notebook that explores the advertising dataset, checks for missing values and outliers, visualises how each channel relates to sales, and fits a Linear Regression model to predict sales from spend. The model achieves an **R² of about 0.91**, and a scatter plot of predicted against actual sales shows the fit.

## Tech stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter.

## Features

- Missing value check and outlier inspection
- Visualisation of the relationship between each channel and sales
- Linear Regression with train/test split
- Performance measured by R² and a predicted-vs-actual plot

## Future steps

- Regularised and non-linear models
- Interaction terms between channels
- Budget-allocation recommendations from the fitted coefficients

## Getting started

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook "4. Advertising.ipynb"
```
