# 🛒 SmartCart Customer Segmentation using K-Means Clustering

An end-to-end Machine Learning project that segments customers of an e-commerce platform using **K-Means Clustering**. The project analyzes customer demographics and purchasing behavior to identify distinct customer groups, helping businesses design targeted marketing strategies and improve customer retention.

---

## 📌 Project Overview

SmartCart is a growing e-commerce platform serving customers across multiple countries. Since all customers were previously targeted using the same marketing strategy, this project applies **unsupervised machine learning** to discover hidden customer segments.

The clustering results can be used for:

- 🎯 Personalized marketing campaigns
- 💰 Identifying high-value customers
- 📉 Detecting churn-prone customers
- 🛍️ Product recommendation strategies
- 📈 Improving customer retention

---

## 📊 Dataset

- **Records:** 2240 Customers
- **Features:** 22 Customer Attributes
- Includes:
  - Demographics
  - Income
  - Spending Behaviour
  - Purchase Frequency
  - Web Activity
  - Campaign Responses

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Scaling
- PCA for Dimensionality Reduction
- Optimal Cluster Selection
  - Elbow Method
  - Silhouette Score
- K-Means Clustering
- 2D & 3D Cluster Visualization
- Customer Segment Analysis

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
SmartCartClustering-System/
│
├── smartcart.ipynb              # Main Notebook
├── smartcart_customers.csv      # Dataset
├── README.md
└── requirements.txt
```

---

## 📈 Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Standardization
6. PCA Transformation
7. Find Optimal K
8. Train K-Means Model
9. Assign Customer Clusters
10. Visualize and Interpret Results

---

## 📊 Results

- Optimal number of clusters selected using **Elbow Method** and **Silhouette Score**.
- PCA reduced the dataset for effective visualization.
- Customers were divided into **4 distinct segments** based on purchasing behaviour.

The project includes:

- Cluster Distribution
- Elbow Curve
- Silhouette Analysis
- 3D PCA Cluster Visualization

---

## 💡 Business Impact

This segmentation helps businesses:

- Increase marketing ROI
- Improve customer satisfaction
- Identify loyal customers
- Target promotional campaigns
- Reduce customer churn

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/jiyaydv/SmartCartClustering-System.git
```

Move into the project directory

```bash
cd SmartCartClustering-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

Open

```
smartcart.ipynb
```

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Or install them together:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## 📸 Visualizations

The notebook includes:

- Customer Cluster Distribution
- Elbow Method Graph
- Silhouette Score Analysis
- 3D PCA Cluster Visualization
- Income & Spending Pattern Analysis

---

## 🔮 Future Improvements

- Deploy using Streamlit
- Interactive Dashboard
- Hierarchical Clustering Comparison
- DBSCAN Comparison
- Automated Customer Recommendations
- Real-time Customer Segmentation

---

## 👨‍💻 Author

**Jiya**

GitHub: https://github.com/jiyaydv

---

## ⭐ If you found this project useful, don't forget to Star the repository!
