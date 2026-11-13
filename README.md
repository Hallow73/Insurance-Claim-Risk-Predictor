# Auto Insurance Claim Prediction

A machine learning project that predicts the likelihood of an automobile insurance claim using historical insurance data. Includes data analysis, model comparison, and an interactive Streamlit application.

## Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Streamlit
- Joblib

## Machine Learning Models

- Decision Tree
- Random Forest
- XGBoost

## Project Workflow

1. **Data Exploration:** Analyzed insurance claim patterns and relationships between features using visualizations.
2. **Preprocessing:** Cleaned data, handled missing values, and encoded categorical variables.
3. **Feature Engineering:** Selected relevant features and prepared data for classification.
4. **Class Imbalance:** Applied techniques to address imbalanced claim outcomes.
5. **Model Training:** Trained Decision Tree, Random Forest, and XGBoost classifiers.
6. **Evaluation:** Compared models using classification metrics, ROC-AUC, and feature importance.
7. **Deployment:** Integrated the selected model into an interactive Streamlit application.

## Objective

Explore factors associated with automobile insurance claims and develop a classification model to predict claim likelihood based on policyholder and vehicle characteristics.

## Notebook

See `insurance_claim_prediction.ipynb` for the analysis and machine learning implementation.

## Dataset

This project uses the [Sample Insurance Claim Prediction Dataset](https://www.kaggle.com/datasets/easonlai/sample-insurance-claim-prediction-dataset) available on Kaggle.

- **Source:** Kaggle
- **Dataset:** Sample Insurance Claim Prediction Dataset
- **Prediction Task:** Classification — Predict whether an automobile insurance claim will occur.

## Streamlit Application

An interactive web application that allows users to enter policyholder and vehicle information to estimate insurance claim probability.

- **Live App:** [Auto Insurance Claim Predictor](https://auto-insurance-claim-predictor.streamlit.app)
