# 🍫 **Chocolate Sales SQL Analytics Project** 📊

SQL Portfolio Project --- Sales Performance & Revenue Optimization

A complete SQL analytics project built around a chocolate-sales
transaction dataset. The project progresses from KPI analysis to
univariate, bivariate, and multivariate analysis, with the end
consumer defined as a Sales Manager.

📌 Project Overview

Business Objective

The goal of this project is to transform raw chocolate-sales
transactions into actionable business insights around:

Revenue performance

Salesperson productivity

Country / market performance

Product performance

Shipment volume

Revenue efficiency

Transaction-value distribution

Monthly and quarterly trends

Market and product coverage

Revenue contribution

Top-performing combinations of salesperson, country, and product

Business Perspective

Sales Performance & Revenue Optimization

End Consumer

Sales Manager

The analysis is designed to help a sales manager understand where
revenue is coming from, which people/products/markets are performing
best, and where optimization opportunities exist.

📂 Repository Contents

File                                Description

README.md                         Project documentation, methodology,
insights, and business conclusions

SQL QUERY.sql                     Complete SQL analysis organized
into four analytical phases

Choc Sales_Dataset.xlsx           Source transaction dataset

Dataset Link : https://www.kaggle.com/datasets/atharvasoundankar/chocolate-sales

Dataset Structure

Column                  Description             Type

Sales Person          Salesperson responsible Categorical
for the transaction

Country               Sales market / country  Categorical

Product               Chocolate product sold  Categorical

Date                  Transaction date        Date

Amount                Transaction revenue     Numeric

Boxes Shipped         Number of boxes shipped Numeric

📊 Dataset Snapshot

Metric                                    Value

Total Revenue                   $6,183,625
Total Boxes Shipped                 177,007
Total Transactions                    1,094
Average Transaction Value           $5,652
Average Boxes / Transaction           161.8
Revenue per Box                        $35
Highest Transaction                $22,050
Lowest Transaction                      $7
Salespeople                              25
Countries                                 6
Products                                 22
Data Start Date                 03 Jan 2022
Data End Date                   31 Aug 2022
Missing Values                            0
Duplicate Rows                            0

🔎 Analytical Approach

The SQL project is divided into four progressive phases.

Phase 1 --- KPI Analysis

Establishes the overall health of the business using core metrics:

Total revenue

Total boxes shipped

Total transactions

Average transaction value

Average boxes per transaction

Revenue per box

Highest transaction value

Lowest transaction value

Number of salespeople

Number of countries

Number of products

Top salesperson by revenue

Top product by revenue

Top country by revenue

Country revenue contribution

Purpose: Build an executive-level understanding of the sales
operation before deeper analysis.

Phase 2 --- Univariate Analysis

Examines individual business dimensions independently.

Salesperson

Revenue by salesperson

Transactions by salesperson

Boxes shipped by salesperson

Country

Revenue by country

Transactions by country

Boxes shipped by country

Product

Revenue by product

Transactions by product

Boxes shipped by product

Time

Monthly revenue

Monthly transactions

Monthly boxes shipped

Quarterly revenue

Distribution Analysis

Transaction-value bands

Shipment-volume bands

Purpose: Identify leaders, laggards, concentration, and distribution
patterns.

Phase 3 --- Bivariate Analysis

Examines relationships between two business dimensions.

Key analyses include:

Transaction value vs. shipment volume

Revenue band vs. average boxes shipped

Salesperson vs. product diversity

Salesperson vs. market reach

Product vs. market reach

Country vs. product diversity

Country vs. salesperson coverage

Product vs. salesperson coverage

Product vs. average boxes per transaction

Country vs. average boxes per transaction

Salesperson vs. average boxes per transaction

Product vs. revenue band

Salesperson vs. revenue band

Country vs. revenue band

Purpose: Move beyond simple rankings and understand how business
dimensions interact.

Phase 4 --- Multivariate Analysis

Combines three or more dimensions to identify deeper performance
patterns.

Advanced analyses

Top salesperson within each country

Top 3 salespeople within each country

Top product within each country

Top 3 products within each country

Salesperson + product performance

Salesperson + product revenue per box

Country + product revenue contribution

Salesperson + country revenue contribution

Month + country revenue

Month + product revenue

Month-over-month revenue movement

