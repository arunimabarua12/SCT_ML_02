# SCT_ML_02
# 🎯 Customer Segmentation using K-Means Clustering

This project applies K-Means clustering to segment customers from a mall dataset based on features like annual income, spending score, age, and gender. It includes multiple clustering approaches and visualizations to understand customer behavior for targeted marketing.

## 📁 Dataset

- **Source:** [Kaggle Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **File Used:** `Mall_Customers.csv`
- **Attributes:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## 🚀 Features & Highlights

- Label encoding for categorical data (`Gender`)
- Standardization using `StandardScaler`
- Multiple clustering strategies:
  - Annual Income vs Spending Score
  - Age vs Spending Score
  - Gender vs Spending Score
  - Multi-dimensional (Income, Age, Gender, Spending Score) via PCA
- Evaluation:
  - Elbow Method (WCSS)
  - Silhouette Score
- PCA-based 2D visualization for multi-dimensional clustering
- Centroid extraction and visualization
- Output CSV with cluster labels
- All plots saved to a dedicated output folder (`kmeans_plots/`)

## 🛠️ Libraries Used

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
