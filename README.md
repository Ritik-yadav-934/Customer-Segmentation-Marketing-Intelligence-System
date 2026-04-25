# 🧠 Customer Segmentation using RFM & Clustering

## 📌 Project Overview

This project focuses on **Customer Segmentation** using **unsupervised learning techniques**.
The goal is to group customers based on their purchasing behavior to enable **targeted marketing strategies and business decision-making**.

---

## 🎯 Objectives

* Identify **high-value (VIP) customers**
* Detect **churned/inactive customers**
* Segment customers based on behavior
* Provide **business-driven insights**

---

## 📂 Dataset

* Online Retail Dataset
* ~397K transactions
* ~4.3K unique customers

### Features:

* InvoiceNo
* StockCode
* Description
* Quantity
* InvoiceDate
* UnitPrice
* CustomerID
* Country

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning

* Removed missing CustomerID
* Removed negative/invalid transactions
* Converted data types

---

### 2️⃣ Exploratory Data Analysis (EDA)

* Country-wise distribution (UK dominant)
* Revenue distribution (highly skewed)
* Monthly sales trend (seasonality observed)

---

### 3️⃣ Feature Engineering (RFM Analysis)

* **Recency** → Days since last purchase
* **Frequency** → Number of purchases
* **Monetary** → Total spending

---

### 4️⃣ Data Preprocessing

* Log transformation (handled skewness)
* Standard scaling

---

### 5️⃣ Clustering Models

#### 🔹 K-Means Clustering

* Optimal clusters found using Elbow Method
* Silhouette Score: **0.30 (moderate)**

#### 🔹 DBSCAN (Optional)

* Used for anomaly detection
* Identified outliers and unusual customers

---

## 📊 Customer Segments

| Segment              | Description                 |
| -------------------- | --------------------------- |
| 💰 VIP Customers     | High value, frequent buyers |
| 🔁 Loyal Customers   | Regular and consistent      |
| 📉 Regular Customers | Average behavior            |
| 🚨 Churned Customers | Inactive, low engagement    |

---

## 💼 Business Insights

* A small group of customers contributes most revenue (**Pareto Principle**)
* Customer behavior is highly skewed
* Sales show strong seasonality (peak in November)
* UK dominates transactions (geographical bias)

---

## 🎯 Business Recommendations

* Focus on VIP customers with loyalty programs
* Re-engage churned customers with discounts
* Upsell regular customers
* Expand into international markets
* Optimize marketing during peak seasons

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📈 Results

* Successfully segmented customers into 4 meaningful groups
* Improved clustering using log transformation
* Generated actionable business insights

---

## 🚀 Future Improvements

* Deploy using Streamlit
* Add real-time prediction API
* Use advanced clustering (Hierarchical, GMM)
* Integrate recommendation system

---

## 👨‍💻 Author

Ritik Yadav
Aspiring Data Scientist

---
