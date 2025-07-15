# iFood Marketing Campaign Optimization: From Loss to Profit

## Overview

This project tackles a real-world data science problem based on a case study from **iFood**, the leading food delivery app in Brazil. The goal is to analyze data from a past marketing campaign to make the next one profitable. This end-to-end project involves data cleaning, exploratory data analysis, customer segmentation, and the development of a predictive model to "cherry-pick" customers, thereby maximizing campaign profit.

---

## The Business Problem

Despite its market leadership, iFood's profit growth is stalling. To improve performance, the marketing department ran a pilot campaign that resulted in a **significant financial loss of -3,046 MU** with a low 15% success rate. This proved that an untargeted, mass-market approach is both inefficient and unsustainable. The key challenge is to use the data from this failed campaign to develop a highly profitable, data-driven marketing strategy.

---

## Methodology & Key Findings

Our approach was structured into three analytical phases:

### 1. Data Exploration: Profiling the "Ideal Responder"
We first analyzed the characteristics of customers who responded to the previous offer.
- **Key Insight:** Responders are not random. They are typically **high-spending, highly educated, middle-aged individuals with fewer teenagers at home**. This initial analysis provided a clear picture of our target demographic.

### 2. Customer Segmentation: The RFM Approach
We used **RFM (Recency, Frequency, Monetary) analysis** and **K-Means Clustering** to segment customers based on their purchasing behavior. This revealed three distinct groups:
- **Best Customers (Champions):** High-value, recent, and frequent buyers with an extremely high **28% response rate**. These are our prime targets.
- **At-Risk High Spenders:** High-value customers who haven't purchased in a while. They have a decent response rate but need re-engagement.
- **Low-Value Customers:** Infrequent, low-spending customers with a very low response rate, making them unprofitable to target.

### 3. Predictive Modeling: Maximizing Profit
The core of the project was to build a classification model to predict which customers would accept the campaign offer.
- **Model:** A **Logistic Regression** model was trained on detailed customer features (demographics, spending habits, etc.).
- **Goal:** The model's primary goal was not just accuracy, but to **maximize campaign profit** by identifying likely responders while avoiding the cost of contacting non-responders.

---

## The Financial Outcome: A Data-Driven Turnaround

The predictive model was a resounding success. By applying the model to the customer base, we can make strategic, data-driven decisions about who to contact.

| Metric | Untargeted Campaign (Actual) | Targeted Campaign (Projected with Model) |
| :--- | :--- | :--- |
| **Total Profit** | **-3,046 MU** | **+589 MU** |

The model successfully turns the campaign's significant loss into a healthy profit, creating a **total value swing of over 3,600 MU** and proving the immense ROI of a data-driven marketing strategy.

---

## Skills Demonstrated

* **Exploratory Data Analysis (EDA)**
* **Customer Segmentation (RFM, K-Means Clustering)**
* **Feature Engineering**
* **Predictive Modeling (Logistic Regression)**
* **Model Evaluation (Confusion Matrix, Classification Report)**
* **Business Impact & ROI Analysis**
