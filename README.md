Name: Gagana S
Roll: DA25C008

# Credit Risk Default: Missing Data Imputation and Modeling

## Overview

This assignment explores strategies for handling missing data in a credit default dataset and evaluates their impact on classification performance. Four approaches are compared:
- Median Imputation
- Linear Regression Imputation
- Non-Linear Regression Imputation (KNN)
- Listwise Deletion

A logistic regression classifier is trained and evaluated for each strategy using standard performance metrics.

## Features

- Data imputation (median, regression, KNN)
- Data splitting and standardization
- Logistic regression model with hyperparameter tuning (GridSearchCV)
- Full classification report (accuracy, precision, recall, F1-score) for each strategy
- Summary and discussion on imputation efficacy

## Requirements

See `requirements.txt`. Minimal setup:
```
pandas
numpy
scikit-learn
```

## Usage

```bash
pip install -r requirements.txt
```
Then run the notebook or your main script.

## Project Structure

- `solution.ipynb` : Main workflow
- `requirements.txt`: Dependencies
- `UCl_Credit_Card.csv`: Place your dataset here

## Workflow

1. **Impute missing values** in raw data (median, linear, KNN).
2. **Create a dataset with listwise deletion**.
3. **Split each dataset** into training and testing sets.
4. **Standardize features** using `StandardScaler`.
5. **Tune and train logistic regression** using `GridSearchCV`.
6. **Evaluate and compare** classification reports.
7. **Summarize and discuss** findings.

## Results

A summary table compares the accuracy, precision, recall, and F1-score across all models. The recommended strategy for this scenario is regression-based imputation, which balances strong performance with conceptual soundness.



## Overview

This project explores different missing data handling strategies in a credit default classification task, including imputation (median, linear regression, KNN) and listwise deletion. Logistic regression classifiers are trained and tuned on each version of the dataset, and their performances are compared.

## Requirements

- See `requirements.txt`
  - pandas
  - numpy
  - scikit-learn

## Usage

1. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
2. Run the provided notebook or Python script.

## Workflow

- Impute missing values with median, linear regression, and KNN.
- Create a complete-case dataset by listwise deletion.
- Split all datasets into train/test sets.
- Standardize features using StandardScaler.
- Tune and train logistic regression models (GridSearchCV).
- Print classification reports for all models.

## Results

The project outputs a comparison table of classifier accuracy, precision, recall, and F1-score for each missing data strategy. Recommendations for best practice are included based on model efficacy and conceptual analysis.


