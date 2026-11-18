# ml-lab-4NI24CI114

# Machine Learning Lab

A collection of Jupyter notebooks covering foundational machine learning exercises, including linear and polynomial regression, regularization, $k$-fold cross-validation, and binary classification.

## Repository Contents

| Notebook | Description | Required Dataset |
| :--- | :--- | :--- |
| `linear-regression.ipynb` | Fits a simple linear regression model to study hours vs. marks, plots the regression line, and predicts marks for 10 study hours. | `linear_regression.csv` |
| `2 degree polynomial.ipynb` | Fits a quadratic polynomial from scratch by constructing the design matrix and solving the normal equations, then evaluates and plots the fit. | `Degree 2 Polynomial.csv` |
| `3 degree polynomial.ipynb` | Generates a small in-memory dataset, fits a cubic polynomial using `scikit-learn`, evaluates metrics, and plots the curve. | *None (built-in)* |
| `kfold.ipynb` | Demonstrates 5-fold cross-validation for linear regression and reports fold-level predictions and error metrics. | `k_fold_linear_regression (2).csv` |
| `regularization.ipynb` | Compares Ordinary Least Squares (OLS), Ridge, and a manual Lasso-style solution on synthetic data across train/val/test splits. | *None (built-in)* |
| `activity 1.ipynb` | Compares OLS, Ridge, and a manual Lasso-style solution on a small synthetic dataset, reporting split-level predictions and MSE. | *None (built-in)* |
| `activity 2.ipynb` | Trains a scaled logistic regression classifier on banknote data; evaluates metrics, decision thresholds, cross-validation, and a decision tree baseline. | `data_banknote_authentication.txt` |

## Prerequisites & Installation

Ensure you have **Python 3** installed, then install the required dependencies:

```bash
`python -m pip install numpy pandas matplotlib scikit-learn jupyter

## Dataset Setup
External datasets are not tracked in this repository. Download the required dataset files here and place them in the root directory alongside the notebooks before running them:

linear_regression.csv — Expects Hours_Studied and Marks columns.

Degree 2 Polynomial.csv — Expects X and Y columns.

k_fold_linear_regression (2).csv — Expects Hours_Studied and Marks columns.

data_banknote_authentication.txt — Headerless UCI Banknote Authentication file (4 feature columns + 1 class label column; headers are assigned in the notebook).

Note: 3 degree polynomial.ipynb, regularization.ipynb, and activity 1.ipynb generate their own synthetic data in-memory and can be run immediately without external files.


Getting Started
Clone or download this repository to your local machine.

Install the required Python packages listed above.

Add the datasets into the root folder alongside the notebooks.

Launch Jupyter from the repository directory and open any notebook:

Bash
jupyter notebook
Each notebook is standalone and can be executed independently. (Note: Running activity 2.ipynb will generate and save diagnostic plot images to your working directory.)
