# Credit Card Fraud Detection

This repository contains a machine learning project that detects fraudulent credit card transactions. The work focuses on building and comparing multiple models under severe class imbalance (fraud is a very small fraction of all transactions), and evaluating performance using metrics that are appropriate for imbalanced classification (precision/recall, F1, ROC-AUC, and precision–recall curves).

## Project objective
- Identify fraudulent credit card transactions as accurately as possible
- Handle extreme class imbalance and reduce false negatives (missed fraud)
- Compare supervised and unsupervised approaches

## Dataset
- File: creditcard.csv
- Common columns in this dataset:
  - Time, Amount
  - V1–V28 (PCA-transformed features)
  - Class (0 = non-fraud, 1 = fraud)

Note: This dataset is highly imbalanced, so accuracy alone is not a reliable metric.

## Models included
Supervised
- Logistic Regression
- Random Forest Classifier

Unsupervised / anomaly detection
- Isolation Forest
- DBSCAN clustering

## Evaluation
Models are evaluated using a combination of:
- Confusion matrix
- Precision, recall, F1-score
- ROC-AUC
- Precision–recall curves (recommended for imbalanced datasets)

## How to run (local)
Clone the repository
```bash
git clone https://github.com/AnahitShekikyan/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection

