# Loan Prediction

This repository contains a solution to the loan prediction problem sourced from the Analytics Vidhya competition [Practice Problem - Loan Prediction III](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/). The problem at hand is a binary classification task where the goal is to predict whether a loan will be approved or not based on various features.

## Problem Statement

The objective of this project is to build a predictive model that can accurately classify whether a loan application will be approved or rejected. The dataset provided includes several features such as applicant income, loan amount, credit history, etc., which are used to make these predictions.

## Data

The dataset for this project is available in the `data` directory. The dataset includes both training and test sets in CSV format (`train.csv` and `test.csv`). 

## Exploratory Data Analysis (EDA)

The notebook `loan_prediction_eda.ipynb` contains the exploratory data analysis performed on the dataset. It includes visualizations, summary statistics, and insights gained from the data exploration process. 

## Missing Values and Outlier Treatment

Handling missing values and outliers is crucial for building a robust predictive model. The notebook `missing_values_outliers.ipynb` details the methods used to address missing values and outliers in the dataset. 

## Model Building

The process of model building and evaluation is documented in the notebook `model_building.ipynb`. Various machine learning models such as logistic regression, decision trees, random forests, and gradient boosting were explored and evaluated using cross-validation techniques.

### Requirements

To reproduce the analysis and run the code, ensure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/loan-prediction.git
    ```
2. Navigate to the repository:
    ```bash
    cd loan-prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5. Open and run the notebooks in the following order:
    - `loan_prediction_eda.ipynb`
    - `missing_values_outliers.ipynb`
    - `model_building.ipynb`

Feel free to explore the notebooks, data, and code to understand the analysis and replicate the results.

## Contributors

- [Joyce Oluwasegun](https://github.com/joyceoluwasegun)

If you find any issues, have suggestions, or want to contribute to this project, please feel free to open an issue or create a pull request.

---

