# 🛍️ Mall Customer Segmentation using K-Means Clustering

## 📖 Project Overview

This project implements the **K-Means Clustering** algorithm to segment mall customers based on their **Annual Income** and **Spending Score**. Customer segmentation helps businesses identify different customer groups and develop targeted marketing strategies.

---

## 🎯 Objective

To group customers into different clusters based on their purchasing behavior using the K-Means Clustering algorithm.

---

## 📂 Dataset

**Dataset:** Mall_Customers.csv

### Features

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

For clustering, the following features were used:

- Annual Income (k$)
- Spending Score (1–100)

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check for missing values
5. Select relevant features
6. Apply the Elbow Method
7. Train the K-Means model
8. Predict customer clusters
9. Visualize customer segments
10. Save the clustered dataset

---

## 📈 Results

### Elbow Method

![Elbow Method](elbow_method.png)

### Customer Segmentation

![Customer Segmentation](clusters.png)

---

## 📁 Project Structure

```
mall-customer-segmentation-kmeans/
│
├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
├── Clustered_Customers.csv
├── README.md
├── requirements.txt
├── elbow_method.png
└── clusters.png
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/mall-customer-segmentation-kmeans.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```
Customer_Segmentation.ipynb
```

4. Run all cells to reproduce the results.

---

## 📌 Output

The K-Means algorithm identified **5 customer segments** based on Annual Income and Spending Score.

These customer segments can be used for:

- Customer profiling
- Personalized marketing
- Business strategy
- Targeted promotions

---
---

⭐ If you found this project useful, consider giving this repository a star!
