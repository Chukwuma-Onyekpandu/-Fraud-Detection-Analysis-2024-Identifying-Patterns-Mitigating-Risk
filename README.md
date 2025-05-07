# 🕵️‍♂️ Fraud Detection Analysis: Identifying Patterns & Mitigating Risk

**Author:** Onyekpandu Chukwuma  
**Prepared For:** Fintech Company Management, Fraud Detection Team, Security Operations  
**Year:** 2024  
![Dashboard](https://github.com/Chukwuma-Onyekpandu/-Fraud-Detection-Analysis-2024-Identifying-Patterns-Mitigating-Risk/blob/main/Vephla%20Excel%20Dashboard%205%20Corrected.png)
---

## 📌 Overview

This project analyzes over 51,000 fintech transaction records to uncover fraud patterns and recommend strategic interventions. Using exploratory data analysis (EDA), we highlight how transaction types, devices, locations, and payment methods correlate with fraud risk.

---

## 📂 Dataset Description

Each record includes:

- `transaction_id`, `user_id`
- `transaction_amount`, `transaction_type`, `payment_method`
- `device_used`, `location`, `account_age`, `transaction_time`
- `previous_fraud_count`, `transactions_last_24hrs`
- `fraud_status` (Fraudulent or Legitimate)

---

## 🧹 Preprocessing

- Cleaned and validated all data types
- Addressed missing or inconsistent entries
- Ensured quality and consistency for analysis

---

## 🎯 Analysis Goals

- Identify high-risk transaction types and locations
- Uncover fraud-prone payment methods and devices
- Explore correlations between account age, transaction behavior, and fraud

---

## 🔍 Key Findings

### General Insights

- **Most Common Transaction Type:** Bills Payment (20.27%)
- **Top Payment Volume:** UPI ($28.1M)
- **Most Used Device:** Laptop (33.7%)
- **Top Transaction City:** Boston ($14.6M)
- **Average Account Age:** ~60 days
- **Overall Fraud Rate:** 4.8%

### Fraud Patterns

- **Most Fraudulent Payment Method:** UPI ($1.46M)
- **Most Fraudulent Device:** Mobile (35.58%)
- **Highest Risk Transaction Type:** Online Purchases (20.88% fraud rate)
- **Top Fraud Cities:** Chicago ($792K), Boston ($753K)

---

## 🏙️ City-Level Breakdown

| City     | Most Used Method | Top Device | Fraud-Prone Type     |
|----------|------------------|------------|-----------------------|
| Boston   | UPI              | Laptop     | ATM Withdrawals       |
| Chicago  | Credit Card      | Laptop     | Bills Payment         |
| Houston  | Net_Banking      | Mobile     | Bank Transfers        |

---

## 📊 Visualizations

> (Built using Power BI, Excel, and Python)

- Column Charts: Transaction amount by type, method, device
- Pie Charts: Transaction type distribution, fraud ratio
- Line Chart: Avg account age per transaction type
- Bar Charts: Location-wise transaction and fraud volume

---

## ✅ Recommendations

- **Enhance Mobile Security**: Multi-factor auth, device fingerprinting
- **UPI & Credit Card Monitoring**: Velocity checks, real-time alerts
- **Location-Specific Rules**: Tighter controls in Chicago and Boston
- **Behavioral Models**: Use ML to detect deviations from user patterns
- **User Education**: Raise awareness on phishing, secure practices

---

## 🛠 Tools Used

- **Excel**  
- **Power BI**  
- **Python** (Seaborn, Matplotlib, Pandas)

---

## 📁 Appendix

- **Appendix A:** Raw and Cleaned Data Samples  
- **Appendix B:** Additional Charts  
- **Appendix C:** Methodology Overview  

---

## 📬 Contact

For feedback, collaboration, or questions:  
📧 [your.email@example.com]  
🔗 [LinkedIn](www.linkedin.com/in/chukwuma-onyekpandu-2a7b3a182)

---

