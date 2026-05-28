# Retail Sales Data Agent on Databricks

## Project Overview
This project was completed as a university assignment to build a working **Data Agent** on Databricks. The agent answers natural-language questions about a retail sales dataset – covering revenue, product performance, customer demographics, and sales trends – without requiring manual SQL queries.

## Objective
To design, instruct, and test a Data Agent that helps a shop manager or business owner quickly understand sales performance, customer spending patterns, and product insights using only plain English.

## Dataset
The dataset (`retail_sales_dataset.csv`) contains **1,000 retail transactions** with the following columns:
- Transaction ID, Date, Customer ID, Gender, Age
- Product Category (Beauty, Clothing, Electronics)
- Quantity, Price per Unit, Total Amount

The table is named `retail_sales_data` in Databricks.

## Tools Used
- **Databricks** (Unity Catalog, SQL Agent)
- **SQL** (for manual validation)
- **GitHub** (for submission)

## Key Insights from the Agent
- **Total revenue** across all transactions: R456,000
- **Best month for sales**: December
- **Top product category** by revenue: Electronics
- **Highest volume category** (units sold): Clothing
- **Gender spending**: Female customers spend more than male customers
- **Highest average transaction value**: Age group 31–45

## Business Recommendations
1. Increase marketing and stock for **Electronics** in November–December.
2. Target **females aged 31–45** with personalised promotions.
3. Bundle Electronics with lower‑performing categories (Beauty, Clothing) to lift cross‑sales.
4. Run limited discounts on slower categories to clear inventory.

## Sample Questions the Agent Can Answer
- What is the total revenue across all transactions?
- Which month had the highest total sales?
- Which product category generated the most revenue?
- How many units were sold in each product category?
- How does spending compare between male and female customers?
- Which age group spends the most per transaction?

## Validation
Three answers were independently validated by writing SQL queries (`SUM`, `GROUP BY`) directly against the Databricks table. All three matched the agent's responses, confirming accuracy.

## Repository Contents
- `Building_A_Retail_Sales_Data_Agent.docx` – Full project report with screenshots, instructions, 10 questions, and validations.
- `retail_sales_dataset.csv` – Original dataset (1,000 rows).
- `README.md` – This file.

## Conclusion
Building this Data Agent demonstrated that clear agent instructions – especially exclusion rules and honesty handling – are critical for trustworthy answers. The agent successfully answered ten business questions, and manual validation proved its reliability. This project shows how non‑technical users can access data insights instantly using a well‑instructed AI agent.

