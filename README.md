# AIML-TASK8
# 🧠 K-Means Clustering - Customer Segmentation

This project demonstrates *Unsupervised Learning* using *K-Means Clustering* on the *Mall Customer Segmentation Dataset*.
Objective

- Perform customer segmentation using K-Means.
- Identify patterns in customer spending habits.
- Visualize clusters in 2D using PCA.
📁 Dataset

- Dataset: *Mall Customer Segmentation Data*
- Features:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)
## 🛠 Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
## ✅ Steps Performed
### 1. Load and Explore Data
- Loaded the dataset using pandas.
- Checked data types, null values, and distributions.
### 2. Preprocessing
- Selected relevant features: Annual Income and Spending Score.
- Applied *PCA* to reduce features to 2D for visualization.
### 3. Apply K-Means Clustering
- Applied KMeans from sklearn.cluster.
- Assigned cluster labels to each customer.
### 4. Determine Optimal Clusters
- Used *Elbow Method* to choose the best K (number of clusters).
- Plotted WCSS (Within-Cluster Sum of Squares).
### 5. Visualize Clusters
- Used scatter plot to visualize customer clusters with different colors.
- Marked centroids of each cluster.
### 6. Evaluate Clustering
- Calculated *Silhouette Score* to measure how well clusters are separated.
