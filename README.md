# 📱 Mobile Sales Analysis Dashboard | Power BI

## 📌 Project Overview
This project focuses on analysing mobile phone sales data using Microsoft Power BI. It explores sales performance, customer behaviour, brand performance, and payment preferences through an interactive dashboard.

This is a guided practice project that I recreated by following my instructor's tutorial.

## 🎯 Project Objectives
- Analyse overall mobile sales performance.
- Compare sales across different mobile brands.
- Understand customer payment preferences.
- Identify monthly and day-wise sales trends.
- Analyse city-wise sales distribution.
- Explore mobile model-wise sales performance.
- Understand customer ratings.

## 📂 Dataset Description
- **Total Records:** 3,835
- **Total Columns:** 14
- **Brands:** 5
- **Cities:** 19
- **Date Range:** 2021–2024

The dataset includes transaction details, mobile brands, models, units sold, prices, customer information, payment methods, cities, and customer ratings.

**Dataset Source:** Provided by Satish Dhawale as part of the SkillCourse Power BI tutorial.

## 🛠️ Tools & Technologies
- Microsoft Power BI
- Microsoft Excel
- DAX (Data Analysis Expressions)

## 📊 Dashboard Features

**Key Performance Indicators (KPIs)**
- Total Sales
- Total Quantity
- Total Transactions
- Average Unit Price

**Sales Analysis**
- Brand-wise Sales Analysis
- Mobile Model-wise Sales Analysis
- Monthly Quantity Trends
- Day-wise Sales Analysis

**Customer & Payment Analysis**
- Customer Ratings
- Payment Method Distribution

**Geographical Analysis**
- City-wise Sales Distribution using Map Visualisation

**Interactive Filters**
- Month
- Brand
- Mobile Model
- Payment Method
- Day Name

## 🧮 DAX Measures

**1. Total Sales**
```dax
Total_sales =
SUMX(
    'Sales Data',
    'Sales Data'[Units Sold] *
    'Sales Data'[Price Per Unit]
)
```

**2. Total Quantity**
```dax
Total_quantity =
SUM('Sales Data'[Units Sold])
```

**3. Total Transactions**
```dax
Total_transaction =
COUNTROWS('Sales Data')
```

**4. Average Unit Price**
```dax
Average =
AVERAGE('Sales Data'[Price Per Unit])
```

## 📚 Key Learnings
- Creating interactive dashboards.
- Writing DAX measures.
- Working with different visualisations.
- Analysing sales and customer data.
- Using slicers and filters.
- Presenting data through visual storytelling.

## 🙏 Credits

This is a guided practice project created by following a tutorial by **Satish Dhawale, Founder of SkillCourse**.

I recreated this dashboard independently as part of my Power BI learning journey.

## 📸 Dashboard Preview

![Mobile Sales Dashboard](dashboard-preview.png)

---

**First Power BI Practice Project | Data Analytics Learning Journey**
