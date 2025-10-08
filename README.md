# Inventory Data Source Transition Project

## 🎯 Project Overview
This Power BI project demonstrates how to build a two-page interactive dashboard for inventory analysis, focusing on transitioning reports between different data sources (Microsoft SQL Server and MySQL). The project covers the creation of six key KPIs using advanced DAX measures and highlights best practices for data validation during data source migration.

## 📊 Dashboard Pages & KPIs

### 1. Inventory Overview (Page 1)
- **Average Demand Per Day**
- **Average Availability Per Day**
- **Total Supply Shortage**

### 2. Financial Impact (Page 2)
- **Total Profit**
- **Total Loss**
- **Average Daily Loss**

*All KPIs are calculated using DAX measures to ensure accuracy and flexibility during data source transitions.*

## 🛠 Technical Implementation

### Data Sources
- **Microsoft SQL Server** (initial data source)
- **MySQL Database** (target data source after migration)

### Data Source Transition
- The project demonstrates how to migrate Power BI reports from Microsoft SQL Server to MySQL by modifying queries in the Power Query Advanced Editor.
- Covers both test-to-production transitions within SQL Server and cross-platform migration to MySQL.

### DAX & SQL Development
- Creation of all KPIs using DAX measures
- Writing SQL queries (with joins) in Microsoft SQL Server for data preparation
- Developing equivalent SQL code for MySQL

### Data Validation
- Ensures that KPI values remain consistent after changing the data source
- Discusses validation techniques to confirm that underlying data and results are unchanged

### Report Publishing
- Steps to publish the final report to Power BI Service for sharing and collaboration

## 🚀 Key Learning Outcomes
- How to transition Power BI reports between different database systems
- Best practices for data validation during migration
- Advanced DAX measure creation for business KPIs
- Writing and adapting SQL code for multiple platforms
- Real-world scenario for interview and CV enhancement

## 📝 Project Structure
- **Page 1**: Inventory KPIs (Demand, Availability, Supply Shortage)
- **Page 2**: Financial KPIs (Profit, Loss, Daily Loss)
- **Data Preparation**: SQL code for both SQL Server and MySQL
- **Data Validation**: Ensuring consistency across data sources

## 📦 Technologies Used
- Microsoft Power BI Desktop
- Power BI Service
- Microsoft SQL Server
- MySQL Database
- DAX (Data Analysis Expressions)
- Power Query

## 📋 How to Use This Project
1. Open the .pbix file in Power BI Desktop
2. Review the queries in Power Query Advanced Editor
3. Switch data source connections as needed (SQL Server ↔ MySQL)
4. Validate KPI results after migration
5. Publish to Power BI Service for sharing

## 📸 Screenshots
-https://github.com/bhargav738/Inventory-Analysis/issues/2
-https://github.com/bhargav738/Inventory-Analysis/issues/1

## 📞 Contact
- **LinkedIn**: https://www.linkedin.com/in/bhargav-mallareddi/
- **Email**: bhargavmallareddi@gmail.com
---
**💡 This project is a practical demonstration of Power BI data source migration, advanced DAX, and robust data validation for real-world business analytics.**
