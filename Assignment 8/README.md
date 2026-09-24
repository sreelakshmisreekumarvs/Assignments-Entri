# ML Assignment 4 – Regression Evaluation Metrics

## Purpose

This assignment evaluates regression techniques using the California Housing dataset. The models are compared using multiple evaluation metrics, followed by cross-validation and hyperparameter tuning to select a suitable regression model.

## Dataset

The assignment uses the **California Housing dataset** available through `sklearn.datasets.fetch_california_housing`.

The dataset contains information about housing characteristics in California and the corresponding median house values.

## Contents

The Jupyter Notebook includes:

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature scaling and missing-value handling
4. Implementation of:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Support Vector Regressor (SVR)
5. Model evaluation using:
   - Mean Squared Error (MSE)
   - Mean Absolute Error (MAE)
   - R-squared (R²)
6. Model comparison
7. 5-fold cross-validation
8. Hyperparameter tuning using GridSearchCV
9. Final regression model selection

## Requirements

Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

## How to Run

1. Download or clone this repository.
2. Open the Jupyter Notebook:

```bash
jupyter notebook
```

3. Open:

`ML_Assignment_4_Regression_Evaluation_Metrics_Answered.ipynb`

4. Run the notebook cells from beginning to end.

The California Housing dataset is downloaded through scikit-learn when the notebook is executed, so no separate dataset file is required.

## Files

- `ML_Assignment_4_Regression_Evaluation_Metrics_Answered.ipynb` – Main Jupyter Notebook containing the implementation, answers, evaluation, cross-validation, and hyperparameter tuning.
- `README.md` – Project description and instructions for running the notebook.

## Evaluation

The models are compared using MSE, MAE, and R². Five-fold cross-validation and hyperparameter tuning are also used to provide a more robust model comparison.

