# Employee Attrition Prediction Using Machine Learning

## Project Overview

This project develops machine learning models to predict employee attrition using HR Analytics data.

The study compares multiple classification algorithms and evaluates their performance using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

---

## Dataset

HR Employee Attrition Dataset

Records: ~14,999 employees

Target Variable:

- left
  - 0 = Employee stays
  - 1 = Employee leaves

Features include:

- Satisfaction level
- Last evaluation
- Number of projects
- Monthly hours
- Time spent in company
- Work accidents
- Promotions
- Department
- Salary

---

## Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting

---

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 90.04% |
| Decision Tree | 97.87% |
| Random Forest | 97.87% |
| SVM | 96.67% |
| Gradient Boosting | 97.92% |

Best Model: Gradient Boosting

---

## Installation

```bash
pip install -r requirements.txt
```

## Running the Project

```bash
jupyter notebook
```

Open:

```text
notebooks/Employee_Attrition_Analysis.ipynb
```

Run all cells sequentially.

---

## Project Workflow

Dataset
↓
Data Preprocessing
↓
Feature Engineering
↓
Model Training
↓
Hyperparameter Tuning
↓
Cross Validation
↓
Evaluation
↓
Model Comparison
↓
Final Model Selection

---

## Author

Awwal Fatima Muhammad
