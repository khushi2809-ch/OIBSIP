# OIBSIP – Customer Segmentation Analysis

## Task 2: Customer Segmentation Analysis

### 📌 Project Overview

This project focuses on segmenting an e-commerce company's customer base based on purchasing behaviour. K-Means clustering is used to identify distinct customer groups that can help businesses develop targeted marketing strategies.

The analysis uses RFM (Recency, Frequency, Monetary) features to understand customer purchasing patterns and create meaningful customer segments.

---

## 🎯 Objective

The main objective of this project is to apply clustering techniques to categorize customers into different segments based on their purchasing behaviour and provide suitable marketing recommendations for each segment.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- K-Means Clustering
- StandardScaler
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The project uses an e-commerce transaction dataset containing customer purchase information.

The dataset was inspected and prepared before applying the clustering algorithm.

---

## 🔍 Data Preparation

The following steps were performed:

- Loaded and inspected the dataset
- Checked the dataset structure
- Handled missing values
- Checked and handled inconsistent data
- Removed unnecessary records where required
- Prepared customer-level transaction data
- Created RFM features

---

## 📊 RFM Analysis

Three important behavioural features were selected for customer segmentation:

### Recency
Measures how recently a customer made a purchase.

### Frequency
Measures how frequently a customer makes purchases.

### Monetary
Measures the total amount spent by a customer.

These three features provide a useful representation of customer purchasing behaviour.

---

## ⚙️ Data Standardization

Before applying K-Means clustering, the RFM features were standardized using `StandardScaler`.

This ensures that features with different numerical scales do not disproportionately influence the clustering algorithm.

---

## 🤖 K-Means Clustering

K-Means clustering was applied to group customers with similar purchasing behaviour.

The **Elbow Method** was used to determine a suitable number of clusters by comparing the number of clusters with the corresponding inertia values.

Based on the analysis, **4 customer clusters** were created.

---

## 📈 Visualizations

The project includes the following visualizations:

- Elbow Method
- Customer Segments – Frequency vs Monetary
- Recency vs Monetary
- Cluster Profile
- Customers per Cluster

These visualizations help understand the characteristics and distribution of each customer segment.

---

## 👥 Customer Segments

The customers were divided into four clusters.

| Cluster | Customer Type | Recommended Marketing Action |
|---|---|---|
| Cluster 0 | Loyal Customers | Loyalty rewards and retention offers |
| Cluster 1 | High-Value Customers | Premium membership and exclusive offers |
| Cluster 2 | New Customers | Welcome coupons and onboarding campaigns |
| Cluster 3 | At-Risk Customers | Re-engagement campaigns and targeted discounts |

---

## 💡 Business Insights

Customer segmentation helps businesses understand that different customers have different purchasing behaviours.

- Loyal customers should be encouraged to continue purchasing through rewards and loyalty programs.
- High-value customers can be targeted with premium services and exclusive offers.
- New customers can be encouraged to make repeat purchases through welcome offers.
- At-risk customers can be targeted through re-engagement campaigns and personalized discounts.

---

## 📁 Project Structure

```text
Task2_Customer_Segmentation/
│
├── KhushiChaudhary_Task2.ipynb
├── Online_Retail.xlsx
