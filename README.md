# 🍫 AtliQ Hardware Sales Analysis

> 🧠 **An end-to-end SQL data analytics project that transforms
> chocolate sales transactions into meaningful revenue, salesperson,
> product, country and time-based business insights.**

[SQL](https://www.microsoft.com/en-us/sql-server)
![image](https://img.shields.io/badge/SQL-Analysis-0078D4?logo=microsoftsqlserver&logoColor=white)
[Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server)
![image](https://img.shields.io/badge/Database-SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white)
[Data Analytics](https://github.com/)
![image](https://img.shields.io/badge/Project-Data%20Analytics-7B61FF)
[GitHub](https://github.com/)
![image](https://img.shields.io/badge/Portfolio-SQL%20Project-181717?logo=github)

------------------------------------------------------------------------

## 📌 Project at a Glance

  -----------------------------------------------------------------------
  **🧩 Component**               **🔧 Technology / Description**
  ------------------------------ ----------------------------------------
  📊 Project Type                **SQL Data Analytics / Sales Performance
                                 Analysis**

  📥 Primary Data                **Chocolate sales transaction dataset**

  🗄️ Database                    **Microsoft SQL Server**

  🔎 Query Language              **SQL / T-SQL**

  📈 Analysis                    **KPI, univariate, bivariate and
                                 multivariate analysis**

  📦 Records                     **1,094 sales transactions**

  👨‍💼 Salespeople                 **25 unique salespeople**

  🌍 Countries                   **6 sales countries**

  🍫 Products                    **22 chocolate products**

  📅 Data Period                 **2022**
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 🎯 Project Goal

**Convert raw chocolate sales transactions into actionable business
intelligence through SQL database management, KPI analysis, dimensional
analysis, advanced aggregations, CTEs, subqueries, CASE statements and
window functions.**

------------------------------------------------------------------------

## ✨ Key Features

-   💰 **Total Revenue & Sales KPI Analysis**
-   📦 **Boxes Shipped Analysis**
-   👨‍💼 **Salesperson Performance Analysis**
-   🌍 **Country-wise Revenue Analysis**
-   🍫 **Product-wise Revenue Analysis**
-   📅 **Monthly & Quarterly Sales Analysis**
-   📊 **Transaction Value Distribution**
-   🔗 **Bivariate Relationship Analysis**
-   🧠 **Multivariate Performance Analysis**
-   🏆 **Top Salesperson / Product / Country Identification**
-   📈 **Month-over-Month Revenue Analysis**
-   ⚡ **Revenue per Box & Revenue per Transaction**
-   🪟 **SQL Window Functions for Ranking & Growth Analysis**
-   📤 **Query Results Exported in CSV Format**
-   📊 **Dashboard-oriented Business Reporting**

------------------------------------------------------------------------

## 🏗️ Project Architecture

``` text
📥 Chocolate Sales Dataset
          ↓
🗄️ SQL Server Database
          ↓
📋 ChocSales Table
          ↓
┌─────────────────────────────┐
│                             │
▼                             ▼
📊 KPI Analysis          📈 Dimensional Analysis
│                             │
└──────────────┬──────────────┘
               ↓
        🔗 Bivariate Analysis
               ↓
        🧠 Multivariate Analysis
               ↓
        📤 CSV Query Results
               ↓
        📊 Dashboard / Report
               ↓
        🎯 Business Insights
```

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   🗄️ **Microsoft SQL Server**
-   🔎 **T-SQL / SQL**
-   📊 **SQL Data Analytics**
-   🧮 **Aggregations & Calculated Metrics**
-   🧠 **CTEs & Subqueries**
-   🪟 **Window Functions**
-   📅 **Time-Series Analysis**
-   📤 **CSV Query Results**
-   📈 **Dashboard & Data Visualization**
-   📝 **GitHub Documentation**

------------------------------------------------------------------------

## 🚀 Getting Started

### 1️⃣ Clone the Repository

``` bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd AtliQ-Hardware-Sales-Analysis
```

### 2️⃣ Open SQL Server

Open **SQL Server Management Studio (SSMS)** or another SQL
Server-compatible client.

### 3️⃣ Create the Database

Open:

``` text
database/Database.sql
```

Run the script.

The script creates:

``` text
ChocSalesDB
```

and the main table:

``` text
dbo.ChocSales
```

### 4️⃣ Run the Analysis

Open:

``` text
queries/Queries.sql
```

Run the analysis in this order:

``` text
Phase 1 → KPI Analysis
Phase 2 → Univariate Analysis
Phase 3 → Bivariate Analysis
Phase 4 → Multivariate Analysis
```

### 5️⃣ Review Query Results

The generated outputs can be exported as CSV files and stored in:

``` text
results/
```

### 6️⃣ Review the Dashboard

Open the dashboard image and project report included in the repository.

> 💡 **Note:** The exact database/query file locations can be changed
> according to the final GitHub folder structure.

------------------------------------------------------------------------

## 📂 Repository Structure

``` text
AtliQ-Hardware-Sales-Analysis/
│
├── 📁 database/
│   └── Database.sql
│
├── 📁 queries/
│   └── Queries.sql
│
├── 📁 results/
│   ├── 📁 Phase_1_KPI/
│   ├── 📁 Phase_2_Univariate/
│   ├── 📁 Phase_3_Bivariate/
│   └── 📁 Phase_4_Multivariate/
│
├── 📁 dashboard/
│   └── Dashboard Image.png
│
├── 📁 reports/
│   └── AtliQ_Hardware_Sales_SQL_Project_Report.pdf
│
├── 📄 README.md
└── 📄 LICENSE
```

------------------------------------------------------------------------

# Table of Contents

1.  Introduction
2.  Project Overview
3.  Problem Statement
4.  Objectives
5.  Scope of the Project
6.  **Data Source** and Data Fields
7.  Data Understanding
8.  System Architecture
9.  Data Model / ER Design
10. **Database** Design
11. Data Cleaning and Preparation
12. Data Classification
13. **SQL** **Analytics**
14. **Python** **Analytics**
15. **Risk Analysis**
16. Dashboard Design
17. Functional Requirements
18. Non-Functional Requirements
19. Project Workflow
20. Testing Strategy
21. **Limitations**
22. **Future Enhancements**
23. Conclusion
24. Suggested Project Folder Structure
25. Key Definitions

------------------------------------------------------------------------

# 1. 📖 Introduction

The **AtliQ Hardware Sales Analysis** project is a SQL-based data
analytics solution designed to convert raw chocolate sales transactions
into structured business intelligence.

The source dataset contains transaction-level information including
**salesperson, country, product, date, sales amount and boxes shipped**.

The system is designed around a **Microsoft SQL Server database**, with
**T-SQL** providing the main analytical layer. The analysis progresses
from basic KPIs to univariate, bivariate and multivariate business
analysis.

The final outputs support **KPI reporting, revenue trends, salesperson
performance, product analysis, country analysis, shipment analysis and
management-oriented business insights**.

------------------------------------------------------------------------

# 2. 🔎 Project Overview

The project follows an end-to-end SQL analytics pipeline:

1.  Load the **Chocolate Sales Dataset**.
2.  Create the **ChocSalesDB** database.
3.  Create the `dbo.ChocSales` transaction table.
4.  Store sales records in SQL Server.
5.  Run **Phase 1 KPI Analysis**.
6.  Run **Phase 2 Univariate Analysis**.
7.  Run **Phase 3 Bivariate Analysis**.
8.  Run **Phase 4 Multivariate Analysis**.
9.  Export important query results to **CSV**.
10. Convert analytical outputs into dashboard-ready insights and
    business recommendations.

------------------------------------------------------------------------

# 3. ❗ Problem Statement

A large transaction table can make it difficult for a sales manager to
understand the real business performance behind individual records.

Important questions include:

-   Which salesperson generates the highest revenue?
-   Which country contributes the most revenue?
-   Which products generate the highest sales?
-   Which months have the strongest revenue?
-   Which quarter performs best?
-   How many boxes are shipped?
-   What is the average transaction value?
-   Which salesperson-product combinations perform best?
-   Which country-product combinations are most efficient?
-   How is revenue changing month over month?

The project addresses these questions by using structured **SQL
analysis** to convert raw transactions into clear performance metrics
and business insights.

------------------------------------------------------------------------

# 4. 🎯 Objectives

-   Create a structured **SQL Server database** for sales transactions.
-   Store and analyze **1,094 sales records**.
-   Calculate overall revenue, shipment and transaction KPIs.
-   Compare salesperson performance.
-   Compare country-level sales performance.
-   Analyze product-level revenue and shipment volume.
-   Identify monthly and quarterly sales trends.
-   Analyze transaction value distributions.
-   Study relationships between business dimensions.
-   Use **CTEs, subqueries and window functions** for advanced analysis.
-   Calculate revenue contribution and efficiency metrics.
-   Calculate month-over-month revenue changes.
-   Generate CSV outputs for reporting and visualization.
-   Produce dashboard-ready business insights.

------------------------------------------------------------------------

# 5. 📦 Scope of the Project

## **5.1 Included**

-   **SQL Server database** creation.
-   `ChocSales` transaction table.
-   Salesperson analysis.
-   Country analysis.
-   Product analysis.
-   Revenue analysis.
-   Boxes shipped analysis.
-   Transaction analysis.
-   Monthly revenue analysis.
-   Quarterly revenue analysis.
-   Transaction value distribution.
-   Bivariate analysis.
-   Multivariate analysis.
-   Revenue contribution analysis.
-   Revenue per box analysis.
-   Revenue per transaction analysis.
-   Month-over-month analysis.
-   SQL query result exports in CSV.
-   Dashboard-oriented reporting.

## **5.2 Optional / Future Extensions**

-   Power BI interactive dashboard.
-   Automated CSV generation.
-   Scheduled SQL reporting.
-   Customer-level analysis if customer data is added.
-   Profit and margin analysis if cost data is added.
-   Inventory analysis if stock data is added.
-   Forecasting and predictive analytics.
-   Real-time sales monitoring.
-   Cloud database deployment.

------------------------------------------------------------------------

# 6. **Data Source** and Data Fields

The project uses the **Choc Sales Dataset**, loaded into SQL Server as
the `dbo.ChocSales` table.

The database script defines six required transaction fields.

  Field             Type / Meaning      Use
  ----------------- ------------------- --------------------------------
  `Sales_Person`    Salesperson name    Sales performance analysis
  `Country`         Sales country       Market analysis
  `Product`         Chocolate product   Product performance analysis
  `Date`            Transaction date    Monthly / quarterly analysis
  `Amount`          Sales revenue       Revenue calculations
  `Boxes_Shipped`   Number of boxes     Shipment volume and efficiency

The SQL database uses `NVARCHAR`, `DATE`, `DECIMAL(12,2)` and `INT` data
types for these fields. fileciteturn11file0L32-L39

------------------------------------------------------------------------

# 7. 🧠 Data Understanding

The dataset is a **transaction-oriented sales dataset**.

Each row represents a sales transaction containing:

-   👨‍💼 Salesperson
-   🌍 Country
-   🍫 Product
-   📅 Transaction date
-   💰 Revenue amount
-   📦 Boxes shipped

The strongest directly supported analyses are:

-   Revenue performance
-   Transaction volume
-   Shipment volume
-   Salesperson performance
-   Country performance
-   Product performance
-   Monthly trends
-   Quarterly trends
-   Revenue efficiency
-   Transaction value distribution

The database script identifies **1,094 records** and Microsoft SQL
Server as the SQL dialect. fileciteturn11file0L12-L16

------------------------------------------------------------------------

# 8. 🏗️ System Architecture

The architecture separates database creation, SQL analysis, result
generation and presentation.

  -----------------------------------------------------------------------
  Layer                   Responsibility          Technology
  ----------------------- ----------------------- -----------------------
  📥 Data Layer           Source sales            Excel / CSV dataset
                          transactions            

  🗄️ Database Layer       Structured transaction  Microsoft SQL Server
                          storage                 

  🔎 Query Layer          Business analysis       T-SQL

  📊 Analytics Layer      KPIs, trends and        SQL
                          comparisons             

  📤 Output Layer         Query result files      CSV

  📈 Visualization Layer  Charts and dashboard    Dashboard / BI tools

  📝 Reporting Layer      Documentation           PDF / GitHub README
  -----------------------------------------------------------------------

## Architecture Flow

``` text
Chocolate Sales Dataset
        |
        v
Database.sql
        |
        v
ChocSalesDB
        |
        v
dbo.ChocSales
        |
        +------------------+
        |                  |
        v                  v
Phase 1 KPI          Phase 2 Univariate
Analysis             Analysis
        |                  |
        +--------+---------+
                 |
                 v
        Phase 3 Bivariate
              Analysis
                 |
                 v
       Phase 4 Multivariate
              Analysis
                 |
                 v
          CSV Results
                 |
                 v
        Dashboard / Report
                 |
                 v
       Business Insights
```

------------------------------------------------------------------------

# 9. 🗂️ Data Model / ER Design

The project uses a simple transaction-focused relational design.

The central table is:

``` text
dbo.ChocSales
```

### Proposed Data Model

``` text
                 +-------------------------+
                 |       ChocSales         |
                 |-------------------------|
                 | Sales_Person             |
                 | Country                  |
                 | Product                  |
                 | Date                     |
                 | Amount                   |
                 | Boxes_Shipped            |
                 +------------+------------+
                              |
             +----------------+----------------+
             |                |                |
             v                v                v
       👨‍💼 Salesperson    🌍 Country       🍫 Product
             |                |                |
             +----------------+----------------+
                              |
                              v
                       📅 Date Analysis
                              |
                              v
                    📊 Business Analytics
```

The table contains the complete transaction-level analytical information
required by the SQL query phases.

------------------------------------------------------------------------

# 10. **Database** Design

## **Core Table**

  -----------------------------------------------------------------------
  Table                   Key Fields              Purpose
  ----------------------- ----------------------- -----------------------
  `dbo.ChocSales`         `Sales_Person`,         Central sales
                          `Country`, `Product`,   transaction table
                          `Date`, `Amount`,       
                          `Boxes_Shipped`         

  -----------------------------------------------------------------------

The database script first creates `ChocSalesDB`, switches to it and
recreates `dbo.ChocSales` before inserting the transaction records.
fileciteturn11file0L19-L43

## **Relationship Logic**

The transaction table supports analytical grouping across:

-   One salesperson → many transactions.
-   One country → many transactions.
-   One product → many transactions.
-   One date → many transactions.
-   Each transaction contains an amount and shipment volume.

These dimensions are combined through SQL `GROUP BY`, CTEs and window
functions to produce higher-level insights.

------------------------------------------------------------------------

# 11. 🧹 Data Cleaning and Preparation

The SQL database setup prepares the dataset for analysis by:

1.  Creating the required database.
2.  Creating the transaction table.
3.  Defining appropriate SQL data types.
4.  Enforcing `NOT NULL` on the transaction fields.
5.  Loading the sales records.
6.  Converting dates into SQL `DATE`.
7.  Storing revenue as `DECIMAL(12,2)`.
8.  Storing shipment quantity as `INT`.
9.  Making the dataset directly queryable through T-SQL.

The source database script uses `NOT NULL` constraints on all six
transaction fields. fileciteturn11file0L28-L39

------------------------------------------------------------------------

# 12. 🏷️ Data Classification

The project classifies the raw transaction data into analytical business
dimensions.

  -----------------------------------------------------------------------
  Classification          Examples                Purpose
  ----------------------- ----------------------- -----------------------
  👨‍💼 Salesperson          Individual sales        Performance comparison
                          representatives         

  🌍 Country              India, USA, UK, Canada, Market comparison
                          Australia, New Zealand  

  🍫 Product              Chocolate product names Product analysis

  📅 Time                 Month / Quarter         Trend analysis

  💰 Revenue              Transaction amount      Financial analysis

  📦 Shipment             Boxes shipped           Volume / efficiency
                                                  analysis
  -----------------------------------------------------------------------

These classifications allow the same transaction table to answer many
different business questions.

------------------------------------------------------------------------

# 13. **SQL** **Analytics**

The SQL analysis is divided into four phases.

## **13.1 Phase 1 --- KPI Analysis**

Phase 1 establishes the overall sales performance baseline.

The project calculates:

1.  💰 Total Revenue
2.  📦 Total Boxes Shipped
3.  🧾 Total Sales Transactions
4.  💵 Average Transaction Value
5.  📦 Average Boxes per Transaction
6.  ⚡ Revenue per Box
7.  ⬆️ Highest Transaction Value
8.  ⬇️ Lowest Transaction Value
9.  👨‍💼 Number of Salespeople
10. 🌍 Number of Countries
11. 🍫 Number of Products
12. 🏆 Top Salesperson Revenue
13. 🥇 Top Product Revenue
14. 🌎 Top Country Revenue
15. 📊 Country Revenue Contribution

These KPIs are explicitly defined in the SQL query file.
fileciteturn11file1L525-L541

### Example --- Total Revenue

``` sql
SELECT
    SUM(Amount) AS Total_Revenue
FROM ChocSales;
```

The KPI uses `SUM(Amount)` to calculate total company revenue.
fileciteturn11file1L544-L554

### Example --- Revenue per Box

``` sql
SELECT
    SUM(Amount) / SUM(Boxes_Shipped) AS Revenue_Per_Box
FROM ChocSales;
```

------------------------------------------------------------------------

## **13.2 Phase 2 --- Univariate Analysis**

Phase 2 studies individual dimensions independently.

### 👨‍💼 Salesperson

-   Revenue by salesperson
-   Transactions by salesperson
-   Boxes shipped by salesperson

### 🌍 Country

-   Revenue by country
-   Transactions by country
-   Boxes shipped by country

### 🍫 Product

-   Revenue by product
-   Transactions by product
-   Boxes shipped by product

### 📅 Time

-   Monthly revenue
-   Monthly transaction volume
-   Monthly boxes shipped
-   Quarterly revenue

### 📊 Distribution

-   Transaction value distribution
-   Boxes shipped distribution

The SQL file contains these analyses as the Phase 2 univariate section.
fileciteturn11file1L764-L781

------------------------------------------------------------------------

## **13.3 Phase 3 --- Bivariate Analysis**

Phase 3 studies relationships between two business dimensions.

Examples include:

-   💰 Transaction Value vs Box Volume
-   📊 Revenue Band vs Box Volume
-   👨‍💼 Salesperson vs Product Mix
-   🌍 Salesperson vs Country Coverage
-   🍫 Product vs Country Coverage
-   📦 Product vs Average Boxes
-   🌍 Country vs Average Boxes
-   👨‍💼 Salesperson vs Average Boxes
-   💵 Product vs Transaction Value Band
-   👨‍💼 Salesperson vs Transaction Value Band
-   🌍 Country vs Transaction Value Band

This phase moves beyond simple rankings and investigates how sales
dimensions behave together.

------------------------------------------------------------------------

## **13.4 Phase 4 --- Multivariate Analysis**

Phase 4 combines multiple business dimensions to produce deeper
insights.

### 🔥 Key Analyses

-   🥇 Top salesperson in each country
-   🏆 Top 3 salespeople in each country
-   🍫 Top products in each country
-   👨‍💼 Salesperson + Product performance
-   ⚡ Salesperson + Product revenue per box
-   🌍 Country + Product revenue contribution
-   👨‍💼 Salesperson + Country revenue contribution
-   📅 Month + Country revenue
-   🍫 Month + Product revenue
-   📈 Month-over-Month revenue growth
-   🌍 Country + Month-over-Month growth
-   ⚡ Salesperson + Country productivity
-   📦 Product + Country revenue efficiency
-   🧠 Salesperson + Country + Product scorecard

The final scorecard combines revenue, boxes shipped and transaction
count, then derives revenue per box and revenue per transaction.
fileciteturn12file0L309-L340

------------------------------------------------------------------------

# 14. **Python** **Analytics**

Python is **not required for the core SQL analysis**.

The main analytical engine of this project is Microsoft SQL Server and
T-SQL.

Python can optionally be used for:

-   📤 Reading exported CSV query results
-   📊 Additional visualization
-   📈 Chart generation
-   🧹 Supporting data preparation
-   📋 Automated reporting
-   📑 Combining multiple SQL outputs
-   🖼️ Creating portfolio-ready visuals

For the core project, the SQL scripts can be executed directly in SQL
Server Management Studio.

------------------------------------------------------------------------

# 15. **Risk Analysis**

This project is focused on **sales performance**, so risk analysis is
treated as a business-performance extension rather than a safety or
accident-risk model.

Possible analytical risk indicators include:

  --------------------------------------------------------------------------------
  Indicator               Meaning                          Data Requirement
  ----------------------- -------------------------------- -----------------------
  💰 Revenue              Dependence on top                Available
  Concentration           countries/products/salespeople   

  📉 MoM Decline          Detect declining monthly revenue Available

  📦 Shipment Efficiency  Revenue generated per box        Available

  👨‍💼 Sales Dependency     Revenue concentration among top  Available
                          salespeople                      

  🌍 Market Dependency    Revenue concentration among top  Available
                          countries                        

  🍫 Product Dependency   Revenue concentration among top  Available
                          products                         
  --------------------------------------------------------------------------------

These metrics can help management identify areas where revenue is highly
concentrated or where performance is weakening.

------------------------------------------------------------------------

# 16. 📊 Dashboard Design

The project dashboard is designed to communicate the SQL analysis
visually.

The supplied dashboard concept includes:

-   💰 Total Revenue
-   🧾 Total Sales
-   📦 Total Quantity
-   🌍 Total Countries
-   👥 Total Customers
-   🌍 Top Countries by Revenue
-   📈 Revenue Trend Over Time
-   🍫 Revenue by Product Category
-   👨‍💼 Top Salespeople by Revenue
-   📅 Sales by Month
-   🚚 Revenue by Shipment Mode
-   📋 Quick Insights / KPI Summary
-   📊 Revenue by Year & Quarter
-   💡 Key Business Insights

### Dashboard Purpose

The dashboard converts SQL query outputs into:

-   KPI cards
-   Ranking charts
-   Trend charts
-   Distribution charts
-   Business summaries
-   Management-oriented insights

> ⚠️ **Dashboard Data Note:** The supplied dashboard image represents a
> different/older visualization version than the current SQL database
> dataset. The current database contains the 2022 `ChocSales` dataset
> with 1,094 records, while the dashboard image displays a different set
> of KPI values and dimensions. The SQL scripts and database should
> therefore be treated as the source of truth for the current
> repository.

------------------------------------------------------------------------

# 17. ⚙️ Functional Requirements

The system shall:

1.  Create the SQL Server database.
2.  Create the `ChocSales` table.
3.  Store sales transactions.
4.  Calculate total revenue.
5.  Calculate shipment volume.
6.  Calculate transaction counts.
7.  Analyze salesperson performance.
8.  Analyze country performance.
9.  Analyze product performance.
10. Analyze monthly and quarterly trends.
11. Calculate revenue efficiency metrics.
12. Perform bivariate analysis.
13. Perform multivariate analysis.
14. Calculate MoM revenue changes.
15. Export query results to CSV.
16. Provide data for dashboard/reporting.

------------------------------------------------------------------------

# 18. 🛡️ Non-Functional Requirements

### Accuracy

All calculations should be reproducible directly from the stored SQL
data.

### Performance

SQL aggregations should remain efficient for the dataset size.

### Usability

Query names, analysis phases and CSV outputs should be easy to
understand.

### Maintainability

Database creation and analytical queries are separated into:

``` text
Database.sql
Queries.sql
```

### Scalability

The design can later be extended with:

-   Customer data
-   Cost data
-   Profit data
-   Inventory data
-   Targets
-   Budgets
-   Additional years

### Reliability

The database script recreates the analysis table consistently, allowing
the project to be rebuilt from the supplied SQL file.

------------------------------------------------------------------------

# 19. 🔄 Project Workflow

``` text
+--------------------------+
| 1. Source Dataset        |
| Chocolate Sales Data     |
+------------+-------------+
             |
             v
+--------------------------+
| 2. Database Setup        |
| Create ChocSalesDB       |
+------------+-------------+
             |
             v
+--------------------------+
| 3. Table Creation        |
| dbo.ChocSales            |
+------------+-------------+
             |
             v
+--------------------------+
| 4. Data Loading          |
| 1,094 Transactions       |
+------------+-------------+
             |
             v
+--------------------------+
| 5. KPI Analysis          |
| Overall Performance      |
+------------+-------------+
             |
             v
+--------------------------+
| 6. Univariate Analysis   |
| Single-Dimension Trends  |
+------------+-------------+
             |
             v
+--------------------------+
| 7. Bivariate Analysis    |
| Dimension Relationships  |
+------------+-------------+
             |
             v
+--------------------------+
| 8. Multivariate Analysis |
| Advanced Scorecards      |
+------------+-------------+
             |
             v
+--------------------------+
| 9. CSV Results           |
| Query Output Files       |
+------------+-------------+
             |
             v
+--------------------------+
| 10. Dashboard / Report   |
| Business Insights        |
+--------------------------+
```

------------------------------------------------------------------------

# 20. 🧪 Testing Strategy

  -----------------------------------------------------------------------
  Test                                Expected Result
  ----------------------------------- -----------------------------------
  🗄️ Database connection              SQL Server database opens
                                      successfully

  🏗️ Database creation                `ChocSalesDB` is created

  📋 Table creation                   `dbo.ChocSales` is created without
                                      errors

  📥 Data insertion                   Sales records are stored

  🔎 Data retrieval                   `SELECT` queries return expected
                                      records

  💰 Revenue calculation              `SUM(Amount)` returns revenue

  📦 Shipment calculation             `SUM(Boxes_Shipped)` returns
                                      shipment volume

  👨‍💼 Salesperson grouping             Salesperson-level metrics are
                                      generated

  🌍 Country grouping                 Country-level metrics are generated

  🍫 Product grouping                 Product-level metrics are generated

  📅 Monthly analysis                 Monthly revenue is generated

  📊 Quarterly analysis               Quarterly revenue is generated

  🪟 Window functions                 Ranking and MoM calculations
                                      execute

  📤 CSV export                       Query outputs can be exported
                                      successfully

  📈 Dashboard outputs                Results can be visualized correctly
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 21. **Limitations**

-   The current database is based on a single **2022 sales dataset**.
-   The database contains transaction-level sales information but does
    not include profit or cost.
-   Customer-level analysis is not supported by the current table
    structure.
-   Inventory information is not included.
-   Sales targets and budgets are not included.
-   Shipment mode and product category fields shown in the supplied
    dashboard are not columns in the current `ChocSales` table.
-   The supplied dashboard image represents a different dataset/version
    from the current SQL database.
-   MoM analysis is based on the available 2022 transaction data.
-   Predictive analytics requires additional historical data and
    modeling.

------------------------------------------------------------------------

# 22. **Future Enhancements**

The project can be extended with:

-   📅 **Multi-year sales history**
-   💰 **Profit and margin analysis**
-   🎯 **Sales targets vs actual performance**
-   👥 **Customer-level analytics**
-   📦 **Inventory management**
-   🚚 **Shipment and logistics analysis**
-   📈 **Sales forecasting**
-   🤖 **Machine learning / predictive analytics**
-   🔴 **Real-time sales dashboard**
-   🔄 **Automated CSV generation**
-   📊 **Power BI integration**
-   ☁️ **Cloud SQL deployment**
-   🔐 **Role-based reporting**
-   📧 **Automated management reports**

------------------------------------------------------------------------

# 23. ✅ Conclusion

The **AtliQ Hardware Sales Analysis** project provides a practical
framework for transforming raw chocolate sales transactions into
structured business intelligence.

The **SQL Server database** provides a reliable foundation for storing
the transaction data, while the **T-SQL analysis** converts those
records into KPIs, rankings, trends, efficiency metrics and
multidimensional performance insights.

The project demonstrates how SQL can progress from:

> **Raw Transactions → Database → KPIs → Univariate Analysis → Bivariate
> Analysis → Multivariate Analysis → CSV Results → Dashboard → Business
> Decisions**

The analysis uses practical SQL techniques including **aggregations,
`GROUP BY`, `CASE`, CTEs, subqueries, `ROW_NUMBER()`, `LAG()` and
`PARTITION BY`**. The query file explicitly organizes the work into KPI,
univariate and multivariate phases. fileciteturn11file1L525-L541

This makes the project suitable for demonstrating **SQL, data analytics,
business intelligence and analytical problem-solving skills** in a
GitHub portfolio.

------------------------------------------------------------------------

# 24. Suggested Project Folder Structure

``` text
AtliQ-Hardware-Sales-Analysis/
│
├── database/
│   └── Database.sql
│
├── queries/
│   └── Queries.sql
│
├── results/
│   ├── Phase_1_KPI/
│   │   ├── P1_01_Total_Revenue.csv
│   │   ├── P1_02_Total_Boxes_Shipped.csv
│   │   ├── P1_03_Total_Transactions.csv
│   │   └── ...
│   │
│   ├── Phase_2_Univariate/
│   │   ├── P2_01_Revenue_By_Salesperson.csv
│   │   ├── P2_02_Transactions_By_Salesperson.csv
│   │   ├── P2_04_Revenue_By_Country.csv
│   │   ├── P2_07_Revenue_By_Product.csv
│   │   └── ...
│   │
│   ├── Phase_3_Bivariate/
│   │   ├── P3_01_Transaction_Value_vs_Box_Volume.csv
│   │   └── ...
│   │
│   └── Phase_4_Multivariate/
│       ├── P4_01_Top_Salesperson_By_Country.csv
│       ├── P4_02_Top_3_Salespeople_By_Country.csv
│       └── ...
│
├── dashboard/
│   └── Dashboard Image.png
│
├── reports/
│   └── AtliQ_Hardware_Sales_SQL_Project_Report.pdf
│
├── README.md
└── LICENSE
```

------------------------------------------------------------------------

# 25. Key Definitions

  -----------------------------------------------------------------------
  Term                                Definition
  ----------------------------------- -----------------------------------
  💰 **Revenue**                      Total sales amount generated from
                                      transactions

  🧾 **Transaction**                  One individual sales record

  📦 **Boxes Shipped**                Number of boxes included in a
                                      transaction

  👨‍💼 **Salesperson**                  Individual responsible for the sale

  🌍 **Country**                      Market in which the transaction
                                      occurred

  🍫 **Product**                      Chocolate product sold

  📊 **KPI**                          Key Performance Indicator used to
                                      summarize business performance

  📈 **MoM Growth**                   Month-over-month change compared
                                      with the previous month

  ⚡ **Revenue per Box**              Revenue generated per shipped box

  💵 **Revenue per Transaction**      Average revenue generated by a
                                      transaction

  🧠 **Univariate Analysis**          Analysis of one business dimension
                                      at a time

  🔗 **Bivariate Analysis**           Analysis of relationships between
                                      two dimensions

  🧩 **Multivariate Analysis**        Analysis involving multiple
                                      dimensions

  🪟 **Window Function**              SQL function used for ranking,
                                      comparison and analytical
                                      calculations

  🧱 **CTE**                          Common Table Expression used to
                                      build readable multi-step queries

  📤 **CSV Result**                   Exported query output used for
                                      reporting or visualization
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## **Technology Summary**

``` text
Data Source      → Chocolate Sales Dataset
Database         → Microsoft SQL Server
Database Table   → dbo.ChocSales
Query Language   → T-SQL / SQL
Analysis         → KPI + Univariate + Bivariate + Multivariate
Advanced SQL     → CTEs + Subqueries + CASE + Window Functions
Output           → CSV Query Results
Visualization    → Dashboard / Charts
Documentation    → GitHub README + PDF Report
```

------------------------------------------------------------------------

# **Project Goal**

**Transform raw chocolate sales transactions into meaningful business
intelligence through SQL Server database management, advanced SQL
analytics, CSV result generation and dashboard-oriented reporting.**

------------------------------------------------------------------------

## 📌 Important Data Note

The current SQL project is based on the supplied **`Database.sql`** and
**`Queries.sql`** files.

The database script specifies:

``` text
Database  → ChocSalesDB
Table     → dbo.ChocSales
Records   → 1,094
Year      → 2022
Columns   → Sales_Person, Country, Product,
            Date, Amount, Boxes_Shipped
```

The dashboard image supplied with the project contains different KPIs
and dimensions from the current database version. Therefore, **the SQL
database and query results are the authoritative source for this
repository**, while the dashboard is retained as a visual reference.

------------------------------------------------------------------------

## 🤝 Future Scope

The project can be extended with:

-   📈 **Power BI interactive dashboard**
-   💰 **Profit and margin analytics**
-   🎯 **Target vs actual sales**
-   👥 **Customer segmentation**
-   📦 **Inventory analytics**
-   🚚 **Shipment performance**
-   📅 **Multi-year trend analysis**
-   🤖 **Predictive sales forecasting**
-   🔄 **Automated reporting**
-   ☁️ **Cloud database deployment**
-   🔴 **Real-time sales monitoring**

------------------------------------------------------------------------

If this project is useful for learning or portfolio purposes, consider
giving the repository a **⭐ Star** on GitHub.

**Built with 🗄️ Microsoft SQL Server + 🔎 T-SQL + 📊 Data Analytics + 📈
Business Intelligence**
