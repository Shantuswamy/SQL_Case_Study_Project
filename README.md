# SQL_Case_Study_Project
SQL Case Study - Sales and Profit Analysis

📌 Overview

As a Database Administrator, the goal of this project is to analyze sales and profit data across different states, considering various factors such as marketing expenses, COGS (Cost of Goods Sold), and budgeted vs. actual performance. The insights derived from this analysis will help in identifying the most profitable products and understanding sales trends to optimize business strategies.

📊 Dataset Details

The dataset consists of three key tables:

1️⃣ FactTable (4,200 rows, 14 columns)

This table contains key financial and sales-related metrics:

Date – Transaction date

ProductID – Unique identifier for each product

Profit – Actual profit generated

Sales – Actual sales revenue

Margin – Profit margin percentage

COGS – Cost of Goods Sold

Total Expenses – Total operational expenses

Marketing – Marketing costs

Inventory – Stock availability

Budget Profit – Projected profit

Budget COGS – Projected cost of goods sold

Budget Margin – Projected margin percentage

Budget Sales – Estimated sales revenue

Area Code – Geographical location reference

2️⃣ ProductTable (13 rows, 4 columns)

This table provides product-specific details:

Product Type – Category of the product

Product – Product name

ProductID – Unique identifier (joins with FactTable)

Type – Sub-category of the product

3️⃣ LocationTable (156 rows, 4 columns)

This table contains geographical insights:

Area Code – Unique location identifier (joins with FactTable)

State – Name of the state

Market – Market category (e.g., regional, local, national)

Market Size – Size classification of the market

🛠 SQL Queries Used

To extract insights, the following queries were written:

✔️ Total Sales and Profit by State – Identifies which states generate the most revenue and profit.✔️ Top 5 Best-Selling Products – Determines the highest-selling products.✔️ Marketing Spend vs. Sales Performance – Analyzes how marketing expenses impact sales.✔️ COGS vs. Profitability Analysis – Finds cost-effective products with high margins.✔️ Budget vs. Actual Performance – Compares projected vs. actual sales and profit.

📌 How to Run the Queries

Load the datasets into a SQL database (MySQL, PostgreSQL, or SQL Server).

Use queries.sql to execute the SQL statements.

Analyze the output to identify sales trends and insights.



🔥 Key Insights & Business Impact

Most Profitable States – Helps in region-based marketing and stock allocation.

High-Demand Products – Optimizes inventory management and promotions.

Marketing ROI – Assesses if marketing investments are generating revenue.

Budget Accuracy – Identifies discrepancies between expected and actual performance.

🚀 Future Enhancements

Integrate Power BI to create interactive dashboards.

Use Python for Advanced Analytics, like predictive modeling.

Optimize SQL Queries for better efficiency on large datasets.

🏆 Contributing & Feedback

Feel free to contribute by adding new queries, improving the analysis, or providing feedback.

📩 Contact

For any queries or suggestions, reach out at [shantuswamy011@gmail.com] or connect via [[LinkedIn Profile](https://www.linkedin.com/in/shanthkumar-swamy-94a014316/)].

