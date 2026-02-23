# 📊 Zepto Sales Data Analysis Project

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

The **Zepto Sales Data Analysis Project** focuses on analyzing real-world sales data from a quick-commerce platform. The goal of this project is to explore, clean, analyze, and visualize large-scale sales datasets using **Python** and data analysis libraries.

This project demonstrates a complete **end-to-end Data Analysis Workflow**, starting from raw datasets to meaningful business insights through visualization.

The dataset contains more than **200,000 sales records** along with product catalog information.

This project helps in understanding:

* Sales performance across different cities
* Customer buying behavior
* Product demand patterns
* Delivery performance
* Category-wise sales contribution
* Time-based sales trends

---

## 🎯 Project Objectives

* Perform real-world data analysis
* Learn data cleaning techniques
* Practice Pandas operations
* Generate business insights
* Create meaningful visualizations

---

## 📂 Dataset Information

This project uses two datasets:

### 1️⃣ zepto_sales.csv

Contains transaction-level sales data.

Columns:

* order_id → Unique order identifier
* order_date → Order date and time
* product_id → Product identifier
* quantity → Units sold
* city → Order location
* delivery_status → Delivery status
* customer_id → Customer identifier
* delivery_time_mins → Delivery time in minutes
* total_amount → Order amount

### 2️⃣ zepto_products.csv

Contains product details.

Columns:

* product_id → Product ID
* product_name → Product Name
* category → Product Category
* base_price → Product Base Price

---

## ⚙️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🧹 Data Cleaning Steps

The following preprocessing steps were performed:

✔ Removed missing values from **city** and **delivery_status**

✔ Filled missing values in **delivery_time_mins** using mean

✔ Removed duplicate records

✔ Converted **order_date** into datetime format

---

## 📊 Data Analysis Performed

The following analysis was performed:

* Minimum order value
* Maximum order value
* Average order value
* Top selling products
* Total sales by city
* Average delivery time by city
* Monthly sales trend
* Daily sales trend
* Sales by product category
* Customer order behavior

---

## 📈 Visualizations

The project includes the following visualizations:

### Basic Visualizations

✔ Top 5 Products by Sales

✔ Total Sales by City

✔ Monthly Sales Trend

✔ Sales by Product Category

✔ Delivery Time Distribution

### Advanced Visualizations

✔ Delivery Status Distribution

✔ Top Cities by Number of Orders

✔ Average Order Value by City

✔ Quantity Distribution

✔ Daily Sales Trend

---

## 📊 Sample Insights

Some key insights from the analysis:

* Certain cities generate the highest revenue
* Few products contribute most of the sales
* Delivery time varies significantly between cities
* Most orders contain small quantities
* Sales show clear trends over time

---

## 🚀 How to Run the Project

### Step 1

Clone the repository

```
git clone https://github.com/viveksahu1408/Zepto-Sales-Data-Analysis-Project.git
```

### Step 2

Install required libraries

```
pip install pandas matplotlib seaborn
```

### Step 3

Run the notebook or python file

```
python zepto_analysis.py
```

---

## 📁 Project Structure

```
Zepto-Sales-Analysis/
│
├── zepto_sales.csv
├── zepto_products.csv
├── zepto_analysis.py
├── README.md
```

---

## 💼 Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Data Visualization
* Exploratory Data Analysis
* Pandas Operations
* Business Insights

---

## 🎓 Learning Outcome

This project provides practical experience with **real-world sales datasets** and helps build strong foundations in **Data Analysis using Python**.

It simulates real business scenarios where data-driven insights help improve business performance.

---

## 👨‍💻 Author

**Vivek Sahu**

Aspiring Data Analyst

---

⭐ If you like this project, give it a star on GitHub!
