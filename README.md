# Loan Risk Prediction – Machine Learning Pipeline

This project implements a complete machine learning workflow for predicting loan approval status based on applicant data.

## Objective
To build and compare multiple ML models for binary classification (loan approved / rejected) and evaluate their performance using structured experimentation.

## Dataset
Structured tabular dataset containing:
- Applicant income
- Co-applicant income
- Credit history
- Loan amount
- Loan term
- Demographic features

## Workflow

1. Data Cleaning & Preprocessing
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. Exploratory Data Analysis (EDA)
   - Distribution analysis
   - Feature correlation
   - Class imbalance check

3. Model Training
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - KNN

4. Hyperparameter Tuning
   - GridSearchCV
   - Cross-validation

5. Model Evaluation
   - Accuracy
   - Confusion Matrix
   - Precision / Recall
   - F1 Score

## Results
Best performing model: K Neighbors	74.418605
6	Random Forest	74.418605

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## Future Improvements
- Pipeline refactoring using sklearn Pipeline
- Model export (joblib)
- API deployment using FastAPI
