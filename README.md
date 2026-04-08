# Machine Learning Algorithms Lab

This repository contains Python programs for Machine Learning lab experiments. The experiments cover basic Python scientific computing, dataset handling, dimensionality reduction, regression, classification, clustering, and model evaluation using libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

## Contents

| File | Description |
| --- | --- |
| `1.py` | Basic NumPy and Math operations such as floor, ceil, square root, GCD, array attributes, determinant, and eigen values. |
| `Exp_2.py` | Pandas Series operations and basic data handling. |
| `Exp_3.py` | Creation and loading of datasets using Pandas. |
| `Exp_4.py` | Dimensionality reduction using Principal Component Analysis (PCA) on the Iris dataset. |
| `Exp_5.py` | ID3 Decision Tree algorithm using the weather dataset. |
| `Exp_6.py` | Simple Linear Regression using Scikit-learn. |
| `Exp_7.py` | Logistic Regression on the Iris dataset with confusion matrix and performance metrics. |
| `Exp_8.py` | K-Nearest Neighbors classification on the Iris dataset. |
| `Exp_9.py` | Random Forest classification with different numbers of trees. |
| `Exp_10.py` | KNN classification with different values of K. |
| `Exp_11.py` | Support Vector Machine classification using Linear, Polynomial, and RBF kernels. |
| `Exp_12.py` | Clustering demonstration using generated blob data. |
| `Exp_13.py` | Simple and Multiple Linear Regression implementation. |
| `Exp_14.py` | Logistic Regression model for a given dataset. |
| `Exp_15.py` | Decision Tree classification model using the Titanic dataset. |
| `Exp_16.py` | Naive Bayes classification implemented from scratch. |
| `Exp_17.py` | ID3 Decision Tree demonstration using the Titanic dataset. |
| `Exp_18.py` | Naive Bayes classifier using the Iris CSV dataset. |
| `Exp_19.py` | K-Nearest Neighbors classification on the Iris dataset with correct and wrong predictions. |
| `Expp20.py` | Decision Tree classification using the Breast Cancer dataset. |
| `Exp21.py` | Naive Bayes classifier using the Olivetti Faces dataset. |
| `Exp22.py` | K-Means clustering using the Wisconsin Breast Cancer dataset with PCA visualization. |

## Datasets

The lab includes the following CSV datasets:

- `Iris.csv`
- `weather.csv`
- `Breast_Cancer.csv`
- `employee_turnover.csv`

Some experiments also use built-in datasets from Scikit-learn and Seaborn, such as Iris, Breast Cancer, Olivetti Faces, and Titanic.

## Requirements

Install the required Python libraries before running the programs:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## How to Run

Open a terminal in the `ma_lab` folder and run any experiment using Python:

```bash
python Exp22.py
```

For example:

```bash
python Exp_8.py
python Exp_14.py
python Exp22.py
```

Run the scripts from inside the `ma_lab` directory because some programs load CSV files using relative paths.

## Topics Covered

- NumPy and Pandas basics
- Dataset creation and loading
- Principal Component Analysis
- Linear Regression
- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine
- Random Forest
- Decision Tree and ID3 algorithm
- Naive Bayes classification
- K-Means clustering
- Model accuracy, classification reports, and visualization

## Notes

These programs are intended for academic lab practice and learning purposes. Some files are exported from Jupyter Notebook format, so they may contain notebook-style comments such as `# In[ ]`.
