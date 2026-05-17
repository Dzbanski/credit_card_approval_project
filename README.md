# Credit Card Default Prediction

Machine Learning classification project focused on predicting whether a customer will default on their credit card payment.

---

## Project Goal

The goal of this project was to build a machine learning model capable of predicting customer default risk based on:

- demographic information,
- repayment history,
- bill statements,
- previous payments.

---

## Dataset

Dataset used:

```text
default_of_credit_card_clients.xls
```

Target variable:

- `0` → no default
- `1` → default

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Workflow

The project includes:

- data cleaning,
- exploratory data analysis,
- preprocessing pipeline,
- Random Forest classification,
- hyperparameter tuning with GridSearchCV,
- model evaluation,
- feature importance analysis,
- threshold tuning experiments.

---

## Model Performance

Final Random Forest results:

| Metric | Score |
|---|---|
| Accuracy | 0.79 |
| F1-score | 0.54 |
| ROC-AUC | 0.77 |

---

## Key Findings

- Payment history variables were the strongest predictors of default risk.
- Random Forest handled correlated financial features effectively.
- Feature engineering and feature selection experiments did not significantly improve performance.
- The model achieved balanced performance for both classes.

---

## Repository Structure

```text
credit_card_approval_project/
│
├── credit_card_approval_project.ipynb
├── default_of_credit_card_clients.xls
└── README.md
```

---

## Future Improvements

Possible future improvements:

- XGBoost comparison,
- advanced feature engineering,

---

## Author

Jacek Dzbański