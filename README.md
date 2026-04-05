# Health Insurance Analysis

Notebook-based Python analysis of U.S. medical insurance costs and the variables that most strongly influence insurance charges.

## Project focus

This project explores how insurance charges shift across factors such as:

- age
- BMI
- smoking status
- number of children
- region

The notebook combines exploratory analysis with predictive modeling so the work does not stop at charts alone.

## Methods used

- Exploratory data analysis with pandas, Seaborn, and Matplotlib
- Feature-level comparison of charge drivers, including smoker and BMI effects
- Predictive modeling with:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Hyperparameter tuning with GridSearchCV for the gradient boosting model

## Repo layout

- `US Medical Insurance Costs Analysis.ipynb` - the main analysis notebook

## Run locally

Place the expected `insurance.csv` dataset next to the notebook, then run:

```bash
jupyter notebook "US Medical Insurance Costs Analysis.ipynb"
```

## Why this repo is in the portfolio

This project shows a practical analysis flow: understand the dataset, identify meaningful business drivers, compare baseline and ensemble models, and use the notebook as both a working document and a communication artifact.
