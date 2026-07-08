# Fraud-Detection-in-Financial-Transactions
An end-to-end Fraud Detection project using Python, Isolation Forest, and Power BI to identify suspicious financial transactions through anomaly detection and interactive business dashboards.


# 🚨 Fraud Detection in Financial Transactions

## 📌 Project Overview

Financial fraud is one of the biggest challenges faced by banks, payment gateways, and financial institutions. Detecting fraudulent transactions quickly is essential to minimize financial losses, improve customer trust, and strengthen security.

This project presents an end-to-end **Fraud Detection System** using **Python**, **Isolation Forest**, and **Power BI**. It covers the complete analytics workflow, including data cleaning, exploratory data analysis (EDA), anomaly detection, model evaluation, and interactive dashboard development to identify suspicious financial transactions and support business decision-making.

---

# 🎯 Objectives

- Detect suspicious financial transactions using the **Isolation Forest** anomaly detection algorithm.
- Perform comprehensive **Exploratory Data Analysis (EDA)** to understand transaction patterns.
- Evaluate model performance using classification metrics.
- Build an interactive **Power BI Dashboard** for fraud monitoring and business insights.
- Demonstrate an end-to-end Data Analytics and Machine Learning workflow.

---

# 📂 Dataset

**Dataset Name:** Credit Card Fraud Detection Dataset

**Source:** Kaggle

### Dataset Features

| Feature | Description |
|----------|-------------|
| Time | Time elapsed between transactions |
| Amount | Transaction amount |
| V1 – V28 | Anonymized features obtained using PCA |
| Class | Target Variable (0 = Genuine, 1 = Fraud) |

### Dataset Statistics

- **Total Transactions:** 284,807
- **Fraud Transactions:** 492
- **Genuine Transactions:** 284,315

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning, EDA & Machine Learning |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Exploratory Data Analysis |
| Scikit-learn | Isolation Forest Algorithm |
| Power BI | Interactive Dashboard & Business Intelligence |
| Git & GitHub | Version Control & Project Hosting |

---

# 📊 Project Workflow

```text
Credit Card Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Isolation Forest Model
        │
        ▼
Fraud Prediction
        │
        ▼
Model Evaluation
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Transaction Class Distribution (Fraud vs Genuine)
- Transaction Amount Distribution
- Fraud vs Genuine Amount Comparison
- Correlation Heatmap
- Transaction Time Distribution
- Transaction Amount vs Class (Boxplot)

---

# 🤖 Machine Learning Model

### Algorithm Used

**Isolation Forest**

### Why Isolation Forest?

- Designed specifically for anomaly detection.
- Works effectively on highly imbalanced datasets.
- Detects unusual transaction behavior without requiring balanced training data.
- Efficient for identifying rare fraudulent transactions.

---

# 📉 Model Evaluation

The model was evaluated using:

- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

These evaluation metrics help measure the effectiveness of the model in detecting fraudulent transactions.

---

# 📊 Power BI Dashboard

The interactive dashboard includes:

- Total Transactions
- Fraud Percentage
- Total Transaction Amount
- Predicted Fraud Transactions
- Predicted Genuine Transactions
- Fraud vs Genuine Transaction Distribution
- Predicted Transactions by Status
- Transaction Amount Distribution
- Transaction Trend Over Time
- Transaction Amount vs Time Analysis
- Interactive Filters and Slicers

---

# 💼 Business Insights

- Fraudulent transactions account for a very small percentage of all financial transactions.
- Isolation Forest successfully identifies anomalous transaction patterns.
- High-value and unusual transactions can be prioritized for further investigation.
- Interactive dashboards enable analysts to monitor fraud trends efficiently.
- The solution supports data-driven decision-making for fraud prevention and risk management.

---

# 🚀 Future Enhancements

- Real-time fraud detection using streaming transaction data.
- Compare Isolation Forest with Random Forest and XGBoost.
- Implement AutoEncoder-based anomaly detection.
- Deploy the model using Flask or Streamlit.
- Integrate automated fraud alert notifications.
- Improve prediction accuracy using additional transaction features.

---

# 📷 Dashboard Preview

> **Fraud Detection Dashboard**

<img src="Images/Fraud_Dashboard.png" width="1000">

---

# 📁 Project Structure

```text
Fraud-Detection-in-Financial-Transactions
│
├── Data
│   └── creditcard.csv
│
├── Notebook
│   └── Fraud_Detection.ipynb
│
├── Dashboard
│   └── Fraud_Detection_Dashboard.pbix
│
├── Output
│   └── Fraud_Detection_Result.csv
│
├── Images
│   └── Fraud_Dashboard.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 📌 Results

The project successfully demonstrates an end-to-end fraud detection workflow by combining **Python**, **Machine Learning**, and **Power BI**. The Isolation Forest model effectively identifies anomalous transactions, while the interactive dashboard provides meaningful insights into fraud patterns, transaction behavior, and business performance.

---

# 👨‍💻 Author

**Anmol Rana**

**Computer Science Engineering (Big Data & Analytics)**

### 🔗 Connect with Me

- **GitHub:** https://github.com/ANMOL8081
- **LinkedIn:** https://www.linkedin.com/in/anmol-rana-041b37249/
Computer Science Engineering (Big Data & Analytics)
