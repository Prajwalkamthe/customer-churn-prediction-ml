
# Customer Churn Prediction Using Machine Learning

## Project Overview

This project predicts whether a telecom customer is likely to leave the company (churn) using machine learning.

The project uses the Telco Customer Churn dataset and compares two Logistic Regression models: a baseline model and a class-balanced model.

## Objectives

- Explore and clean customer data.
- Analyze customer churn patterns.
- Preprocess categorical and numerical features.
- Train and evaluate Logistic Regression models.
- Compare model performance using classification metrics.
- Save the trained model for future predictions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Dataset

The project uses the Telco Customer Churn dataset.

The raw dataset is excluded from this repository. Obtain it from a legitimate source and place the CSV file at:

`data/raw/Telco-Customer-Churn.csv`

## Machine Learning Workflow

1. Data loading and inspection
2. Data cleaning
3. Exploratory Data Analysis (EDA)
4. Feature and target separation
5. Train-test split
6. Categorical encoding and numerical scaling
7. Logistic Regression model training
8. Model evaluation and comparison
9. Model saving and prediction verification

## Models

### Baseline Logistic Regression

- Accuracy: 80.55%
- Churn precision: 65.72%
- Churn recall: 55.88%
- Churn F1-score: 60.40%

### Class-Balanced Logistic Regression

- Accuracy: 73.81%
- Churn precision: 50.43%
- Churn recall: 78.34%
- Churn F1-score: 61.36%

The balanced model identifies a larger proportion of customers who churn, at the cost of lower precision and overall accuracy.

These results are from the project's current test split and should not be interpreted as guaranteed performance on new customers.

## Project Structure

```text
customer-churn-prediction-ml/
├── customer_churn.ipynb
├── requirements.txt
├── .gitignore
├── README.md
├── models/
├── outputs/
├── reports/
└── data/
    └── raw/
```

## How to Run

1. Clone or download this repository.
2. Install the required packages:

   `pip install -r requirements.txt`

3. Place the dataset at the path specified in the Dataset section.
4. Open `customer_churn.ipynb` in Jupyter Notebook.
5. Run the notebook cells in order.

## Future Improvements

- Compare additional classification algorithms.
- Tune model hyperparameters.
- Evaluate probability thresholds based on business needs.
- Build an interactive prediction application.
- Monitor model performance on new data.

## Author

Prajwal Kamthe
