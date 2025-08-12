# CUSTOMER-ANALYTICS-PROJECT

## Overview
This project analyzes customer data to identify patterns, predict churn, and group similar customers using clustering.  
It follows the assignment requirements for **data cleaning, EDA, preprocessing, feature selection, clustering, and evaluation**.

The dataset used is the **Telco Customer Churn dataset**, stored in an Excel file, with the path specified via a `config.yaml` file.

---

## Features
- Load dataset path dynamically from `config.yaml`
- Data cleaning:
  - Remove rows with >70% missing values
  - Fill remaining nulls with column means
  - Remove duplicates
- Exploratory Data Analysis (EDA):
  - Univariate, Bivariate, Multivariate visualizations
- Outlier removal using **IQR method**
- Feature scaling using **MinMaxScaler**
- Feature selection using:
  - Random Forest
  - AdaBoost
  - XGBoost
- Clustering with **DBSCAN**
- Model training & evaluation (Random Forest Classifier)
- F1 score reporting
- DBSCAN cluster visualization (PCA reduced)


---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   cd customer-churn-analysis

   

