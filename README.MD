# 📊 E-Commerce Customer Segmentation (RFM Analysis & K-Means)

## 🚀 Project Overview

This project focuses on **customer segmentation** using real-world e-commerce transaction data. By applying **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering**, customers are grouped into meaningful segments such as **High Value, Regular, and At-Risk**, enabling targeted marketing and data-driven decision-making.

---

## 🎯 Objective

* Identify high-value customers contributing maximum revenue
* Detect low-engagement customers for retention strategies
* Provide actionable business insights through data visualization

---

## 🛠️ Tools & Technologies

* **Python**: Pandas, NumPy, Scikit-learn
* **Data Visualization**: Matplotlib
* **BI Tool**: Power BI
* **Techniques**: RFM Analysis, K-Means Clustering, Data Cleaning, Feature Engineering

---

## 📂 Repository Structure

```
Ecommerce_Customer_Segmentation/
│
├── data/
│   ├── raw_data.csv
│   └── rfm_output.csv
│
├── notebooks/
│   └── segmentation_analysis.ipynb
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

## ⚙️ Project Workflow

### 🔹 1. Data Cleaning & Preprocessing

* Removed missing values and invalid records
* Handled duplicates and formatted data
* Created **TotalPrice = Quantity × UnitPrice**

---

### 🔹 2. Feature Engineering (RFM)

* **Recency** → Days since last purchase

* **Frequency** → Number of transactions

* **Monetary** → Total spending

* Aggregated data at **CustomerID level (4338 customers)**

---

### 🔹 3. Data Scaling

* Applied **StandardScaler** to normalize features before clustering

---

### 🔹 4. Customer Segmentation

* Used **Elbow Method** to determine optimal clusters (**k = 3**)
* Applied **K-Means Clustering**

---

### 🔹 5. Customer Segments Identified

| Segment       | Description                                     |
| ------------- | ----------------------------------------------- |
| 🟢 High Value | Frequent buyers, high spending, recent activity |
| 🟡 Regular    | Moderate activity and spending                  |
| 🔴 Low Value  | Inactive, low frequency, low spending           |

---

## 📊 Key Insights

* A small percentage of customers contributes a **major share of revenue**
* Majority of customers are **low-frequency buyers**
* Significant segment identified as **at-risk**, requiring retention strategies

---

## 📈 Power BI Dashboard

### 🔹 Features:

* KPI Cards: Total Customers, Revenue, Avg Spend
* Customer Segment Distribution
* Revenue Contribution by Segment
* Scatter Plot: Recency vs Monetary (Customer Behavior)
* Interactive Filters (Slicers)

## Dashboard Preview
https://github.com/Aakriti-Singh01/Ecommerce-Customer-Segmentation/blob/main/images/image.png



---

## 💡 Business Impact

* Enables **targeted marketing campaigns**
* Helps improve **customer retention**
* Supports **data-driven decision making**

---

## 📦 Installation & Setup

1. Clone the repository:

```
git clone https://github.com/YOUR_USERNAME/Ecommerce-Customer-Segmentation.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run Jupyter Notebook:

```
jupyter notebook
```

---

## 🧠 Key Learnings

* Data cleaning and preprocessing of large datasets
* Feature engineering using RFM methodology
* Clustering using K-Means
* Data visualization and storytelling using Power BI

---

## 👤 Author

**Aakriti Singh**
Data Analyst | Python | SQL | Power BI | Excel

---

## ⭐ If you found this project useful, consider giving it a star!
