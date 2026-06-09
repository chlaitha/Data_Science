# 🐍 Python Data Science Projects

This repository contains two beginner-friendly Python data science projects, each with a Jupyter Notebook and a dedicated README. Together they cover the full journey from **descriptive statistics** to **predictive machine learning**.

---

## 📁 Repository Structure

```
└── README.md                         # ← You are here
├── Statistics.ipynb                  # Notebook: descriptive statistics & visualisation
└── Regression Analysis.ipynb         # Notebook: head and brain prediction with ML
├── Predictive Analysis.ipynb         # Notebook: house price prediction with ML

```
---

## 📂 Projects at a Glance

### 1. 📊 Statistics Using Python
**File:** [Statistics.ipynb](https://github.com/chlaitha/Machine-Learning/blob/main/Statistics.ipynb)

An introduction to **descriptive statistics** using a custom dataset and the classic Iris dataset.

| What you'll learn | Tools used |
|---|---|
| Mean, Median, Mode | `statistics` (built-in) |
| Variance & Standard Deviation | `statistics.pvariance`, `stdev` |
| Summary statistics on real data | `pandas` `.describe()` |
| Pairwise feature visualisation | `seaborn` pairplot |

> 💡 **Key insight:** Demonstrates why the **median** is more reliable than the **mean** when outliers are present — a right-skewed dataset makes this tangible.

---

### 2. 🧠 Linear Regression — Brain Weight Prediction
**File:** [Linear_Regression.ipynb](https://github.com/chlaitha/Machine-Learning/blob/main/Linear%20Regression.ipynb)

A hands-on implementation of **Linear Regression from scratch**, then validated using Scikit-learn — predicting brain weight from head size measurements.

| What you'll learn | Tools used |
|---|---|
| Implementing regression manually (least squares) | `numpy` |
| Visualising regression lines & scatter plots | `matplotlib` |
| Calculating R² (coefficient of determination) | `pandas` |
| Validating with a ML library | `sklearn.linear_model` |

> 💡 **Key result:** Built Linear Regression from scratch using the least squares formula, then confirmed the result with Scikit-learn — both approaches yielding the same R² score.

---

### 3. 🏠 Predictive Analysis — House Price Prediction
**File:** [Predictive Analysis.ipynb](https://github.com/chlaitha/Machine-Learning/blob/main/Predictive%20Analysis.ipynb)

A complete **machine learning pipeline** that predicts house prices using Linear Regression, achieving a **92% R² score** on test data.

| What you'll learn | Tools used |
|---|---|
| Exploratory data analysis (EDA) | `pandas` |
| Visualising feature relationships | `seaborn` relplot |
| Train/test splitting | `sklearn.model_selection` |
| Building & evaluating a model | `sklearn.linear_model` |

> 💡 **Key result:** The model explains 92% of variance in house prices — a strong fit demonstrating the power of Linear Regression on structured data.

---

### 4. 🚗 Classification — SUV Purchase Prediction
**File:** [Logistic_Regression_SUV_Predictions.ipynb](https://github.com/chlaitha/Machine-Learning/blob/main/Logistic%20Regression%20SUV%20Predictions.ipynb)

A complete **classification pipeline** that predicts whether a user will purchase an SUV based on age and salary, using Logistic Regression and achieving **89% accuracy** on test data.

| What you'll learn | Tools used |
|---|---|
| Feature selection by index | `pandas` / `numpy` |
| Train/test splitting | `sklearn.model_selection` |
| Feature scaling | `sklearn.preprocessing` |
| Building & evaluating a classifier | `sklearn.linear_model` |

> 💡 **Key result:** The model correctly classifies 89% of unseen users as buyers or non-buyers — demonstrating Logistic Regression as a practical tool for binary classification problems.

## 🙌 Acknowledgements

Built with Python and the open-source data science ecosystem:
[pandas](https://pandas.pydata.org/) · [NumPy](https://numpy.org/) · [seaborn](https://seaborn.pydata.org/) · [scikit-learn](https://scikit-learn.org/) · [matplotlib](https://matplotlib.org/)
