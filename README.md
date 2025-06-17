# 🛍️ Retail Sales Analysis

An exploratory data analysis project using a real-world retail dataset to uncover business insights, identify trends, and prepare for future forecasting.

---

## 📌 Project Overview

This project explores historical retail sales data to answer key business questions:

- Which products, categories, and regions perform best?
- What are the monthly and seasonal sales trends?
- Can we engineer useful features like `Month`, `Quarter`, etc.?
- How can this data be prepared for future sales forecasting?

---

## 📂 Dataset

- **Source:** [Kaggle - Sales Forecasting Dataset](https://www.kaggle.com)
- **File used:** `sales.csv`
- **Columns include:**
  - `Order_Date`, `Product_Name`, `Category`, `Sub-Category`
  - `Sales`, `Customer_ID`, `Segment`, `Region`, etc.

---

## 📊 Key Analysis Steps

- ✅ Data Cleaning & Column Normalization  
- ✅ Missing Values Handling  
- ✅ Feature Engineering: `Month`, `Quarter`, `Year`, `Month_Name`  
- ✅ Sales by Product, Category, Region, and State  
- ✅ Monthly Sales Trend Analysis  
- ✅ Estimated Profit Calculation (assumed margin)

---

## 📈 Visual Insights

- Bar charts: Top-selling products & categories  
- Line plots: Monthly and seasonal sales trends  
- Heatmaps: Correlation matrix (Sales vs other metrics)

---

## 💡 Sample Insights

- 📦 Certain `Sub-Categories` and `States` generate most of the revenue
- 📅 Sales peak in specific months, indicating seasonality
- 🧠 Adding `Profit` (estimated) gives deeper insight into high-margin products

---

## 🧰 Tools & Libraries

- Python (Jupyter/Colab)
- Pandas, NumPy
- Matplotlib, Seaborn
- Optional: Scikit-learn, Prophet (for forecasting)

---

## 🚀 Next Steps

- 🧠 Build forecasting models using `Linear Regression` or `Prophet`
- 📊 Create a dashboard with `Plotly`, `Dash`, or `Streamlit`
- 📦 Package cleaned data for future ML tasks

---

## 📌 Folder Structure

