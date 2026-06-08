# Retail-Fraud-Detection
Retail Fraud Detection: Machine Learning

## Overview
This project explores fraud detection in retail transactions using machine learning techniques. The goal is to predict whether a transaction is fraudulent while balancing false positives and false negatives. The project includes exploratory data analysis (EDA), baseline model development, feature engineering, and model optimization.

## Dataset
Dataset: Retail Intelligence: Fraud Detection Dataset
Source: Kaggle (Noopur Bhatt)
File:
* `retail_fraud_detection_100k.csv`

The dataset contains 100,000 retail transactions and includes transaction information, customer behavior indicators, risk flags, and fraud labels.

## Repository Structure

* `retail_fraud_detection_100k.csv` — Dataset used for analysis and modeling
* `EDA.ipynb` — Exploratory Data Analysis, data inspection, visualizations, and feature investigation
* `Modeling.ipynb` — Baseline models, feature engineering, model optimization, and evaluation
* `report.pdf` — Final project report

## Methods

The following models were evaluated:

* Dummy Classifier
* Naïve Bayes
* Logistic Regression
* k-Nearest Neighbors (k-NN)

Performance was evaluated using:

* Accuracy
* F1 Score

Feature engineering included correlation-based feature selection and one-hot encoding of categorical variables.

## Results

Best-performing model:

* k-NN:
  * Accuracy: 0.9999
  * F1 Score: 0.9999

The unusually high performance is likely influenced by the balanced nature and simplified structure of the dataset, which may not fully reflect real-world fraud detection challenges.

## Requirements

Python libraries used:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Reproducing the Analysis

1. Clone the repository.
2. Install the required libraries.
3. Open and run `EDA.ipynb`.
4. Open and run `Modeling.ipynb`.
