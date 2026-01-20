# 📊 Pro-Analytics: Customer Retention & Churn Intelligence

**Task 2 | Data Science & Analytics Internship** **Project ID:** `FUTURE_DS_02`

## 📝 Project Overview

This project focuses on identifying high-risk customer segments and retention drivers for a subscription-based telecommunications provider. Using a modular Python pipeline, I engineered a **Churn Propensity Scoring** model to assist stakeholders in proactive customer success management.


## 🚀 Key Features

* **Modular Pipeline:** Clean, functional code separated into processing, scoring, and visualization engines.
* **Risk Propensity Model:** A custom-weighted algorithm that assigns a risk score (0–100) based on contract stability, service type, and tenure.
* **GridSpec Dashboard:** A high-resolution, multi-panel visual report that prevents overlapping and ensures professional readability.
* **Feature Engineering:** Includes custom metrics like `Service_Count` (stickiness) and `Charge_Velocity`.


## 📊 Analysis Highlights

### 1. The "Stickiness" Effect

Analysis shows a direct inverse correlation between the number of subscribed services and churn probability. Customers with **4 or more add-on services** exhibit a churn rate of less than 5%, proving that service bundling is a primary retention lever.

### 2. High-Risk Segments

Customers on **Month-to-month contracts** are **4.5x more likely** to churn than those on long-term contracts. High monthly charges coupled with a lack of technical support services represent the "Danger Zone" for the customer base.

### 3. Pricing Sensitivity

Using Kernel Density Estimation (KDE), the data reveals that churners are significantly more sensitive to price points above the median, specifically within the Fiber Optic segment.


## 🛠️ Technical Stack

* **Python 3.10+**
* **Pandas & NumPy:** Data cleaning and feature engineering.
* **Matplotlib (GridSpec):** Advanced dashboard layout.
* **Seaborn:** Statistical data visualization.


## 📂 Repository Structure

```text
FUTURE_DS_01/
└── Task2_Retention_Analysis/
    ├── telco_churn.csv            # Source Dataset
    ├── Advanced_Retention_Code.py  # Main Analysis Engine
    ├── Churn_Dashboard_v2.png      # High-Res Dashboard Output
    └── README.md                   # Project Documentation

```

## 💡 Executive Recommendations

1. **Mandatory Trials:** Automatically enroll Fiber Optic users in 30-day "Online Security" trials to increase product stickiness.
2. **Contract Incentives:** Launch a targeted campaign offering a 3-month discount to month-to-month users who migrate to a 1-year stability contract.
3. **Automated Billing:** Prioritize the migration of manual-pay users to automated systems to reduce "passive" churn.

## 👤 Intern Information

* **Name:** Krayolin Kisten
* **CIN ID:** FIT/JAN26/DS12090
* **Company:** Future Interns
* **Submission Date:** February 2026
