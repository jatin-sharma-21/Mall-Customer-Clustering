# 🛍️ Customer Segmentation using K-Means Clustering

A Machine Learning project that segments mall customers into distinct groups using the **K-Means Clustering** algorithm. The project applies exploratory data analysis (EDA), feature scaling, the Elbow Method, Silhouette Score evaluation, and customer segmentation to help businesses understand customer purchasing behavior.

---

## 📌 Project Overview

Customer segmentation enables businesses to identify groups of customers with similar characteristics and purchasing patterns. These insights help create targeted marketing campaigns, improve customer retention, and maximize revenue.

In this project, customers are segmented based on their **Annual Income** and **Spending Score** using the K-Means clustering algorithm.

---

## 🎯 Business Objective

Develop an unsupervised machine learning model to identify meaningful customer segments that can support personalized marketing strategies and business decision-making.

---

## 📂 Dataset

The project uses the **Mall Customers Dataset**, which contains demographic and spending information for mall customers.

### Features

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

### Features Used for Clustering

- Annual Income
- Spending Score

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

- Data inspection
- Missing value analysis
- Duplicate record checking
- Descriptive statistics
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Correlation Heatmap
- Distribution and Box Plots
- Pair Plot Analysis

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Column renaming for readability
- Missing value verification
- Duplicate value detection
- Feature selection
- Standardization using **StandardScaler**

---

## 🤖 Machine Learning Model

### Algorithm Used

- K-Means Clustering

### Model Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Selection
4. Feature Scaling
5. Optimal Cluster Selection using the Elbow Method
6. Cluster Validation using Silhouette Score
7. Customer Segmentation
8. Cluster Visualization
9. New Customer Cluster Prediction

---

## 📈 Model Evaluation

The clustering model is evaluated using:

- **Elbow Method (WCSS)** to determine the optimal number of clusters.
- **Silhouette Score** to measure cluster quality and separation.

The analysis identified **5 optimal customer segments**, providing a balance between compactness and separation.

---

## 👥 Customer Segments

The model identifies five distinct customer groups:

| Cluster | Customer Type | Description |
|----------|---------------|-------------|
| 0 | Medium Customers | Medium income with medium spending |
| 1 | Premium Customers | High income with high spending |
| 2 | Young Customers | Low income with high spending |
| 3 | Careful Customers | High income with low spending |
| 4 | Budget Customers | Low income with low spending |

---

## 📊 Visualizations

The project includes several visualizations to interpret customer behavior:

- Distribution Plots
- Box Plots
- Pair Plot
- Correlation Heatmap
- Elbow Curve
- Customer Cluster Scatter Plot
- Cluster-wise Income Distribution
- Gender Distribution Across Clusters

---

## 📁 Project Structure

```
Customer-Segmentation/
│
├── customers_clustering.py
├── Mall_Customers.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Customer-Segmentation.git
```

Navigate to the project directory:

```bash
cd Customer-Segmentation
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the project:

```bash
python customers_clustering.py
```

---

## 📌 Project Highlights

- Performed comprehensive exploratory data analysis.
- Applied feature scaling using **StandardScaler**.
- Identified the optimal number of clusters using the **Elbow Method**.
- Evaluated clustering performance with the **Silhouette Score**.
- Segmented customers into five meaningful groups.
- Predicted the segment for new customer profiles.

---

## 🚀 Future Improvements

- Compare with Hierarchical Clustering and DBSCAN.
- Include additional customer features such as Age and Gender in clustering.
- Automate optimal cluster selection.
- Build an interactive customer segmentation dashboard using Streamlit.
- Deploy the model as a web application for real-time customer classification.


## 📜 License

This project is intended for educational and learning purposes.
