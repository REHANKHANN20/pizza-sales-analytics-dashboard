# 🍕 Pizza Sales Analytics Dashboard

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Advanced-purple?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-blue?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data%20Model-Star%20Schema-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

# 📊 Dashboard Preview

> *(Replace this image after uploading your dashboard screenshot.)*

![Dashboard Preview](Images/Dashboard%20Preview.png)

---

# 📖 Project Overview

This project presents an interactive **Pizza Sales Analytics Dashboard** developed in **Microsoft Power BI** to analyze sales performance and generate meaningful business insights.

The dashboard transforms raw transactional data into interactive visual reports, enabling stakeholders to monitor KPIs, identify revenue trends, understand customer ordering behavior, and make informed business decisions.

In addition to traditional dashboards, this project includes a **dynamic Business Insights & Recommendations page**, where insights and recommendations automatically update based on slicer selections.

---

# 🎯 Business Objective

The objective of this project is to help management answer key business questions such as:

- Which pizza category generates the highest revenue?
- Which pizza sells the most?
- What is the average order value?
- Which weekday receives the highest number of orders?
- Which hour has peak customer traffic?
- Which pizza size contributes the most revenue?
- What actions can increase future sales?

---

# 🗂 Dataset Information

The project uses four relational tables.

| Table | Description |
|--------|-------------|
| Orders | Customer order information |
| Order Details | Ordered pizza items |
| Pizzas | Pizza size and price |
| Pizza Types | Pizza name, category and ingredients |

### Dataset Summary

- 21,000+ Orders
- 50,000+ Pizza Sold
- 4 Relational Tables
- Star Schema Data Model

---

# 🏗 Data Model

The project follows a **Star Schema** for optimized reporting and faster DAX calculations.

### Relationship Diagram

![Data Model](Images/Data%20Model.png)

---

# 🧹 Data Preparation

Data preparation was performed using **Power Query**.

### Cleaning Steps

- Removed unnecessary columns
- Checked missing values
- Corrected data types
- Created Date Table
- Generated Month and Weekday columns
- Built relationships
- Optimized model

---

# 🧮 DAX Measures

Several advanced DAX measures were developed.

### KPI Measures

- Total Revenue
- Total Orders
- Total Quantity Sold
- Average Order Value
- Average Pizza per Order

### Business Measures

- Revenue %
- Revenue Rank
- Top Selling Pizza
- Top Revenue Pizza
- Best Performing Category
- Peak Ordering Hour
- Best Weekday

### Dynamic Measures

- Executive Summary
- Dynamic Insights
- Dynamic Recommendations
- Dynamic Page Titles
- Last Refresh Date

---

# 📈 Dashboard Features

## Executive Dashboard

✔ KPI Cards

✔ Monthly Revenue Trend

✔ Revenue by Category

✔ Revenue by Pizza Size

✔ Peak Ordering Hours

✔ Orders by Weekday

✔ Top Selling Pizzas

✔ Interactive Filters

---

## Business Insights Page

Dynamic Executive Summary

Dynamic Business Insights

Dynamic Business Recommendations

Automatic Text Generation

Interactive Slicer Support

---

# 💡 Key Business Insights

The dashboard automatically generates business insights such as:

- Revenue generated during the selected period
- Highest revenue category
- Best-selling pizza
- Peak ordering hour
- Best performing weekday

All insights dynamically update based on user selections.

---

# 🚀 Business Recommendations

Based on dashboard analysis, Power BI automatically recommends actions such as:

- Increase inventory for top-performing pizzas
- Promote low-performing pizza sizes
- Schedule additional staff during peak hours
- Feature best-selling pizzas in marketing campaigns

These recommendations are fully dynamic and respond to slicer selections.

---

# 📷 Dashboard Screenshots

## Sales Dashboard

![Sales Dashboard](Images/Dashboard.png)

---

## Business Insights

![Business Insights](Images/Business%20Insights.png)

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Star Schema
- Business Intelligence
- Microsoft Excel

---

# 🧠 Skills Demonstrated

- Data Cleaning
- Data Transformation
- ETL
- Data Modeling
- Star Schema Design
- DAX Programming
- KPI Development
- Dashboard Design
- Interactive Reporting
- Business Intelligence
- Business Storytelling
- Analytical Thinking

---

# 📂 Repository Structure

```
pizza-sales-analytics-dashboard
│
├── Dashboard
│   └── Pizza Sales Dashboard.pbix
│
├── Dataset
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── Images
│   ├── Dashboard Preview.png
│   ├── Dashboard.png
│   ├── Business Insights.png
│   └── Data Model.png
│
└── README.md
```

---

# 📌 Future Improvements

- Forecasting
- Drill Through Pages
- Tooltip Pages
- Mobile Layout
- Row-Level Security (RLS)
- AI Visuals
- Bookmarks & Navigation
- Performance Optimization

---

# 👨‍💻 Author

**Rehan Khan**

Aspiring Data Analyst | Power BI | SQL | Python | Business Intelligence

---

## ⭐ If you found this project helpful, consider giving it a Star!
