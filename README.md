# Titanic Survival Prediction: Feature Engineering, Model Evaluation and Hyperparameter Optimization

## Overview
This project predicts passenger survival using a complete machine learning workflow.

It is designed as a professional portfolio project for entry-level AI Engineer, Machine Learning Engineer, and Junior Data Scientist applications.

## Key Skills Demonstrated
- Exploratory Data Analysis
- Feature Engineering
- Data Cleaning
- Missing Value Imputation
- One-Hot Encoding
- Feature Scaling
- Scikit-Learn Pipelines
- Cross-Validation
- Model Comparison
- Hyperparameter Tuning with GridSearchCV
- Classification Metrics
- Confusion Matrix
- ROC Curve
- Feature Importance Analysis

## Repository Structure

```text
Feature_Engineering_Model_Evaluation_Portfolio_Project/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── Titanic_Survival_Prediction_Portfolio_Project.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   └── evaluate.py
│
├── images/
├── models/
├── requirements.txt
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/Titanic_Survival_Prediction_Portfolio_Project.ipynb
```

4. Place your Titanic dataset in:

```text
data/titanic.csv
```

The notebook also includes a fallback loader that can use Seaborn's Titanic dataset when available.

## Models Compared
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Recommended Portfolio Improvements
Future extensions can include:
- SHAP explainability
- Model deployment with Streamlit or FastAPI
- MLflow experiment tracking
- Docker packaging
