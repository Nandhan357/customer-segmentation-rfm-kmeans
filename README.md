# Customer Segmentation Using RFM Analysis and K-Means Clustering

## Online Retail Customer Segmentation

This project analyzes customer purchasing behavior from an Online Retail transactional dataset using **RFM (Recency, Frequency, and Monetary) analysis** and **K-Means clustering**.

The objective is to identify distinct customer segments based on their purchasing behavior and derive actionable business insights that can support targeted marketing, customer retention, and loyalty strategies.

---

## Project Overview

Customer segmentation is an important technique in retail analytics that allows businesses to group customers with similar purchasing behavior.

In this project, transactional customer data is transformed into customer-level RFM features:

- **Recency** – How recently a customer made a purchase
- **Frequency** – How frequently a customer makes purchases
- **Monetary** – How much a customer spends

These RFM features are then used with the **K-Means unsupervised machine learning algorithm** to identify customer segments.

---

## Objectives

The main objectives of this project are:

- Explore and understand the Online Retail dataset
- Perform data cleaning and preprocessing
- Analyze customer purchasing behavior
- Construct RFM features
- Visualize customer behavior
- Determine an appropriate number of clusters
- Apply K-Means clustering
- Analyze and interpret the resulting customer segments
- Develop business recommendations for each customer segment

---

## Dataset

The project uses the **Online Retail transactional dataset**.

The dataset contains information related to retail transactions, including:

- Invoice number
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

The analysis transforms transaction-level data into customer-level information for segmentation.

---

## Methodology

The project follows the following workflow:

```text
Raw Transaction Data
        ↓
Data Exploration
        ↓
Data Cleaning & Preprocessing
        ↓
RFM Feature Engineering
        ↓
RFM Visualization
        ↓
K-Means Clustering
        ↓
Elbow Method & Silhouette Analysis
        ↓
Customer Segmentation
        ↓
Cluster Profiling
        ↓
Business Recommendations
