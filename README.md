# 📊 Supply Chain Operational Dashboard | Power BI

## Overview

This project is an interactive **Supply Chain Operational Dashboard** built in **Power BI** to monitor operational performance across supply chain categories and distribution activity.

The dashboard focuses on tracking core KPIs such as **Fill Rate**, **Unsaleable %**, **Stores Ordered**, and category performance to help identify trends and support operational decision-making.

The goal of this project was to practice building business-focused dashboards and transforming raw operational data into clear, actionable insights.

---

## Dashboard Preview

Key dashboard sections include:

### 🎯 KPI Cards
- Fill Rate %
- Unsaleable %
- Stores Ordered

### 📈 Trend Analysis
- Fill Rate average by Week and Year

### 📊 Category Performance
- Fill Rate vs Unsaleable % by Category

### 🏪 Operational Activity
- Stores Ordered and SKU Count by Category

### 🍊 Distribution Overview
- Category performance comparison
- Product category insights
- Order volume distribution by Mode

---

## Dataset

The dataset simulates supply chain operational activity and includes:

- Date
- Week / Year / Quarter
- Distribution Center
- Category / Sub-category
- Mode
- Shipper
- Grower
- SKU
- Ordered Quantity
- Filled Quantity
- Unsaleable Quantity
- Total Cost
- Stores Ordered

### KPI calculations

**Fill Rate %**
```DAX
Fill Rate % = DIVIDE([Filled Qty],[Ordered Qty])
```

**Unsaleable %**
```DAX
Unsaleable % = DIVIDE([Unsaleable Qty],[Ordered Qty])
```

---

## Tools Used

🟡 **Power BI Desktop**

### Features used:
- Data modeling
- DAX measures
- Line charts
- Clustered column charts
- Gauge visuals
- Donut charts
- Data labels
- Visual formatting
- Dashboard layout design

---

## Key Insights

Example insights from the dashboard:

✅ Fill Rate remained above target in most weeks

⚠️ Some product categories showed higher unsaleable percentages

📦 Category demand varied across supply chain groups

🏪 Store ordering activity differed by product type

📈 Weekly trends made it easier to identify performance drops and recovery periods

---

## Skills Demonstrated

### 🧠 Analytics
- Data Analysis
- KPI Reporting
- Trend Analysis
- Business Intelligence
- Data Storytelling

### 📊 Power BI
- Dashboard Development
- Data Visualization
- DAX Measures
- Visual formatting
- Interactive reporting

### 📦 Business
- Supply Chain Analytics
- Operational Reporting
- Performance monitoring

---

## Project Purpose

This project was created as part of my **data analytics portfolio** to strengthen Power BI dashboard development and improve how I communicate business insights through data visualization.

The focus was on creating a dashboard that is:

✔️ Interactive  
✔️ Easy to understand  
✔️ Business focused  
✔️ Visually clean  
✔️ Useful for operational decision-making

---

## Files

- `Supply Chain Operational Dashboard BI.pbix`
- `README.md`

---

## Connect

Always open to feedback and learning.

💼 LinkedIn: www.linkedin.com/in/barany-cristian
