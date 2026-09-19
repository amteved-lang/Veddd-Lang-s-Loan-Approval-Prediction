# Veddd-Lang-s-Loan-Approval-Prediction
Developed an end-to-end Machine Learning classification project to predict loan approval. Prepared and cleaned the dataset, encoded categorical variables, split the data into training and testing sets, trained a Logistic Regression model, generated predictions, evaluated the model using Accuracy, Precision, Recall and F1 Score .
# 🏦 Loan Approval Prediction

## Project Overview

This project is an end-to-end Machine Learning project that predicts whether a loan application will be approved or rejected.

The project demonstrates the complete Machine Learning workflow, including data loading, preprocessing, feature preparation, model training, prediction, and evaluation.

## Objective

The objective is to build a Machine Learning classification model that predicts loan approval based on applicant and loan information.

## Dataset

The dataset contains information about loan applicants, including:

- Applicant Income
- Coapplicant Income
- Loan Amount
- Credit Score
- Loan Term
- Property Area
- Employment Status
- Education
- Marital Status
- Loan Approval Status

The target variable is:

`LoanApproved`

### Target Classes

- `1` - Loan Approved
- `0` - Loan Rejected

### Dataset Note

This is a small educational dataset created specifically for demonstrating the Machine Learning workflow. It is not a real-world banking dataset and should not be used for actual lending decisions.

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas
- Checked missing values
- Checked duplicate records
- Removed duplicate records
- Converted categorical variables into numerical values using Label Encoding
- Converted the target variable into binary values
- Separated features and target variable
- Split the data into training and testing sets

## Machine Learning Model

### Logistic Regression

Logistic Regression was selected because the project is a binary classification problem.

The model predicts whether a loan application belongs to the Approved or Rejected category.

## Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The actual evaluation results are generated in the notebook.

## Visualizations

The project generates:

1. Confusion Matrix
2. Model Performance Comparison

## New Prediction

The trained model was also tested with a new sample loan application to demonstrate how the model can generate a prediction for unseen data.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git
- GitHub

## Project Files

- `loan_approval_prediction.ipynb` - Complete Machine Learning notebook
- `loan_approval_dataset.csv` - Educational loan dataset
- `confusion_matrix.png` - Confusion matrix visualization
- `model_evaluation.png` - Model performance visualization
- `README.md` - Project documentation

## Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Logistic Regression
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Confusion Matrix
