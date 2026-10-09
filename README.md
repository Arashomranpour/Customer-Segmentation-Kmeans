<div align="center">

# 🛍️ Customer Segmentation with K-Means

**Group mall customers into meaningful segments using unsupervised learning.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

The notebook analyses the classic **Mall Customers** dataset (`CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`; 200 customers, no missing values):

1. 🔎 Explore the data (info, nulls, distributions) with pandas and seaborn.
2. 📐 Choose the number of clusters - the optimum found is **5**.
3. 🧩 Fit a **K-Means** model and visualise the customer segments.

Useful for marketing ideas such as targeting high-income / high-spending groups differently from budget-conscious ones.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/Customer-Segmentation-Kmeans.git
cd Customer-Segmentation-Kmeans
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Untitled-1.ipynb
```

## 📁 Project Structure

```
.
├── Untitled-1.ipynb     # EDA, K-Means, visualisation
└── Mall_Customers.csv   # Dataset
```

## 🛠️ Tech Stack

`pandas` · `NumPy` · `scikit-learn` · `Seaborn` · `Matplotlib`
