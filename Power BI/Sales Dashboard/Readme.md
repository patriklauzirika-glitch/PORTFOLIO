# Sales Analysis Dashboard | AdventureWorks

## Project Overview

This project consists of the design and development of an interactive **Sales Analysis Dashboard in Power BI**, built on top of a custom **star schema Data Warehouse** created from the original **AdventureWorks** database in SQL Server.

The goal of the project was to transform transactional data into a business-oriented analytical model, allowing the creation of dynamic reports, KPIs, and actionable insights through Power BI.

The dashboard includes data modeling, DAX measures, calculated columns, and calculated tables as part of an end-to-end Business Intelligence workflow.
---

## Project Objectives

- Build a clean and scalable **star schema model** for reporting purposes.
- Connect Power BI to a SQL-based analytical database.
- Create key business KPIs using **DAX measures**.
- Practice advanced Power BI features:
  - Calculated columns
  - Calculated tables
  - Time intelligence measures
  - Interactive filtering
- Deliver a dashboard focused on sales performance analysis.

---

## Data Source

**Original Source:** AdventureWorks (Microsoft sample database)

**Transformation Layer:** SQL Server Data Warehouse developed previously using ETL processes.

**Final Data Model:** Star Schema optimized for BI reporting.

---

## Data Model

The dashboard was built using a dimensional model composed of:

### Fact Table
- `FactSales`

### Dimension Tables
- `DimDates`
- `DimCustomers`
- `DimProduct`
- `DimTerritory`
- `DimProduct`
