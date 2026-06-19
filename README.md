# Credit Card Approval Prediction Using PyCaret

This repository contains the implementation and experimental results for the research:

**Machine Learning Model Evaluation and Optimization for Credit Card Approval Prediction Using PyCaret**

## Overview

This study evaluates machine learning models for credit card approval prediction using the PyCaret Automated Machine Learning (AutoML) framework. Two class imbalance handling strategies were compared:

1. SMOTE-based imbalance handling using PyCaret.
2. Random undersampling before model development.

## Dataset

- Credit Card Approval Prediction (Cleaned Version)
- Total records: 25,128
- Predictor variables: 20
- Target variable: Application Status

Dataset Source:  
https://www.kaggle.com/datasets/caesarmario/application-data

## Experimental Results

### Experiment 1 – SMOTE-Based Classification
- Best Model: Random Forest
- Accuracy: 99.68%
- Recall (Rejected Class): 36.11%
- Cohen's Kappa: 0.5187
- MCC: 0.5780

### Experiment 2 – Random Undersampling-Based Classification
- Best Model: Gradient Boosting
- Accuracy: 98.63%
- Recall (Rejected Class): 100%
- Cohen's Kappa: 0.9726
- MCC: 0.9730

## Files

- `Application_Data.csv` – Dataset
- `credit_card_approval_final.ipynb` – Main notebook
- `credit_card_approval_final_model.pkl` – Trained model
- `requirements.txt` – Required Python libraries

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
jupyter notebook credit_card_approval_final.ipynb
```

## Author

Mario Suryowisnu Wicaksono  
Informatics Engineering – Data Science  
Universitas Kristen Satya Wacana