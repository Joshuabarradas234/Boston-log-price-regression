# Boston-log-price-regression
House price valuation model using multivariable regression and log(PRICE) for improved generalisation and stable residuals.
# Multivariable Regression + Valuation Model (Boston Housing)

Multivariable linear regression workflow using the Boston Housing dataset, including EDA, feature relationships, residual diagnostics, and a comparison between a raw PRICE model vs a log(PRICE) model (train/test evaluation).

## What this project shows
- Data loading + basic quality checks (missing values, duplicates)
- Exploratory analysis (distributions, pairplots, scatter plots)
- Baseline multivariable linear regression on PRICE
- Diagnostics (actual vs predicted, residuals vs predicted, residual distribution)
- log(PRICE) transformation to improve stability/generalisation
- Out-of-sample comparison using R² (test set)

## Key result (from the notebook)
The log(PRICE) model achieves better out-of-sample performance than the raw PRICE model, and residuals are more stable across the prediction range.

## How to run
### Option 1: Google Colab
1. Upload the notebook to Colab
2. Upload `boston.csv` to the Colab session (if required)
3. Run all cells

### Option 2: Local
```bash
pip install -r requirements.txt
jupyter notebook
