# Customer Churn Prediction Project

## Overview

This project focuses on analyzing and predicting customer churn in telecom services. The project involves data exploration, preprocessing, feature engineering, and building machine learning models to identify customers at risk of leaving.

## Project Objectives

- **Exploratory Data Analysis (EDA)**: Understand patterns and relationships in customer data
- **Data Preprocessing**: Clean and prepare data for modeling
- **Feature Engineering**: Create meaningful features for prediction
- **Model Development**: Build and evaluate ML models for churn prediction
- **Insights & Recommendations**: Provide actionable insights to reduce churn

## Dataset

- **Source**: Telco Customer Churn dataset
- **File**: `Telco_customer_churn.xlsx`
- **Location**: `data/raw/`

## Project Structure

```
customer-churn-project/
├── data/
│   ├── raw/                          # Raw data files
│   │   └── Telco_customer_churn.xlsx
│   └── processed/                    # Cleaned and processed data
├── notebooks/
│   └──1_raw_data.ipynb       
│   └──2_raw_data.ipynb   
├── README.md                         # Project documentation
```

## Technologies Used

- **Python 3.x**
- **pandas**: Data manipulation and analysis
- **scikit-learn**: Machine learning models
- **openpyxl**: Excel file handling
- **Jupyter Notebook**: Interactive analysis and documentation

## Installation & Setup

1. Clone or navigate to the project directory
2. Install required dependencies:
   ```bash
   pip install pandas openpyxl scikit-learn jupyter matplotlib seaborn
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
