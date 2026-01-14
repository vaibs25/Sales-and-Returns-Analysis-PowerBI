# Sales-and-Returns-Analysis-PowerBI

📊 Power BI Advanced Visuals – Sales & Returns Analysis
📌 Project Overview

This project focuses on building advanced Power BI visuals to analyze sales performance, profitability, customer behavior, and returns.
The goal is to practice data transformation, modeling, DAX measures, and advanced visual analytics using real-world business scenarios.

The report demonstrates the use of:

Key Influencers

Maps

Decomposition Trees

Ribbon Charts

Waterfall Charts

Funnel Charts

Combo Charts

🎯 Objectives

Prepare and model data correctly for advanced Power BI visuals

Create calculated columns and measures

Analyze sales, profit/loss, returns, and customer funnel behavior

Build a multi-page Power BI report with professional formatting

🛠️ Tools & Technologies

Power BI Desktop

Power Query – Data transformation

DAX – Calculated columns & measures

GitHub – Version control & documentation

📂 Data Loading & Modeling
🔹 Data Sources

Sales_Transactions

Customer_Info

🔗 Relationships

Sales_Transactions → Customer_Info

Relationship: Many-to-One

Key: Customer ID

🔄 Data Type Validation
🧾 Text Columns

Customer ID

Gender

Country

State

Funnel Stage

Product Category

Product Name

Sales Channel

Campaign Source

Return Flag

Return Reason

🔢 Whole Number

Age

Units Sold

Discount (%)

📅 Date

Date

💰 Currency

Unit Price

Cost Price

➕ Calculated Columns
🧮 Sale Price
Sale Price =
(Unit Price * (1 - Discount (%) / 100)) * Units Sold

💹 Profit / Loss
Profit/Loss =
Sale Price - (Cost Price * Units Sold)


Both fields are set to Currency data type

📊 Report Pages & Visuals
📄 Page 1 – Key Influencers

Visual: Key Influencers

Analyze: Return Flag

Explain By:

Sales Channel

Product Category

Country

Discount (%)

Purpose: Identify factors influencing product returns

📄 Page 2 – Map

Visual: Map

Location: State

Legend: Country

Bubble Size: Sum of Sale Price

Tooltips: Sum of Units Sold

Title: Sales across Countries

Purpose: Geographic sales distribution

📄 Page 3 – Decomposition Tree (Sales)

Analyze: Sum of Sale Price

Explain By:

Sales Channel

Product Category

Country

State

Campaign Source

Purpose: Drill-down sales performance drivers

📄 Page 4 – Decomposition Tree (Profit/Loss)

Analyze: Sum of Profit/Loss

Explain By:

Sales Channel

Product Category

Country

State

Campaign Source

Purpose: Identify profitability contributors

📄 Page 5 – Ribbon Chart

X-Axis: Date (Year, Quarter)

Y-Axis: Sum of Sale Price

Legend: Product Category

Small Multiples: Return Flag

Title: Sales and Returns against Product Category Trend

Purpose: Category ranking changes over time

📄 Page 6 – Waterfall Chart

Category: Product Category

Y-Axis: Sum of Profit/Loss

Title: Profit/Loss by Product Category

Purpose: Contribution of each category to profit/loss

📄 Page 7 – Funnel Chart

Category: Funnel Stage

Values: Customer ID

Title: Customers by Funnel Stage

Purpose: Customer drop-off analysis across funnel stages

📄 Page 8 – Combo Chart (Sales & Profit)

Visual: Line & Stacked Column Chart

X-Axis: Date (Year, Quarter)

Column Y-Axis: Sum of Sale Price

Line Y-Axis: Sum of Profit/Loss

Column Legend: Country

Title: Sales and Profit Margin Trend

Purpose: Compare revenue vs profitability trends

📄 Page 9 – Combo Chart (Units & Returns)

Visual: Line & Clustered Column Chart

X-Axis: Date (Year, Quarter)

Column Y-Axis: Sum of Units Sold

Line Y-Axis: Count of Returns

Column Legend: Product Category

Small Multiples: Country

Page Filter: Return Flag = "Returned"

Title: Units Sold and Returns Trend

Purpose: Analyze returns relative to sales volume

🎨 Formatting Standards

Visual Border: On

Alignment: Centered on Page

Consistent titles and layout across all pages

Professional report structure

📁 Project Files

📊 Advanced_Visuals_PowerBI.pbix – Power BI report

📄 README.md – Project documentation

🧠 Skills Demonstrated

Power BI Data Modeling

Power Query Transformations

DAX Calculated Columns

Advanced Power BI Visuals

Business-driven analytical thinking

Professional dashboard design
