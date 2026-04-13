#  Regional Sales Analysis Dashboard — Tableau

A course-end project for the Data Visualization Using Tableau , focused on building an interactive sales performance dashboard to compare two selected regions.

---

##  Project Overview

This project analyzes and visualizes sales performance across two selectable regions using Tableau. The goal is to help upper management compare regional trends, identify areas for improvement, and make informed strategic decisions through a dynamic, interactive dashboard.

---

## 🗂️ Repository Contents

```
├── sales_performance_dashboard.twbx   # Packaged Tableau workbook
├── regional_sales_analysis_problem_statement.pdf  # Project brief
└── README.md
```

---

##  Objectives

- Compare total sales between a **Primary** and **Secondary** region
- Analyze average sales per order and total order counts per region
- Identify the number of unique customers per region
- Track the number of distinct products sold per region
- Present all findings in a single, dynamic Tableau dashboard

---

##  Features & Implementation

### 1. Sales Performance Parameters
- Created **Primary Region** and **Secondary Region** parameters listing all available regions
- Built calculated fields to filter data dynamically based on selected regions
- Dedicated worksheets display total sales for each region separately

### 2. Average Sales & Order Statistics
- Worksheet showing **average sales per order** for both regions
- Displays the **total number of orders** per region
- Filters applied to ensure each worksheet reflects only the selected region

### 3. Customer & Product Analysis
- Worksheet displaying the count of **unique customers** per region
- Worksheet showing the number of **distinct products sold** per region
- Filters applied for data accuracy across both regions

### 4. Comparative Dashboard
- All individual worksheets combined into a **single unified dashboard**
- Containers partition the layout into clear Primary and Secondary region sections
- **Parameter controls** allow users to switch regions and instantly update all visualizations

---

## 📈 Key Metrics Tracked

| Metric | Description |
|---|---|
| Total Sales | Sum of sales for the selected region |
| Average Sales per Order | Mean order value within the region |
| Total Orders | Count of all orders in the region |
| Unique Customers | Count of distinct customers |
| Products Sold | Count of distinct products |

---

## 🚀 How to Open the Dashboard

1. Download and install [Tableau Public](https://public.tableau.com/) (free) or Tableau Desktop
2. Clone or download this repository
3. Open `sales_performance_dashboard.twbx` in Tableau
4. Use the **Primary Region** and **Secondary Region** parameter controls on the dashboard to select and compare any two regions

---

## 🧰 Tools & Technologies

- **Tableau** — Data visualization and dashboard creation
- **Calculated Fields** — Custom logic for region filtering
- **Parameters** — Dynamic region selection
- **Dashboard Containers** — Structured layout for comparative view

---

## 📚 Course Context

> **Course:** Data Visualization Using Tableau Certification Training  
> **Project Type:** Course-End Project  
> **Submission:** Word document with step-by-step screenshots uploaded to the Learning Management System (LMS)

---

## 📄 License

This project was created for educational purposes as part of a certification training programme.
