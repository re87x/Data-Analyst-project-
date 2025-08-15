<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/IBM_logo.svg" alt="IBM logo" width="160">
</p>

# Data Analysis with Python – Final Project

This project is my full implementation of the Course 7 capstone in IBM’s Data Analyst Professional Certificate. It provides end-to-end analysis pipelines—data cleaning, EDA, feature engineering, and predictive modeling—across two real-world case studies (medical insurance charges and King County housing). The repo includes organized notebooks, requirements, and instructions to reproduce results and figures.

---

## Project Overview

This repository contains two case studies:

### 1) Insurance Cost Analysis
Analyze a medical insurance dataset to explore factors affecting charges and build regression models.

Key steps:
- Load and clean `insurance.csv`.
- Perform Exploratory Data Analysis (EDA) with statistical summaries and visualizations.
- Identify correlations between age, BMI, smoker status, and charges.
- Build and evaluate:
  - Single-variable Linear Regression.
  - Multivariable Linear Regression.
  - Ridge Regression for improved performance.

---

### 2) House Sales in King County, USA
Predict housing prices based on property features using a dataset from King County (including Seattle).

Key steps:
- Load and preprocess `kc_house_data.csv` (feature engineering for house age and renovation status).
- Analyze price distributions and correlations with features like square footage, grade, and location.
- Build and evaluate:
  - Multivariable Linear Regression.
  - Ridge Regression with cross-validation for optimal alpha selection.
  - Optional polynomial transformations for non-linear relationships.

---

## Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering and selection
- Predictive modeling (Linear and Ridge Regression)
- Model evaluation (R², MAE, RMSE)
- Visualization of correlations, distributions, and residuals

---

## Technologies Used
- Python 3.12
- pandas – Data manipulation
- numpy – Numerical computing
- matplotlib and seaborn – Visualization
- scikit-learn – Machine learning models and evaluation

---

## Project Structure
```
project-folder/
├─ insurance_analysis.ipynb       # Part 1 – Insurance cost analysis
├─ house_sales_analysis.ipynb     # Part 2 – King County house prices
├─ requirements.txt
├─ README.md
└─ data/
   ├─ insurance.csv
   └─ kc_house_data.csv
```

---

## How to Run
1) Clone the repository:
```bash
git clone <repo-url>
cd <repo-folder>
```

2) Install dependencies:
```bash
pip install -r requirements.txt
```

3) Run the Jupyter Notebooks:
```bash
jupyter notebook
```

---