Country-level month-over-month growth

Salesperson + country productivity

Country + product revenue efficiency

Salesperson + country + product performance scorecard

Purpose: Identify the strongest combinations of people + markets +
products + time + operational volume.

💡 Key Business Insights

1. Strong Overall Sales Base

The dataset contains 1,094 transactions generating approximately
$6,183,625 in revenue from 177,007 boxes.

The average transaction generates approximately $5,652, while the
average transaction ships around 161.8 boxes.

The overall revenue generated per shipped box is approximately $35.

Business interpretation: The dataset provides enough transactional
detail to evaluate both revenue generation and shipment activity.

2. Australia Is the Largest Revenue Market

Australia is the highest-revenue country with approximately
$1,137,367, representing 18.4% of total revenue.

The next three markets are:

Rank Country             Revenue   Revenue Share

   1 Australia       \$1,137,367           18.4%
   2 UK              \$1,051,792           17.0%
   3 India           \$1,045,800           16.9%
   4 USA             \$1,035,349           16.7%
   5 Canada            \$962,899           15.6%
   6 New Zealand       \$950,418           15.4%

Business interpretation: Revenue is relatively well distributed
across the six countries rather than being dominated by a single market.
This reduces concentration risk but also creates opportunities to
benchmark market-level productivity.

3. Ches Bonnell Is the Top Revenue-Generating Salesperson

The highest-revenue salesperson is Ches Bonnell, generating
approximately $320,901 across 48 transactions.

Other high-performing salespeople include:

Oby Sorrel

Madelene Upcott

Brien Boise

Kelci Walkden

Business interpretation: These salespeople can be studied for
repeatable practices, product mix, customer/market coverage, and
transaction size.

4. Smooth Sliky Salty Is the Top Product by Revenue

The leading product by total revenue is Smooth Sliky Salty,
generating approximately $349,692.

The leading products by revenue include:

Rank Product                   Revenue   Transactions

   1 Smooth Sliky Salty      \$349,692             59
   2 50% Dark Bites          \$341,712             60
   3 White Choc              \$329,147             58
   4 Peanut Butter Cubes     \$324,842             49
   5 Eclairs                 \$312,445             60

Business interpretation: Product ranking should not be judged only
by revenue. The SQL project therefore also evaluates boxes shipped,
average transaction value, market reach, and revenue per box.

5. Revenue Peaks in January

The strongest month by revenue is Month 1, with approximately
$896,105.

Monthly revenue:

Month     Revenue   Transactions    Boxes

    1   \$896,105            154   27,535
    2   \$699,377            110   18,015
    3   \$749,483            131   19,561
    4   \$674,051            118   21,003
    5   \$752,892            135   21,856
    6   \$865,144            163   26,260
    7   \$803,425            149   22,876
    8   \$743,148            134   19,901

Business interpretation: Monthly analysis can support sales
planning, inventory allocation, campaign timing, and capacity planning.

6. Q1 Is the Strongest Quarter

Quarter       Revenue

     Q1   \$2,344,965
     Q2   \$2,292,087
     Q3   \$1,546,573

Business interpretation: Q1 generated the highest quarterly revenue.
Seasonal patterns should be validated with a longer historical period
before making major forecasting decisions.

7. Most Transactions Are Below $5K

The transaction-value distribution is:

Revenue Band     Transactions   Share

Below 5K                  558   51.0%
5K-10K                    371   33.9%
10K-15K                   132   12.1%
15K+                       33    3.0%

Business interpretation: The large majority of transactions are
below $5K. This suggests that improving transaction frequency,
upselling, cross-selling, or selectively increasing order size could
have a meaningful impact on total revenue.

8. Shipment Volume Is Concentrated in Medium-Sized Orders

Shipment Band     Transactions   Share

Below 100                  409   37.4%
100-249                    452   41.3%
250-399                    169   15.4%
400+                        64    5.9%

The 100--249 box band is the largest category.

Business interpretation: Medium-volume transactions represent an
important operational segment and can be targeted for conversion into
higher-volume orders.

9. Revenue and Boxes Shipped Should Not Be Treated as the Same KPI

The Pearson correlation between Amount and Boxes Shipped in this
dataset is approximately -0.019, indicating a very weak linear
relationship.

