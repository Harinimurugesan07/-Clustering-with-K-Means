# 🚀 K-Means Clustering – Customer Segmentation (task-8)

## 📌 Objective
Perform **unsupervised learning** using **K-Means Clustering** to group customers based on **Annual Income** and **Spending Score**, helping businesses with targeted marketing strategies.

## 📂 Dataset
- **Name:** Mall Customers Dataset  
- **Source:** [📊 Kaggle – Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **Features Used:**  
  - Annual Income (k$)  
  - Spending Score (1-100)  

## 🛠️ Tools & Libraries:

 **Pandas**   - Data loading & manipulation 
 **NumPy**    - Numerical computations 
 **Matplotlib** - Plotting graphs 
 **Seaborn**  - Data visualization 
 **Scikit-learn** -Machine learning algorithms 


## 📊 Project Workflow
1. **Load & Explore Data** – Understand dataset structure.
2. **Data Cleaning** – Handle missing values (if any).
3. **Feature Selection** – Select relevant numerical features.
4. **Elbow Method** – Find optimal number of clusters (**K**).
5. **Apply K-Means** – Cluster data points.
6. **Visualization** – Plot clusters for better understanding.
7. **Evaluation** – Measure clustering quality using **Silhouette Score**.


## 📈 Results
- **Optimal K:** 5  
- **Silhouette Score:** ~0.55  
- **Cluster Groups Identified:**
  1. High Income – High Spending 💸
  2. High Income – Low Spending 🏦
  3. Average Income – Average Spending 📊
  4. Low Income – High Spending 🎯
  5. Low Income – Low Spending 📉
