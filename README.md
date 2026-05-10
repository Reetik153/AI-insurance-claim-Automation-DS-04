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

