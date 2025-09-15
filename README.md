# Unsupervised-ML Project

---

## 📌 Project Overview

This repository demonstrates core unsupervised learning techniques, including clustering and dimensionality reduction. Key tasks include:

- K-means Clustering  
- Hierarchical Clustering  
- DBSCAN  
- Principal Component Analysis (PCA)  
- Anomaly Detection  

All experiments are performed in Jupyter Notebooks, illustrating how to preprocess data, apply algorithms, visualize results, and interpret clusters or anomalies.

---

## 📂 Project Structure
├── DBSCAN.ipynb # Notebook for DBSCAN clustering

├── Kmeans clustering.ipynb # Notebook for K-Means algorithm

├── PCA.ipynb # Notebook for dimensionality reduction via PCA

├── Anamoly Detection in ML.ipynb# Notebook for anomaly detection

└── hierarichal clustering.ipynb# Notebook for hierarchical clustering

---

## ⚙️ Getting Started

### 1️⃣ Prerequisites

- Python 3.x  
- Jupyter Notebook or JupyterLab  
- Libraries such as `scikit-learn`, `pandas`, `numpy`, `matplotlib` / `seaborn`  

### 2️⃣ Installation

# Clone the repository
git clone https://github.com/hariom845/Unsupervised-ML.git
cd Unsupervised-ML

# (Optional) Create & activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install scikit-learn pandas numpy matplotlib seaborn

# 🔧 Usage
- Open the notebooks in Jupyter to follow the workflow step by step.
- You can run the cells in each notebook:
  - Kmeans clustering to explore cluster assignments
  - Hierarchical clustering to see tree-based clustering
  - DBSCAN for density-based clustering
  - PCA for reducing dimensions and visualizing data
  - Anomaly Detection to find outliers

# 🔍 What You’ll Learn
How different clustering algorithms behave on sample or synthetic datasets
- Use of PCA to reduce features and visualize high-dimensional data
- Identifying anomalies using unsupervised methods
- How to choose or tune algorithm hyperparameters (e.g. number of clusters, epsilon for DBSCAN)

# 🔮 Future Improvements
- Add more datasets to test robustness (real-world vs synthetic)
- Compare clustering performance using metrics like silhouette score, Davies–Bouldin index, etc
- Build a small interface or script to apply clustering as a component in a larger pipeline
- Add visualization dashboards (e.g., Plotly, Bokeh) for more interactive plots



