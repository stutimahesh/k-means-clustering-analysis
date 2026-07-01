# 📊 K-Means Clustering on Breast Cancer Dataset

This project demonstrates **K-Means Clustering**, an unsupervised machine learning algorithm, on the Breast Cancer Wisconsin Dataset. The workflow includes data preprocessing, feature scaling, dimensionality reduction using PCA, cluster optimization with the Elbow Method, evaluation using the Silhouette Score, and visualization of clustered data.

---

# 📌 Project Overview

The objective of this project is to group similar breast cancer samples into clusters without using the diagnosis labels during clustering.

The project covers:

- Data preprocessing
- Feature scaling
- Principal Component Analysis (PCA)
- Elbow Method for choosing the optimal number of clusters
- K-Means clustering
- Silhouette Score evaluation
- Cluster visualization with centroids

---

# 📂 Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

Dataset Features:

- 569 samples
- 30 numerical features
- Diagnosis column
  - M → Malignant
  - B → Benign

Although the diagnosis column exists, it is **not used for clustering**. It is only converted to numeric for reference.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 🤖 Machine Learning Algorithm

**K-Means Clustering**

Type:

- Unsupervised Learning

---

# 📈 Workflow

1. Load the dataset
2. Remove unnecessary columns
3. Encode diagnosis labels
4. Handle missing values
5. Standardize features
6. Reduce dimensions using PCA
7. Determine the optimal number of clusters using the Elbow Method
8. Train the K-Means model
9. Evaluate clustering using the Silhouette Score
10. Visualize clusters and centroids

---

# 📊 Evaluation Metrics

The project uses:

- Elbow Method (WCSS)
- Silhouette Score
- PCA Explained Variance

---

# 📉 Visualizations

The project generates:

- Elbow Method Plot
- PCA Scatter Plot
- Cluster Visualization
- Cluster Centroids

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/stutimahesh/k-means-clustering-analysis.git
```

Move into the project

```bash
cd k-means-clustering-analysis

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python kmeans.py
```

---


# 🎯 Learning Outcomes

- Unsupervised Learning
- K-Means Clustering
- Data Preprocessing
- Feature Scaling
- Principal Component Analysis (PCA)
- Elbow Method
- Silhouette Score
- Cluster Visualization
