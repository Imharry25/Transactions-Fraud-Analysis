# 💳 Fraud Risk Analysis Dashboard using Power BI

## 📌 Project Overview

This project focuses on **fraud detection and transaction behavior analysis** using a synthetic financial transaction dataset. The goal is to identify fraud trends, risk segments, and user patterns through an interactive and insightful Power BI dashboard.

---

## 📊 Dashboard Highlights

### 🧩 Dashboard 1: Fraud Detection Overview

- **Fraud Rate**: 32.13%
- **Total Transactions**: 50K  
- **High-Risk Transactions**: 20K  
- **Fraud Amount**: 1.60M  
- **Avg Risk Score**: 0.50

#### Key Visuals:
- No. of Transactions by **Type & Fraud Label**
- **Device-wise** fraud analysis (Tablet, Mobile, Laptop)
- **Location vs Risk Category** (Tokyo, NY, Sydney...)
- **Fraud by Merchant Category** (Clothing, Travel, Electronics)
- **Monthly Fraud Rate Trends**
- Fraud Label Legend: `0 = Normal`, `1 = Fraud`

---

### 📥 Dashboard 2: Transaction Behavior & User Insights

- **Total Transaction Amount**: 4.97M  
- **Unique Users**: 8,963  
- **Avg Daily Transactions**: 7.49  
- **Avg Failed Transactions**: 2  
- **Avg Transaction Amount**: 255.27

#### Key Visuals:
- Total Transaction Amount by **Device & Type**
- Avg Transaction Amount by **Fraud Status**
- Avg Risk Score by **Authentication Method**
- **Top 10 High Value Users** and **Top 10 Risky Users** (Toggle Switch)
- Monthly Trends of Transaction Volume

---

**Columns include**:  
`Transaction_ID`, `Timestamp`, `Location`, `Device_Type`, `Card_Type`, `Authentication_Method`, `Transaction_Amount`, `Risk_Score`, `Risk`, `Fraud_Label`, `Transaction_Type`, etc.

---

## 📷 Dashboard Screenshots

### 🛡️ Fraud Detection View  
![image](https://github.com/user-attachments/assets/cc950389-3a47-46d2-af8d-a88769c3e22d)


### 📈 Transaction Insights View  
![image](https://github.com/user-attachments/assets/cfdee54f-b87f-4d9d-9001-800537b42c7a)

---

## 🚀 Tools Used

- **Power BI** – Data visualization and dashboard creation  
- **DAX** – Measures & KPIs  
- **Excel / CSV** – Data preprocessing  
- **Color Palette** – Dark mode + color-blind friendly theme  
- **Power BI Bookmarks & Toggles** – For interactive view switching

---

## 🔗 Live Project Links

- 📊 [**Explore the Live Power BI Dashboard**](https://app.powerbi.com/groups/me/reports/f623d7dc-04d7-45fa-9281-99f7aa417837/7b8a4decb2b357cde8c7?experience=power-bi)

---

## 📈 Key Insights

- High concentration of frauds from **Tablet & Mobile users** and **Online/ATM withdrawal** transaction types
- **Restaurant, Groceries and Travel** categories contribute to >60% of fraud
- **Risk Score** above 0.7 is a strong fraud indicator.
- **Password & Biometric authentication** methods slightly riskier than OTP & PIN
- Most fraud cases are concentrated in **Tokyo, NY, Sydney**
- **August** has highest Fraud transactions 1434.
- **Mastercard** has highest fraud cases.
- High-value transactions tend to be lower risk, but still monitored.
- **User 9644** shows high value & high risk, making them a candidate for manual review or advanced monitoring.
- Dip seen in **February**, possibly due to fewer working days or off-peak cycle.
- **August** may correspond with shopping festivals or seasonal events leading to a surge in transactions
- Peak months for transaction volume: **August & December**.
- Fraudulent transactions tend to have a slightly higher average amount suggesting possible attempts to extract more value in each attack.
- **Password-based authentication** has a higher risk score, indicating it might be more vulnerable than OTP, PIN-based methods.
**Tablet users** have the highest transaction value, suggesting higher value transactions are preferred via tablet devices.


---

## 🏷️ Tags

`Power BI` `Fraud Detection` `Banking Analytics` `Risk Scoring` `Synthetic Dataset` `Data Analysis Project` `Interactive Dashboard` `DAX` `Data Visualization`
