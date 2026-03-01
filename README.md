# Customer Lifetime Value Forecasting using XGBoost and RFM






A full Customer Lifetime Value (CLV) Prediction project constructed with RFM analysis and XGBoost Regression is included in this repository.

To help with business decision-making, the goal is to forecast future spending value by analyzing client transaction behavior.

📘 Project Overview
### How Businesses Benefit from Customer Lifetime Value (CLV):

Determine the high-value clients

Project future earnings

Make retention tactics better

Maximize the investment in marketing

This project shows how to create a prediction model using data from customer transactions.

# 📊 Dataset

dataset of synthetic transactions comprising:

1,000 clients

Ten thousand transactions

Dates of invoices

Amounts

Amounts purchased

⚙️ Project Process
1. Data Generation

Realistic transaction data was simulated for modeling purposes.

2. Feature Engineering with RFM

Determined:

Recency: The number of days since the last purchase

Frequency: The quantity of transactions

Financial: Total expenditure

used RFM grading based on quantiles.

3. Creation of Target Variables

made a Future_CLV variable simulation.

4. Model Training

XGBoost Regressor was used with:

Two hundred estimators

Rate of learning: 0.05

Maximum depth: 4.

80/20 Train/Test Split

5. Model Assessment

RMSE

R2 Score


Visualization of Feature Significance

# 📈 Results

Monetary value and frequency were strong predictors

Model achieved good regression performance

Feature importance provided business insights

# 🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

XGBoost

Matplotlib

### Install Dependencies
pip install -r requirements.txt
Run the Notebook
jupyter notebook
📌 Future Improvements

Use real-world e-commerce dataset

Perform hyperparameter tuning

Deploy model using Streamlit

Add customer segmentation clustering


## How to Run
1. Clone the repository:
```bash
https://github.com/jerem-a11y/customer_clv_prediction

