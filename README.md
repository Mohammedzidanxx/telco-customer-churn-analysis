# Telco Customer Churn Analysis

Exploratory data analysis and an interactive Streamlit dashboard investigating why telecom customers leave.

**Dataset:** [Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) - 7,043 customers, 21 columns.

## Status
Work in progress.

## Run locally
pip install -r requirements.txt
streamlit run app.py

## Project structure
- `data/` - raw dataset
- `notebooks/analysis.ipynb` - cleaning, feature engineering, EDA
- `app.py` - Streamlit dashboard
- `requirements.txt` - Python dependencies

## Data cleaning notes
`TotalCharges` has 11 blank values, all belonging to customers with tenure = 0 (new customers not yet billed). They were set to 0 instead of being dropped.
