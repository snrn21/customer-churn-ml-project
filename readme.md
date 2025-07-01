# Telco Customer Churn Prediction

This project predicts customer churn behavior for a telecommunications company using the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The analysis follows a structured data science workflow, including exploratory data analysis (EDA), data preprocessing, and applying multiple classification models to predict customer churn.

## Dataset Overview

- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Description**: The dataset contains information about ~7,000 customers, including demographics, account details, and service usage. The target variable is whether or not a customer has churned.

### Dataset Features
- **Demographic Information**: Age, gender, marital status, etc.
- **Account Information**: Account length, payment method, etc.
- **Service Details**: Monthly charges, tenure, etc.
- **Churn**: Whether the customer has churned (1) or not (0).

## Project Structure

The project follows a modular structure:

- `telco_churn_prediction.ipynb`: Main Jupyter notebook for the analysis, including EDA, preprocessing, and model training/evaluation.
- `requirements.txt`: Contains the necessary Python dependencies for the project.

## Models & Techniques

We experiment with several classification models to predict customer churn:

- **Logistic Regression**: A simple baseline model for binary classification.
- **Random Forest**: An ensemble tree-based model that is robust to overfitting.
- **XGBoost**: A gradient boosting model that often performs well in Kaggle competitions.
- **LightGBM**: A faster gradient boosting framework based on decision trees.
- **Gradient Boosting**: Another powerful boosting method that combines weak models to create a stronger one.

Each model is evaluated on standard classification metrics, including accuracy, precision, recall, and F1 score.

## Installation

To set up the project environment, install the required dependencies:

```bash
pip install -r requirements.txt