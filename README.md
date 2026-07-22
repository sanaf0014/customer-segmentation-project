# Customer Segmentation Project

A simple machine learning project built in Python to segment customers based on their annual income and spending score using **K-Means Clustering**.

---

## 📌 Project Overview
The goal of this project is to analyze customer behavior data (140 customers) and group them into distinct segments. This helps businesses tailor marketing strategies, improve customer retention, and optimize sales strategies.

---

## 🛠️ Tools & Technologies Used
* **Python** (Google Colab)
* **Pandas** & **NumPy** for data generation and manipulation
* **Scikit-learn** for K-Means Clustering
* **Matplotlib** for visualising customer segments

---

## 📊 How It Works

1. **Data Generation:** Creates synthetic data for 140 customers including `CustomerID`, `Age`, `Income`, and `SpendingScore`.
2. **K-Means Clustering:** Groups customers into 3 distinct clusters based on their financial and spending patterns.
3. **Visualization:** Generates a 2D scatter plot showing how customers are grouped by Income vs. Spending Score.

---

## 🚀 How to Run the Code

1. Open the [`Customer_Segmentation.ipynb`](./Customer_Segmentation.ipynb) file in Google Colab.
2. Run each cell sequentially using `Shift + Enter`.
3. View the generated cluster summary and visualization directly in the notebook output!

---

## 📈 Sample Results
The model groups 140 customers into 3 actionable segments:
* **Cluster 0:** Moderate Spend / Moderate Income
* **Cluster 1:** High Income / High Spending Score
* **Cluster 2:** Low Income / Low Spending Score
