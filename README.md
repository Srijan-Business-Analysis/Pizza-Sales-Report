
# 🍕 Pizza Sales Dashboard

🔗 **View Dashboard**: [Click here to view on Tableau Public](https://public.tableau.com/app/profile/srijan.mishra/viz/PizzaSalesReport_17481846134950/BestWorstSellers?publish=yes)

This project presents an interactive Tableau dashboard that analyzes key performance indicators (KPIs), sales patterns, and product performance based on a pizza sales dataset.

## 📂 Dataset

The pizza sales dataset is used for all analysis and visualizations.

**Download the full dataset:** [pizza_sales_excel_file.csv](./pizza_sales_excel_file.xlsx)


---

## 📄 SQL Queries Document

All SQL queries used for calculating KPIs and generating charts are available here:

👉 [PIZZA SALES SQL QUERIES](./PIZZA_SALES_SQL_QUERIES.docx)

---

## 📊 KPIs Calculated

| KPI                       | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| **Total Revenue**         | Sum of all `total_price` values                                             |
| **Average Order Value**   | Total Revenue ÷ Total Orders                                                |
| **Total Pizzas Sold**     | Sum of `quantity`                                                           |
| **Total Orders**          | Count of distinct `order_id`s                                               |
| **Average Pizzas/Order**  | Total Pizzas Sold ÷ Total Orders                                            |

---

## 📈 Visualizations in Tableau Dashboard

### 1. ⏰ **Hourly Trend for Total Pizzas Sold**
- **Chart Type**: Stacked Bar Chart
- **Purpose**: Identify peak ordering times

### 2. 📅 **Weekly Trend for Total Orders**
- **Chart Type**: Line Chart
- **Purpose**: Understand sales performance by week

### 3. 🍕 **% Sales by Pizza Category**
- **Chart Type**: Pie Chart
- **Purpose**: Visualize revenue contribution by category

### 4. 📏 **% Sales by Pizza Size**
- **Chart Type**: Pie Chart
- **Purpose**: Understand customer preference by pizza size

### 5. 🧮 **Total Pizzas Sold by Category**
- **Chart Type**: Funnel Chart
- **Purpose**: Compare quantity sold across pizza categories

### 6. ⭐ **Top 5 Best Sellers**
- **Chart Type**: Bar Charts (3 metrics)
- **Metrics**: Revenue, Quantity, Total Orders

### 7. 🔻 **Bottom 5 Worst Sellers**
- **Chart Type**: Bar Charts (3 metrics)
- **Metrics**: Revenue, Quantity, Total Orders

---

## 📌 Insights Derived

### ⏰ **Hourly Trends**
- Peak order times are between **12:00 PM and 1:00 PM**, and in the **evening from 4:00 PM to 7:00 PM**, indicating strong demand during lunch and early dinner hours.

### 📅 **Weekly Trends**
- There are **significant variations** in weekly orders throughout the year.
- The **highest spike** occurs in the **48th week of the year (December)**, likely driven by holiday season demand.

### 🍕 **Pizza Category Performance**
- The **Classic Category** dominates across all metrics:
  - **Maximum Revenue**
  - **Highest Number of Orders**
  - **Total Pizzas Sold**

### 📏 **Pizza Size Performance**
- **Large-sized pizzas** are the most preferred by customers, contributing the **highest to total revenue**.

---

### 🏆 **Top Performers (Best Sellers)**

| Metric         | Pizza Name               |
|----------------|--------------------------|
| **Revenue**    | Thai Chicken Pizza       |
| **Quantity**   | Classic Deluxe Pizza     |
| **Total Orders**| Classic Deluxe Pizza     |

---

### 📉 **Low Performers (Worst Sellers)**

| Metric         | Pizza Name               |
|----------------|--------------------------|
| **Revenue**    | Brie Carre Pizza         |
| **Quantity**   | Brie Carre Pizza         |
| **Total Orders**| Brie Carre Pizza         |

---

## 💻 Tools Used

- **SQL**: For data cleaning, transformation, and metric calculations
- **Tableau**: For interactive visualizations and dashboard design
- **Excel**: For initial data review

## 📁 File Structure

```
├── pizza_sales_excel_file.csv
├── pizza_sales_sql_queries.sql
├── Tableau Dashboard (Published/Packaged)
└── README.md
```

## 🙌 Acknowledgements

Special thanks to the open pizza dataset community for making this analysis possible.

---

Feel free to explore the dashboard and gain insights into what makes a pizza business successful! 🍕📈
