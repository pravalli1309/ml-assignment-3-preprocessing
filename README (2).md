# ML Assignment 3 Data preprocessing

Notebook: `assignment3_preprocessing.ipynb` (run top to bottom with Runtime -> Restart and run all).
Fitted pipeline: `pipeline.joblib`

## Dataset
Credit Risk Dataset (loan applications; target `loan_status`: 1 = default)
Source: https://www.kaggle.com/datasets/laotse/credit-risk-dataset
File used: `credit_risk_dataset.csv`

## Quick facts from this run
- Rows: 32581 | train: 26064 | test: 6517
- Default rate (minority class): 0.218
- Pipeline output columns: 20 (train and test match)
- Train class counts before SMOTE: {0: 20378, 1: 5686}
- Train class counts after SMOTE:  {0: 20378, 1: 20378}
