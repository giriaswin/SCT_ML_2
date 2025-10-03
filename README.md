# Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers of a retail store based on their purchase history. The dataset used is **Mall_Customers.csv**, which contains details like Age, Annual Income, and Spending Score.  
The goal is to identify different customer groups to help businesses make data-driven marketing and sales decisions.

# Dataset
The dataset `Mall_Customers.csv` contains the following columns:
- `CustomerID` – Unique ID for each customer
- `Gender` – Male / Female
- `Age` – Age of the customer
- `Annual Income (k$)` – Income in thousands of dollars
- `Spending Score (1-100)` – A score assigned by the store based on customer behavior

# Project Workflow
1. **Load Data** – Read and explore the dataset using Pandas.
2. **Feature Selection** – Select key features for clustering:
   - 2D Clustering → `Annual Income` and `Spending Score`
   - 3D Clustering → `Age`, `Annual Income`, and `Spending Score`
3. **Elbow Method** – Determine the optimal number of clusters (k).
4. **K-Means Clustering** – Apply K-Means algorithm with the chosen `k`.
5. **Visualization** – 
   - 2D Scatter Plot of clusters with centroids
   - 3D Scatter Plot for deeper insights
6. **Save Results** – Store the clustered dataset into CSV files.

# Visualizations
- **2D Plot:** Clustering based on Annual Income & Spending Score.
- **3D Plot:** Clustering based on Age, Annual Income & Spending Score.

# Requirements
Install the required Python libraries before running the script.