Business interpretation: A transaction shipping more boxes does not
automatically imply proportionally higher revenue. Management should
therefore evaluate:

Revenue per box

Average transaction value

Product mix

Country mix

Salesperson mix

rather than relying only on shipment volume.

10. Almond Choco Has the Highest Revenue Efficiency per Box

Based on the available transactions, Almond Choco has the highest
aggregate revenue per shipped box at approximately $41 per box.

This is different from the highest-revenue product.

Business interpretation: A product can be strategically valuable
because of revenue efficiency, even when it is not the absolute
leader in total revenue.

🏆 Portfolio-Level Takeaways

Revenue

Total revenue: $6,183,625

Average transaction value: $5,652

Revenue per box: $35

Sales Team

Ches Bonnell is the top salesperson by revenue.

Salesperson performance varies considerably, creating opportunities
for performance benchmarking.

Average transaction value and revenue per box provide additional
ways to assess salesperson effectiveness.

Markets

Australia is the leading country by revenue.

Revenue is spread relatively evenly across the six countries.

Country-level analysis supports market-specific sales strategies.

Products

Smooth Sliky Salty is the leading product by total revenue.

Product leaders differ when measured by revenue efficiency.

Product-country analysis helps identify localized winners.

Time

January is the strongest month in this dataset.

Q1 is the strongest quarter.

Monthly and country-level MoM analysis provides a foundation for
seasonality and growth monitoring.

Operational Volume

Most transactions are below $5K.

The 100--249 box shipment segment is the largest.

Revenue and shipment volume have a weak linear relationship,
reinforcing the need for efficiency KPIs.

🎯 Business Recommendations

1. Benchmark Top Salespeople

Study the practices of high-performing salespeople such as Ches
Bonnell and compare:

Product mix

Countries served

Average transaction value

Revenue per box

Transaction frequency

The goal should be to identify repeatable sales behaviors, not
simply reward absolute revenue.

2. Protect and Expand High-Performing Markets

Australia leads revenue, but no country contributes an overwhelming
share.

This provides a strong opportunity to:

Replicate successful strategies across markets

Identify underperforming salesperson-market combinations

Improve market-specific product mixes

3. Separate Revenue Growth from Volume Growth

Because revenue and boxes shipped show a weak linear relationship,
management should track:

Revenue → Revenue per Box → Average Transaction Value → Boxes
Shipped

rather than using shipment volume as a proxy for financial performance.

4. Focus on Small-to-Medium Transactions

Since most transactions fall below $5K, potential growth levers
include:

Upselling

Cross-selling

Product bundles

Volume incentives

Tiered pricing

Minimum-order promotions

5. Use Product-Market Combinations for Decision Making

A product that performs well globally may not perform equally well in
every country.

The multivariate SQL analysis can identify:

Which product + country combinations generate the strongest revenue
and revenue efficiency?

This is more actionable than a simple global product ranking.

6. Monitor Revenue Efficiency

Revenue per box should be used alongside total revenue.

High revenue with very high shipment volume can indicate a different
business opportunity from moderate revenue generated with exceptional
revenue efficiency.

🧠 SQL Skills Demonstrated

This project demonstrates practical SQL analytics skills including:

SELECT

WHERE

GROUP BY

ORDER BY

Aggregate functions: SUM, AVG, COUNT, MIN, MAX

COUNT(DISTINCT ...)

CASE WHEN

Common Table Expressions (WITH)

Window functions

ROW_NUMBER()

LAG()

PARTITION BY

DATEPART()

MONTH()

Revenue contribution calculations

Ranking within groups

Ratio calculations

Revenue-per-box analysis

Transaction-band segmentation

Multi-dimensional performance analysis

🛠️ SQL Execution Notes

The SQL file is written primarily with Microsoft SQL Server / T-SQL
syntax.

Example table:

CREATE TABLE ChocSales (
    Sales_Person VARCHAR(100),
    Country VARCHAR(50),
    Product VARCHAR(100),
    Date DATE,
    Amount INT,
    Boxes_Shipped INT
);

After loading the Excel data into SQL Server, the main table referenced
by the analysis is:

ChocSales

Recommended execution environment

Microsoft SQL Server

SQL Server Management Studio (SSMS)

Azure Data Studio

⚠️ Important SQL Improvements for Production Use

