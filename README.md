# House Price Prediction

This mini project predicts house sale prices using the Kaggle **House Prices: Advanced Regression Techniques** dataset. It walks through the basic machine learning pipeline: loading data, exploring important patterns, preparing features, training regression models, and comparing their performance.

## What This Project Does

- Explores how features like living area, quality, bedrooms, and neighborhood relate to sale price
- Handles missing values in numerical and categorical columns
- Encodes categorical features and scales the final feature set
- Selects the most useful features using `SelectKBest`
- Trains and compares two regression models:
  - Ridge Regression
  - Gradient Boosting Regressor
- Evaluates results using MAE, RMSE, R2, and MAPE
- Visualizes actual vs predicted prices and model residuals

## Dataset

The project uses the Kaggle House Prices dataset:

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

If running locally, download `train.csv` from Kaggle and place it in the same folder as the notebook.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How To Run

1. Open `house_price_prediction.ipynb` in Jupyter Notebook, JupyterLab, VS Code, or Kaggle.
2. Make sure the dataset file `train.csv` is available.
3. Run the notebook cells from top to bottom.

## Key Learning

This project shows how regression models can be used to estimate real-world house prices, and how preprocessing, feature selection, and model comparison can improve prediction quality.
