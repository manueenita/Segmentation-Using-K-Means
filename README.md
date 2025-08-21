# 🛍️ Customer Purchase Behavior Clustering

## 📌 Overview

This project explores customer purchase behavior using unsupervised learning techniques. The main goal is to perform **clustering analysis** on transactional data to uncover hidden segments or patterns in purchasing habits.

## 📂 Dataset

- Retail dataset with transactional data
- Includes fields like `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, and `Country`
- Special `StockCode` entries (like 'DOT', 'BANK CHARGES', etc.) are cleaned or removed

## 🔍 Exploratory Data Analysis (EDA)

- Analyzed `StockCode` patterns and filtered invalid entries
- Removed rows with null `CustomerID` and negative quantities
- Created RFM (Recency, Frequency, Monetary) features

## 🧠 Clustering Approach

- Used **KMeans clustering** to segment customers
- Elbow Method and Silhouette Score used to determine optimal number of clusters
- Focused on RFM-based segmentation

## 🧾 Key Insights

- Cluster 0: High-frequency and high-value customers
- Cluster 1: Low-frequency, low-spending customers
- Cluster 2: Occasional buyers with medium spend
- Cleaned data leads to better clustering performance

## ⚙️ How to Run

1. Clone this repository
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
