# DS-04 Week 1 – Automated Model Evaluation Pipeline

## Project Overview

This project implements an automated machine learning model evaluation pipeline for insurance claim classification.

The pipeline:
- Loads insurance claim dataset
- Preprocesses the data
- Trains a Random Forest Classification model
- Evaluates model performance
- Calculates Accuracy, F1 Score, and AUC-ROC
- Stores evaluation metrics into a database
- Creates execution logs for monitoring

---

# Internship Task

Task Assigned:

> Set up automated model evaluation pipeline:
> runs nightly, stores accuracy/F1/AUC to metrics table in DB.

---

# Dataset Used

Dataset Name:
`claim_data.csv`

The dataset contains insurance claim information such as:
- Claim Status
- Claim Amount
- Provider Information
- Insurance Details
- Patient Information

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SQLAlchemy
- SQLite
- Joblib

---
# DS-04 Week 2 – SHAP Visualisations & Feature Importance Analysis

## Project Overview

This project focuses on explainable AI for insurance claim classification and fraud detection using SHAP (SHapley Additive Explanations).

The notebook:
- Trains a claim classification model
- Builds a fraud detection model
- Generates SHAP summary plots
- Creates feature importance visualisations
- Explains model predictions and important features

---

# Internship Task

Task Assigned:

> Build SHAP summary plots for claim classifier and fraud model, create feature importance bar charts.

Deliverable:
- SHAP visualisations notebook

---

# Dataset Used

Dataset:
`claim_data.csv`

The dataset contains:
- Claim information
- Patient details
- Claim status
- Financial claim data
- Insurance-related variables

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SHAP
- Matplotlib
- Joblib

---

# Project Structure

```text
project/
│
├── claim_data.csv
├── claim_classifier.pkl
├── DS_04_WEEK_2.ipynb
└── README.md
```

---

# Workflow

```text
Insurance Claim Dataset
        ↓
Data Preprocessing
        ↓
Feature Encoding
        ↓
Train Claim Classification Model
        ↓
Train Fraud Detection Model
        ↓
Generate SHAP Values
        ↓
Create SHAP Summary Plots
        ↓
Generate Feature Importance Charts
```

---

# Models Used

## 1. Claim Classification Model
- Random Forest Classifier

Purpose:
- Predict claim approval status

---

## 2. Fraud Detection Model
- Random Forest Classifier

Purpose:
- Identify potentially fraudulent claims

---

# SHAP Explainability

SHAP helps explain:
- Which features influence predictions
- Feature contribution importance
- Positive and negative impacts on model output

---

# Visualisations Generated

## SHAP Summary Plot
Displays:
- Most important features
- Feature impact distribution
- Direction of impact

---

## Feature Importance Bar Chart
Displays:
- Importance score of each feature
- Ranking of top influencing variables

---

# Features Analysed

Example features:
- Claim Amount
- Insurance Type
- Provider Information
- Patient Details
- Claim Status

---

# How to Run the Project

## Step 1 – Install Libraries

```bash
pip install pandas numpy scikit-learn shap matplotlib joblib
```

---

## Step 2 – Run Notebook

Open:

```text
DS_04_WEEK_2.ipynb
```

Run all cells.

---

# Output

The notebook generates:
- SHAP summary plots
- Feature importance charts
- Fraud model explainability plots

---

# Sample Insights

- Claim Amount strongly influences fraud prediction
- Insurance Type impacts approval probability
- Provider-related features affect model decisions

---