The current SQL file is strong as a learning/portfolio analysis, but a
production-ready version should consider the following improvements:

1. Use a consistent table reference

One query references:

[DB1].[dbo].[ChocSales]

while most queries use:

ChocSales

For portability, use one consistent table reference.

2. Avoid MONTH(Date) alone for long-term datasets

Grouping only by month number can combine January across multiple years.

For production reporting, use:

YEAR(Date),
MONTH(Date)

or a proper calendar/date dimension.

3. Protect percentage calculations

MoM growth should handle a zero previous-month value:

NULLIF(Previous_Month_Revenue, 0)

4. Handle ties when ranking

Some analyses use ROW_NUMBER(). If tied rankings should share the same
rank, consider:

RANK()

or:

DENSE_RANK()

5. Standardize naming

The source data uses names such as:

Sales Person
Boxes Shipped

while SQL uses:

Sales_Person
Boxes_Shipped

A production dataset would benefit from consistent naming conventions.

📈 Suggested GitHub Project Structure

chocolate-sales-sql-analysis/
│
├── README.md
│
├── SQL QUERY.sql
│
├── Choc Sales_Dataset.xlsx
│
└── screenshots/
    ├── kpi-results.png
    ├── country-analysis.png
    ├── product-analysis.png
    └── salesperson-analysis.png

If you later add a Power BI/Tableau dashboard, a recommended structure
is:

chocolate-sales-sql-analysis/
│
├── README.md
├── SQL QUERY.sql
├── Choc Sales_Dataset.xlsx
│
├── dashboard/
│   └── chocolate-sales-dashboard.pbix
│
├── screenshots/
│   ├── executive-overview.png
│   ├── salesperson-performance.png
│   ├── country-performance.png
│   └── product-performance.png
│
└── docs/
    └── data-dictionary.md

🚀 Future Enhancements

To take this project from a SQL analysis project to a stronger portfolio
project, the next logical enhancements are:

Build an executive sales dashboard

Add KPI cards for revenue, transactions, boxes, and revenue per box

Add salesperson leaderboard

Add country performance map

Add product performance matrix

Add monthly revenue trend

Add MoM growth %

Add product-country heatmap

Add salesperson productivity matrix

Add revenue-per-box analysis

Add dynamic date filters

Add customer-level data if available

Add profit/margin data if available

Build a forecasting layer with a longer historical dataset

👔 Business Questions Answered

This project can answer questions such as:

How much revenue has the company generated?

How many boxes have been shipped?

What is the average transaction value?

Which salesperson generates the most revenue?

Which country is the strongest market?

Which product generates the most revenue?

Which products are most efficient per box?

Which countries have the highest shipment volume?

Which salesperson serves the most markets?

Which salesperson sells the widest product range?

Which products have the widest market reach?

Which month generates the highest revenue?

Which quarter performs best?

What is the distribution of transaction values?

What is the distribution of shipment volumes?

Who is the top salesperson in each country?

What is the top product in each country?

Which salesperson-product combinations generate the most revenue?

Which country-product combinations have the highest revenue
efficiency?

How does revenue change month over month?

Which salesperson-country combinations have the strongest
productivity?

Which salesperson-country-product combinations are strongest
overall?

🏁 Final Conclusion

This project demonstrates a complete SQL-based sales analytics
workflow rather than a collection of isolated queries.

The analysis progresses from:

Raw Transactions → KPIs → Univariate Analysis → Bivariate Analysis →
Multivariate Analysis → Business Insights → Recommendations

The strongest overall finding is that sales performance should be
evaluated from multiple perspectives. Revenue alone is not enough. A
professional sales-performance framework should combine:

Revenue + Transactions + Boxes + Average Transaction Value + Revenue
per Box + Product Mix + Country Mix + Salesperson Performance + Time
Trends

This makes the project suitable as a portfolio demonstration of SQL
querying, analytical thinking, KPI design, business interpretation, and
data-driven decision making.

📌 Project Status

Status: ✅ Completed SQL Analytics Project

Primary Tool: SQL Server / T-SQL

Analysis Level: KPI → Univariate → Bivariate → Multivariate

Business Perspective: Sales Performance & Revenue Optimization

End Consumer: Sales Manager

Dataset Records: 1,094

Countries: 6

Products: 22

Salespeople: 25

