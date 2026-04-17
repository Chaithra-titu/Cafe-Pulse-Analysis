# ☕ Cafe Sales Analysis (SQL + Power BI)

## 📊 Project Overview

This project analyzes cafe transaction data to uncover insights related to product performance, sales trends, customer behavior, and revenue distribution.

The analysis was conducted using:

* **Excel** → Data cleaning
* **SQL** → Data analysis
* **Power BI** → Data visualization

---

## 📁 Dataset Description

The dataset contains ~8,000 transaction records with the following fields:

* Transaction ID
* Item
* Quantity
* Price per Unit
* Total Spent
* Payment Mode
* Location
* Transaction Date

---

## 🎯 Objectives

* Identify top-performing and underperforming items
* Analyze sales trends over time
* Understand customer payment behavior
* Evaluate location-based performance

---

## 🔍 Key Insights

### 🥗 Product Performance

* **Salad is the top-performing item**, generating the highest revenue (~90K) and highest quantity sold (~3K units), making it the primary driver of sales.

* **Tea is the lowest-performing item**, with the least revenue (~8K), despite moderate quantity sold (~2.8K units), indicating lower value per transaction.

* **Juice and Smoothie generate similar revenue**, but Juice has higher quantity sold, suggesting:

  * Juice is sold in higher volume at a lower price
  * Smoothies generate higher value per unit

---

### 📅 Time-Based Trends

* **January is the peak sales month** for multiple items, indicating strong demand at the start of the year.

* **Sales for Salad drop significantly in November and December**, showing possible seasonality.

* **Tea experiences a sharp decline in February**, indicating short-term demand fluctuation.

---

### 💳 Payment Behavior

* **“Other” payment mode is the most used**, which may indicate unclassified or mixed payment types.

* Among standard payment methods:

  * **Credit Card is the most used (~17K transactions)**
  * Followed by Digital Wallet and Cash

---

### 📍 Location Insights

* **“Other” locations generate the highest revenue**, suggesting possible data grouping or undefined categories.

* **In-store is the second highest (~22K revenue)**, showing strong physical store performance.

---

## 📊 Dashboard Features (Power BI)

* KPI cards for revenue, transactions, and average order value
* Item-wise revenue and quantity analysis
* Monthly sales trends
* Payment mode distribution
* Location-based performance
