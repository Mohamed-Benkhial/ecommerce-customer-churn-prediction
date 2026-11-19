# E-Commerce Customer Churn Prediction

## Project Overview

This project uses machine learning to predict customer churn in an e-commerce business. The objective is to identify customers who may leave and understand the factors associated with customer churn.

## Project Objectives

- Perform exploratory data analysis.
- Clean and preprocess customer data.
- Handle class imbalance.
- Train and compare machine learning models.
- Evaluate model performance.
- Identify important features affecting churn predictions.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Key Findings

Random Forest achieved the best overall performance in the initial model comparison, with an accuracy of 97.4% and an F1 Score of 91.8%.

The most important features identified through permutation importance include Tenure, Complain, PreferredOrderCat, MaritalStatus, and CashbackAmount.

_Note: These are preliminary test-set results and require further validation._

## Project Structure

```text
ecommerce-customer-churn-prediction/
│
├── README.md
├── requirements.txt
├── .gitignore
│
└── Notebook/
    ├── ecommerce_customer_churn_prediction.ipynb
    └── data/
        └── loblaws.xlsx
```

## How to Run

1. Clone this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Open the Notebook folder.
4. Launch the Jupyter Notebook.
5. Run the notebook cells.

## Disclaimer

This project is intended for educational and portfolio purposes.
