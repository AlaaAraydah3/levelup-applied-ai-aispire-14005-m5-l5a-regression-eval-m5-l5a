# Telecom Customer Churn Prediction & Model Evaluation

A machine learning project that predicts customer churn and monthly charges using the Petra Telecom dataset. The project demonstrates end-to-end model development, preprocessing, evaluation, and performance comparison using Scikit-learn.

## Features

- Customer churn prediction using Logistic Regression.
- Monthly charge prediction using Ridge Regression.
- Data preprocessing with Scikit-learn Pipelines and StandardScaler.
- Model evaluation using classification and regression metrics.
- Cross-validation for robust model performance assessment.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

## Models

### Classification
- Logistic Regression
- Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
  - Stratified Cross-Validation

### Regression
- Ridge Regression
- Metrics:
  - Mean Absolute Error (MAE)
  - R² Score

## Results

| Model | Performance |
|-------|-------------|
| Logistic Regression | Accuracy: **63%** |
| Ridge Regression | **R² = 0.71**, **MAE = 10.61** |

## Project Structure

```
.
├── data/
│   └── telecom_churn.csv
├── lab_regression.py
├── requirements.txt
└── README.md
```

## Key Learnings

- Built reusable machine learning pipelines using Scikit-learn.
- Applied feature scaling with StandardScaler.
- Evaluated both classification and regression models.
- Compared model performance using appropriate evaluation metrics.
- Implemented train/test splitting and cross-validation following machine learning best practices.

## Future Improvements

- Perform feature engineering.
- Handle class imbalance using techniques such as SMOTE or class weighting.
- Experiment with ensemble models such as Random Forest and XGBoost.
- Tune hyperparameters using GridSearchCV.

## Author

**Alaa Araydah**

Bachelor of Electronics Engineering  
AI & Machine Learning Enthusiast
