# Customer Analytics Project

## Project Overview
This project is developed as part of the **Stellara Academy Data Science Assignment**.  
It focuses on **analyzing customer data**, performing **exploratory data analysis (EDA)**, applying **machine learning for prediction**, and using **unsupervised clustering** to segment customers into meaningful groups.

The dataset used is the **Telco Customer Churn dataset**, stored in Excel format.  
The project adheres strictly to the given requirements, including:
- Loading the dataset path dynamically from `config.yaml`
- Cleaning and preprocessing data
- Performing univariate, bivariate, and multivariate analysis
- Removing outliers
- Feature scaling
- Feature selection using three algorithms
- Clustering using DBSCAN
- Model training, testing, and evaluation with **F1 score**
- Visualization of clustering results

---

## Objectives
1. Understand customer churn patterns through **EDA**.
2. Apply **data cleaning and preprocessing** for better model accuracy.
3. Perform **feature selection** using:
   - Random Forest
   - AdaBoost
   - XGBoost
4. Implement **DBSCAN clustering** to group similar customers.
5. Evaluate classification models using metrics like **F1 score**.

---

## Features Implemented
- **Config-based Dataset Loading**
  - Dataset path is stored in `config.yaml` for flexibility.
- **Data Cleaning**
  - Remove rows with >70% missing values.
  - Fill remaining missing values with column means.
  - Remove duplicate entries.
- **Exploratory Data Analysis**
  - **Univariate**: Histograms for each numerical feature.
  - **Bivariate**: Correlation heatmap.
  - **Multivariate**: Pairplots for first 4 numerical features.
- **Outlier Removal**
  - IQR method applied before scaling.
- **Feature Scaling**
  - MinMaxScaler applied to all numeric features.
- **Feature Selection**
  - Feature importance extracted from Random Forest, AdaBoost, and XGBoost.
- **Clustering**
  - DBSCAN applied to group customers.
  - PCA used for 2D visualization of clusters.
- **Model Training & Evaluation**
  - Random Forest Classifier for churn prediction.
  - Classification report and F1 score output.
- **Visualizations**
  - EDA plots.
  - DBSCAN cluster plot (PCA reduced).
  - Silhouette score analysis.

---

## Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   cd customer-churn-analysis
2. **Dependencies**
    ```bash
   pip install -r requirements.txt
4. **Dataset Path**
    ```bash
   data_source: "C:/path/to/WA_Fn-UseC_-Telco-Customer-Churn.xlsx"

## License
This project is licensed under the MIT License – feel free to use and modify it.

## Author
**Vijay V S**  
GitHub: [vijayvs73](https://github.com/vijayvs73)

## Connect with Me
Feel free to connect with me on  
[LinkedIn](www.linkedin.com/in/vs-vijay)




