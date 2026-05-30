# Store-Analysis-Using-Excel-Using-Pivot-Tables-and-Pivot-Charts-
A complete data analytics project covering data cleaning in Python, business analysis using MYSQL, and an interactive dashboard built in Power BI, based on a retail sales dataset of 1,250 orders across 8 Indian cities

## 🛠️ Tools & Technologies
Python | MYSQL | Power BI | Excel 

## Project Overview
This project simulates a real-world retail business scenario where a sales manager needs visibility into revenue performance, regional trends, product profitability, and sales team effectiveness. The goal was to go from a raw, messy dataset all the way to a business-ready dashboard.

##  📁 Dataset Description
- **Source** - Synthetically generated retail sales data
- **Size** - 1,250 rows × 16 columns (after cleaning)
- **Columns** -  order_id, order_date, product, category, city, region, sales_rep, customer_segment, quantity, unit_price, discount, revenue, cost, profit, payment_mode
- **Time Period** - January 2023 to December 2023

##  🧹 Data Quality Issues Found and Fixed

-  Removed **~80** duplicate rows based on order_id
- Handled **~40** blank/null values in columns like city, sales_rep, payment_mode
- Standardized category name inconsistencies — fixed typos like **"Electronisc", "Stationary", inconsistent casing**
- Removed **~20** rows with invalid quantity values (zero or negative)
-  Dropped **~15** rows with future dates (year 2025 — clear data entry errors)

##  🔍 SQL Business Analysis 
After cleaning, the data was imported into MySQL and 12 business questions were answered through SQL queries — ranging from basic aggregations to window functions and CTEs.
### Questions - 
- Q1. Give me the total revenue and total profit we generated in the entire year. Also show me the overall profit margin %.
- Q2. How many orders did each sales rep close? Rank them from highest to lowest. I want to know who's pulling their weight.
- Q3. Which product brought in the most revenue? Show me the top 5.
- Q4. Break down total revenue by region. Which region is our strongest market?
- Q5. Which city has the highest average order value (revenue per order)? Show top 5 cities.
- Q6. What is the total revenue and profit by customer segment (Retail, Corporate, SMB)? Which segment is most profitable?
- Q7. Show me revenue by category for each region. I want a breakdown — which category sells best in which region?
- Q8. How much discount are we giving out vs what we're earning? Show total discount amount, total revenue, and discount as % of gross revenue — grouped by product category.
- Q9. Give me the top 3 sales reps in each region based on total revenue. Use window functions.
- Q10. Which products have a profit margin below 15%? List them with their avg selling price, avg cost, and margin %.
-  Q11. Find all sales reps who have sold in at least 4 different cities. These are our most versatile reps.
- Q12. What % of our orders used UPI vs Credit Card vs Cash? Show payment mode distribution as % of total orders.
##  💡 Key Business Insights
- **Quarter-4** was the strongest quarter, generating **₹24M** in revenue which was **31%** of the annual total
- **Arjun Nair** was the top performing sales rep with **₹9.3M** in revenue
- **Electronics** dominates, contributing **84.9%** of total revenue
-  **South** region led all regions in total revenue
- **December** was the single highest revenue month at **₹10.1M**
- Overall profit margin stood at **17.90%**, with Furniture being the lowest margin category

##  📊 Dashboard Preview

![Dashboard Page](https://github.com/bhavyasanoria01-lab/Retail-Sales-Analysis/blob/main/Dashboard%20Page%201.png)


##  📝 Learnings & Challenges
This was my first end-to-end analytics project. The biggest challenge was handling the date column during Python cleaning which required regenerating clean dates before the Power BI dashboard could be completed. I also learned the importance of reading business questions carefully because a few SQL queries initially 
