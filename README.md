# 🤖 Machine Learning Lab

Welcome to my **Machine Learning Lab Repository!**

This repository contains Jupyter Notebooks covering fundamental Machine Learning concepts and their practical implementations using Python. It includes regression techniques, regularization methods, cross-validation, and classification algorithms.

## 📂 Repository Contents

| Notebook | Description |
|---|---|
| `activity 1.ipynb` | Implements and compares Ordinary Least Squares (OLS), Ridge Regression, and a manually calculated Lasso-style solution using a synthetic dataset. |
| `activity 2.ipynb` | Explores the UCI Banknote Authentication dataset using Logistic Regression and Decision Tree classification. Covers scaling, classification metrics, thresholds, and cross-validation. |
| `2 degree polynomial.ipynb` | Implements quadratic polynomial regression using a design matrix and normal equations. Includes predictions and visualization. |
| `3 degree polynomial.ipynb` | Demonstrates cubic polynomial regression using Scikit-learn with model evaluation and visualization. |
| `kfold.ipynb` | Demonstrates 5-Fold Cross-Validation for Linear Regression and evaluates performance across different folds. |
| `linear-regression.ipynb` | Implements Simple Linear Regression using study hours and marks, with visualization and prediction. |
| `regularization.ipynb` | Compares OLS, Ridge Regression, and a manually calculated Lasso-style solution using a synthetic dataset. |

## 🛠️ Technologies Used

- 🐍 Python 3
- 📓 Jupyter Notebook
- 🔢 NumPy
- 🐼 Pandas
- 📊 Matplotlib
- ⚙️ Scikit-learn

## ⚙️ Installation & Setup

**1. Clone the repository**

```bash
git clone <repository-url>
```

**2. Navigate to the project directory**

```bash
cd <repository-folder>
```

**3. Install the required libraries**

```bash
python -m pip install numpy pandas matplotlib scikit-learn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

## 📊 Dataset Requirements

Some notebooks require external datasets.

📥 **[Download the required CSV and dataset files here](https://tinyurl.com/4h5mahd5)**

After downloading, place the files in the same directory as the notebooks.

| Notebook | Required Dataset | Expected Columns |
|---|---|---|
| `2 degree polynomial.ipynb` | `Degree 2 Polynomial.csv` | `X`, `Y` |
| `kfold.ipynb` | `k_fold_linear_regression (2).csv` | `Hours_Studied`, `Marks` |
| `linear-regression.ipynb` | `linear_regression.csv` | `Hours_Studied`, `Marks` |
| `activity 2.ipynb` | `data_banknote_authentication.txt` | Four features followed by the class label |

**Note:** The Banknote Authentication dataset is loaded without a header. Column names are assigned within the notebook.

The following notebooks generate their own sample datasets and do not require external files:

- `activity 1.ipynb`
- `regularization.ipynb`
- `3 degree polynomial.ipynb`

## 🚀 How to Run

1. Open the repository in Jupyter Notebook or JupyterLab.
2. Ensure all required datasets are available in the project directory.
3. Open the notebook you want to execute.
4. Run the cells sequentially to explore the implementation, predictions, evaluation metrics, and visualizations.

## 📚 Concepts Covered

- Linear Regression
- Polynomial Regression (2nd and
