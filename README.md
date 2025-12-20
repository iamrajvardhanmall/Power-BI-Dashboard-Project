# 📊 Power BI Dashboard Project

## 📌 Project Overview
This project presents a **professional Power BI dashboard** designed to analyze business performance through **interactive, data-driven visualizations**. The dashboard transforms raw data into **actionable insights**, enabling stakeholders to track KPIs, identify trends, and support informed decision-making.

This repository is created as a **portfolio-level Business Intelligence project**, showcasing hands-on expertise in **Power BI, DAX, data modeling, and dashboard design** using real-world BI best practices.

---

## 🎯 Project Objectives
- Design an **enterprise-style Power BI dashboard**
- Apply **best practices in data modeling (Star Schema)**
- Build meaningful **KPIs and calculated measures using DAX**
- Enable **interactive analysis** with slicers and filters
- Deliver a **clean, executive-ready dashboard layout**

---

## 🧩 Key Features

### Executive Summary
- High-level KPIs for quick decision-making
- Snapshot view of overall business performance

### Sales Analysis
- Revenue and sales trends over time
- Comparative analysis across categories and regions

### Customer Insights
- Customer segmentation and behavioral analysis
- Identification of high-value and repeat customers

### Product Performance
- Category-wise and product-level performance analysis
- Contribution of products to total revenue

### Interactivity
- Date, category, and region slicers
- Cross-filtering between visuals
- Drill-downs and tooltips for deeper analysis

---

## 🏗️ Data Model
The dashboard is built using a **Star Schema**, the industry-standard approach for scalable and high-performance BI solutions.

### Fact Table
**Sales**
- Order Date  
- Product Key  
- Customer Key  
- Quantity  
- Revenue  
- Cost  

### Dimension Tables
- Customers  
- Products  
- Date (custom Date Table)  
- Stores / Regions (if applicable)  

### Relationships
- Sales → Customers (Many-to-One)  
- Sales → Products (Many-to-One)  
- Sales → Date Table (Many-to-One)  

This structure ensures **accurate aggregations, optimized performance, and clean DAX calculations**.

---

## 📐 DAX & Calculations
The project uses **DAX (Data Analysis Expressions)** to create business-critical metrics such as:
- Total Revenue
- Total Cost
- Profit and Profit Margin
- Time Intelligence measures (MTD, YTD, trend analysis)
- Dynamic KPIs responsive to slicers

All measures are written with **performance, readability, and scalability** in mind.

---

## 🎨 Dashboard Design Principles
- Clean and minimal layout
- Consistent and professional color palette
- Logical visual hierarchy
- Business-friendly visuals (cards, bar charts, line charts, tables)
- Focus on insight clarity over visual clutter

---

## 🛠️ Tools & Technologies
- **Microsoft Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (ETL & data transformation)**
- **Star Schema Data Modeling**

---

## 🚀 How to Run This Project

### Prerequisites
- Install **Power BI Desktop**  
  https://powerbi.microsoft.com/desktop/

### Steps
1. Clone or download this repository  
2. Open the `.pbix` file using **Power BI Desktop**
3. The dashboard loads automatically and is ready to use
4. Use slicers and filters to explore insights interactively
5. *(Optional)* Publish to Power BI Service for sharing and scheduled refresh

✅ No database setup  
✅ No credentials required  
✅ No environment configuration  

---

## 📷 Dashboard Preview
Dashboard screenshots are included in the repository for quick viewing.  
For full interactivity, open the `.pbix` file in **Power BI Desktop**.

---

## 📈 Use Cases
- Portfolio project for **Data Analyst / Business Intelligence roles**
- Reference project for **learning Power BI and DAX**
- Template for **sales and performance dashboards**
- Demonstration of **real-world BI best practices**

---

## ⚠️ Notes
- GitHub does not support interactive Power BI reports
- Scheduled refresh requires Power BI Service
- External data sources (if any) may require reconfiguration

---

## 👤 Author
**Rajvardhan Mall**  
Data Analytics & Business Intelligence Enthusiast  

⭐ If you find this project useful, feel free to star the repository.
