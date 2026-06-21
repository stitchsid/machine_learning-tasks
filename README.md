# Credit Scoring Model

## Overview
This project predicts whether a loan applicant is creditworthy based on their financial history using Machine Learning classification algorithms.

The model analyzes factors such as income, employment length, loan amount, loan intent, interest rate, and credit history to determine the likelihood of loan default.

---

## Objective

To build a machine learning model that can classify applicants into:

- Low Credit Risk
- High Credit Risk

This helps financial institutions make informed lending decisions.

---

## Dataset

Dataset: Credit Risk Dataset

Features include:

- Person Age
- Person Income
- Home Ownership
- Employment Length
- Loan Intent
- Loan Grade
- Loan Amount
- Interest Rate
- Loan Percent Income
- Historical Default Status
- Credit History Length

Target Variable:

- loan_status
  - 0 = No Default
  - 1 = Default

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Machine Learning Algorithms

### Logistic Regression
A statistical classification algorithm used as a baseline model.

### Decision Tree Classifier
A tree-based model that makes predictions using decision rules.

### Random Forest Classifier
An ensemble learning algorithm that combines multiple decision trees for improved accuracy.

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Missing Value Handling
4. Feature Encoding
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Feature Importance Analysis
9. Performance Comparison

---

## Evaluation Metrics

The following metrics are used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## Results

The models were compared based on their performance metrics.

Random Forest achieved the best overall performance and was selected as the final model.

---

## Feature Importance

The project identifies the most influential factors affecting creditworthiness.

Examples include:

- Loan Grade
- Interest Rate
- Income
- Loan Amount
- Credit History Length

---

## Visualizations

The project includes:

- Confusion Matrix
- ROC Curve
- Feature Importance Graph

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost Implementation
- LightGBM Implementation
- Model Deployment using Flask or Streamlit

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/credit-scoring-model.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Place the dataset file in the project folder

```
credit_risk_dataset.csv
```

4. Run the project

```bash
python credit_scoring_model.py
```

---

## Learning Outcomes

Through this project, I learned:

- Data Preprocessing
- Feature Engineering
- Classification Algorithms
- Model Evaluation
- Credit Risk Analysis
- Data Visualization
- Machine Learning Workflow

---

## Author

SIDRA RANGINWALA

AI & ML Student
