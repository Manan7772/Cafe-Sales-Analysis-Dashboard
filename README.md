# ☕ Cafe Sales Analysis Dashboard

## 📌 Project Overview

Cafe Sales Analysis is a Data Analytics project that analyzes cafe order data to understand sales performance, product popularity, and customer purchasing patterns.

The project uses Python for data cleaning, processing, and exploratory data analysis (EDA), along with Power BI to create an interactive dashboard for visualizing important business insights.

## 🚀 Key Features

- **Data Cleaning:** Removes duplicate records and handles missing values.
- **Sales Analysis:** Calculates total sales, orders, and average order value.
- **Category Analysis:** Compares sales across different product categories.
- **Product Analysis:** Identifies the top-selling products.
- **Monthly Sales Trends:** Analyzes sales performance over time.
- **Weekly Sales Analysis:** Compares sales across different days.
- **Power BI Dashboard:** Presents key business insights through interactive visualizations.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Analysis | Pandas |
| Data Visualization | Matplotlib |
| Dashboard Development | Microsoft Power BI |
| Development Environment | Google Colab |
| Dataset Format | CSV |

## 📂 Dataset Information

**Dataset:** orders.csv

- Original Records: 4,108
- Records After Cleaning: 4,021
- Total Columns: 7

**Dataset Columns:**
- order_id
- order_date
- customer_id
- product_category
- product_name
- quantity
- sales

## ⚙️ Project Workflow

1. **Data Input:** Import the cafe sales dataset using Google Colab.
2. **Data Cleaning:** Remove duplicate records and convert date and numerical columns into appropriate formats.
3. **Data Analysis:** Calculate total sales, total orders, quantity sold, and average order sales.
4. **Category Analysis:** Analyze sales performance across different product categories.
5. **Sales Trends:** Identify monthly and weekly sales patterns.
6. **Data Visualization:** Create area charts, pie charts, and column charts using Matplotlib.
7. **Power BI Dashboard:** Build a dashboard to present key sales information and business insights.

## 📊 Key Insights

| Metric | Result |
|---|---:|
| Total Sales | 1,962,555 |
| Total Orders | 1,699 |
| Total Quantity Sold | 10,057 |
| Average Order Sales | 488.08 |
| Average Quantity per Order | 2.5 |

### Sales by Product Category

- Main Course: 962,629.5
- Starters: 487,071
- Beverages: 312,062.5
- Desserts: 200,792

### Top 5 Products by Sales

1. Butter Chicken
2. Margherita Pizza
3. Veg Biryani
4. Chicken Wings
5. Paneer Tikka

### Sales by Day

Saturday recorded the highest sales, followed by Sunday and Friday.

## 📈 Power BI Dashboard

The Power BI dashboard includes:

- Total Sales
- Total Orders
- Average Order Value
- Units Sold
- Monthly Sales Trend (Area Chart)
- Sales Share by Product Category (Pie Chart)
- Sales by Day of the Week (Column Chart)

The dashboard uses a coffee-brown and cream color theme to provide a clean and attractive presentation.

## ⚙️ How to Run

**1. Clone the repository**

```bash
git clone <your-repository-url>
```

**2. Open Google Colab**

Upload the project notebook and the `orders.csv` dataset.

**3. Install the required library**

```python
!pip install pandas matplotlib
```

**4. Execute the notebook**

Run the notebook cells sequentially to perform data cleaning, analysis, and visualization.

**5. Open Power BI**

Import `orders.csv` into Microsoft Power BI and create the dashboard using the provided analysis and visualizations.

## 🎯 Project Objective

The main objective of this project is to analyze cafe sales data, identify popular products, understand customer purchasing patterns, and visualize business performance to support better business decisions.

## 👨‍💻 Project Information

**Project Name:** Cafe Sales Analysis Dashboard

**Domain:** Data Analytics

**Tools:** Python, Pandas, Matplotlib, Power BI

**Platform:** Google Colab

---

*Developed for educational and learning purposes.*
