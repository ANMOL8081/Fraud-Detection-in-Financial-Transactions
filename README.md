# Fraud-Detection-in-Financial-Transactions
An end-to-end Fraud Detection project using Python, Isolation Forest, and Power BI to identify suspicious financial transactions through anomaly detection and interactive business dashboards.


# Fraud Detection in Financial Transactions
Project Overview:

Financial fraud has become a significant challenge for banks and payment service providers. Detecting fraudulent transactions quickly is essential to minimize financial losses and protect customers.

This project develops an end-to-end fraud detection system using Python, Isolation Forest, and Power BI. The workflow includes data cleaning, exploratory data analysis (EDA), anomaly detection, model evaluation, and interactive dashboard creation for business insights.

Objectives:
Detect suspicious financial transactions using anomaly detection.
Analyze transaction patterns through Exploratory Data Analysis.
Evaluate model performance using classification metrics.
Build an interactive Power BI dashboard for fraud monitoring.

Dataset:

Dataset Name

Credit Card Fraud Detection Dataset

Source

Kaggle

Dataset Features

Time
Amount
V1–V28 (Anonymized Features)
Class
0 = Genuine
1 = Fraud

Total Records

284,807
Technologies Used
Technology	Purpose
Python	Data Cleaning & Machine Learning
Pandas	Data Manipulation
NumPy	Numerical Computing
Matplotlib	Visualization
Seaborn	EDA
Scikit-learn	Isolation Forest
Power BI	Dashboard
GitHub	Version Control


Project Workflow:
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Isolation Forest
      │
      ▼
Fraud Prediction
      │
      ▼
Model Evaluation
      │
      ▼
Power BI Dashboard


Exploratory Data Analysis
Performed the following analyses:
  Transaction Class Distribution
  Transaction Amount Distribution
  Fraud vs Genuine Distribution
  Correlation Heatmap
  Transaction Time Distribution
  Boxplot of Amount vs Class
  
Machine Learning:
Algorithm Used

Isolation Forest

Reason

Effective for anomaly detection.
Suitable for highly imbalanced datasets.
Does not require balanced training data.

Dashboard Features:

The Power BI dashboard includes:

Total Transactions
Fraud Percentage
Total Transaction Amount
Predicted Fraud Transactions
Predicted Genuine Transactions
Fraud vs Genuine Distribution
Transaction Amount Distribution
Transaction Trend Over Time
Transaction Amount vs Time
Interactive Filters
Business Insights
Fraudulent transactions account for a very small percentage of all transactions.
Isolation Forest successfully identifies anomalous transactions.
Interactive dashboards help analysts monitor suspicious activities.
High-value anomalies can be prioritized for investigation.

Future Improvements:
Real-time fraud detection.
AutoEncoder implementation.
XGBoost comparison.
Fraud alert notifications.
Model deployment using Flask or Streamlit.

Results:

The project successfully detects anomalous transactions and visualizes fraud insights through an interactive Power BI dashboard.

Author

Anmol Rana

Computer Science Engineering (Big Data & Analytics)
