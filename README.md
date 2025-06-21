# 💳 Real-Time Financial Fraud Detection System

An end-to-end project that simulates financial transactions and detects fraud using unsupervised machine learning (Isolation Forest). The results are visualized through an interactive Power BI dashboard.

---

## 📊 Project Overview

🔍 The goal of this project is to:
- Detect anomalies in transaction data (potential fraud)
- Use machine learning (Isolation Forest) for scoring
- Visualize fraud patterns in an interactive Power BI dashboard

---

## 🛠 Tech Stack

| Component      | Tools Used                          |
|----------------|--------------------------------------|
| Data Handling  | Python, Pandas, NumPy                |
| ML Modeling    | Scikit-learn (Isolation Forest)      |
| Dashboarding   | Power BI                             |
| Visualization  | Seaborn, Matplotlib                  |
| Automation     | Jupyter, Scripts, CSV Pipelines      |

---

## 📁 Folder Structure
Real-Time-Financial-Fraud-Detection/
├── data/
│ ├── transactions.csv # Raw generated data
│ └── fraud_scored.csv # Output with fraud predictions
├── scripts/
│ ├── generate_data.py # Creates synthetic transaction data
│ └── fraud_model.py # ML model with evaluation
├── notebooks/
│ └── eda.ipynb # Visual EDA & pattern analysis
├── dashboard/
│ ├── Fraud_Dashboard.pbix # Power BI Dashboard file
│ └── screenshots/ # Dashboard preview images
├── README.md # Project overview
└── requirements.txt # Python libraries


---

## 💡 Key Features

- ✅ Synthetic dataset of 5000+ financial transactions
- ✅ Fraud prediction using **Isolation Forest**
- ✅ Visual fraud trend analysis by device, city, and time
- ✅ Real-time fraud alerts simulation (Power BI)
- ✅ Model evaluated with confusion matrix & classification report

---

## 📈 Model Evaluation

| Metric       | Value     |
|--------------|-----------|
| True Positives (TP) | 13        |
| False Positives (FP)| 186       |
| True Negatives (TN) | 4624      |
| False Negatives (FN)| 177       |

📊 Confusion Matrix:
[[4624, 186],
[177, 13]]


---

## 📷 Dashboard Preview

> ✅ Built in Power BI Desktop  
> 📍 Location-wise fraud  
> 📱 Device-type fraud  
> 📉 Real-time trend chart  
> ⚠️ Fraud Rate & Suspicious Table

![Dashboard Screenshot 1](dashboard/screenshots/fraud_summary.png)  
![Dashboard Screenshot 2](dashboard/screenshots/device_trend.png)

---

## 🔍 How to Run This Project

### 1️⃣ Generate Data
python scripts/generate_data.py
### 2️⃣ Run the ML Model
python scripts/fraud_model.py
### 3️⃣ Launch Dashboard
Open dashboard/Fraud_Dashboard.pbix in Power BI Desktop
Connect to data/fraud_scored.csv
Enjoy real-time fraud visuals 🎯

✍️ Author
Dilip Raj. S
📍 Chennai, India
🎓 MBA in Finance & HR (Anna University)
🔗 LinkedIn | 🌐 Portfolio
📦 GitHub: dilipraj05
