# Fraud Detection using Machine Learning

## Project Overview

This project develops a machine learning system to detect fraudulent financial transactions using a highly imbalanced transaction dataset.

## Dataset

- Total Transactions: 10,000
- Normal Transactions: 9,849 (98.49%)
- Fraudulent Transactions: 151 (1.51%)
- Target Variable: `is_fraud`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook / Google Colab

## Methodology

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Class Imbalance Analysis
5. Categorical Feature Encoding
6. Stratified Train-Test Split
7. Feature Scaling
8. SMOTE for Class Balancing
9. Logistic Regression
10. Random Forest
11. Model Evaluation

## Models and Results

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 96.45% | 28.87% | 93.33% | 44.09% | 99.32% |
| Random Forest | 99.35% | 79.31% | 76.67% | 77.97% | 99.81% |

## Key Findings

Random Forest achieved the best overall balance between Precision, Recall and F1-Score.

Recall is especially important in fraud detection because missing a fraudulent transaction can cause financial loss.

## Future Improvements

- Threshold tuning for better fraud recall
- XGBoost implementation
- Real-time fraud detection
- Model monitoring and drift detection
- Deployment using an API

## Project Files

- `Fraud_Detection.ipynb` - Complete machine learning notebook
- `requirements.txt` - Required Python libraries
