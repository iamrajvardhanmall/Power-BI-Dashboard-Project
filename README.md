# 📊 Power BI Dashboard Project

## 📌 Project Overview
This project presents a **professional Power BI dashboard** designed to analyze business performance using **interactive and data-driven visualizations**. The dashboard converts raw data into actionable insights, helping stakeholders track KPIs, identify trends, and support data-driven decision-making.

This repository is created as a **portfolio-level Business Intelligence project**, demonstrating hands-on skills in **Power BI, DAX, data modeling, and dashboard design**.

---

## 🎯 Project Objectives
- Design an **enterprise-style Power BI dashboard**
- Implement **best practices in data modeling (Star Schema)**
- Create meaningful **KPIs and calculated measures**
- Enable **interactive analysis** using slicers and filters
- Deliver a **clean, executive-ready dashboard layout**

---

## 🧩 Key Features
- **Executive Summary**
  - High-level KPIs for quick insights
  - Snapshot of overall business performance

- **Sales Analysis**
  - Revenue trends over time
  - Comparative analysis across categories and regions

- **Customer Insights**
  - Customer segmentation and behavior analysis
  - Identification of high-value customers

- **Product Performance**
  - Category-wise and product-level performance
  - Contribution to total revenue

- **Interactivity**
  - Date, category, and region slicers
  - Cross-filtering between visuals
  - Drill-down and tooltips for detailed analysis

---

## 🏗️ Data Model
The dashboard follows a **Star Schema**, which is a standard industry approach for scalable and high-performance BI solutions.

### Fact Table
- **Sales**
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

---

## 📐 DAX & Calculations
The project uses **DAX (Data Analysis Expressions)** to create:
- Total Revenue
- Total Cost
- Profit and Profit Margin
- Time intelligence metrics (MTD, YTD, trends)
- Dynamic KPIs responsive to slicers

All measures are written with performance and readability in mind.

---

## 🎨 Dashboard Design Principles
- Clean and minimal layout
- Consistent color palette
- Logical visual hierarchy
- Business-friendly charts (cards, bar charts, line charts, tables)
- Focus on clarity and insight rather than clutter

---

## 🛠️ Tools & Technologies
- **Microsoft Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (ETL & data transformation)**
- **Star Schema Data Modeling**

---

## 🚀 How to Use This Project
1. Install **Power BI Desktop**
2. Clone or download this repository
3. Open the `.pbix` file using Power BI Desktop
4. Use slicers and filters to explore the dashboard
5. (Optional) Publish to Power BI Service for sharing and refresh

---

## 📷 Dashboard Preview
Screenshots of the dashboard are included in the repository.  
For full interactivity, open the `.pbix` file in Power BI Desktop.

---

## 📈 Use Cases
- Portfolio project for **Data Analyst / BI roles**
- Reference project for **learning Power BI**
- Template for **sales and performance dashboards**
- Demonstration of **real-world BI best practices**

---

## ⚠️ Notes
- GitHub does not support interactive Power BI reports.
- Scheduled refresh requires Power BI Service.
- External data sources (if any) may require local reconfiguration.

---

## 👤 Author
**Rajvardhan Mall**  
Data Analytics & Business Intelligence Enthusiast  

⭐ If you find this project useful, feel free to star the repository.
