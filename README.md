# Customer Segmentation Using K-Means Clustering

## 💡 Project Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to perform **customer segmentation** based on their **Annual Income** and **Spending Score**. The objective is to group customers into meaningful clusters to help businesses tailor marketing strategies and improve customer experience.

---

## 📁 Dataset Description

The dataset used (`Mall_Customers.csv`) includes the following features:

| Column                  | Description                                               |
|-------------------------|-----------------------------------------------------------|
| `CustomerID`            | Unique identifier for each customer                       |
| `Gender`                | Gender of the customer (Male/Female)                      |
| `Age`                   | Age of the customer                                       |
| `Annual Income (k$)`    | Annual income of the customer in thousands of dollars     |
| `Spending Score (1-100)`| Score based on customer’s behavior and mall spending style|

📌 **Source**: Publicly available dataset from Kaggle

---

## 🛠️ Dependencies

Make sure the following Python libraries are installed:
```bash
pip install pandas matplotlib scikit-learn
