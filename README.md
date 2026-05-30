# 🛒 Store Sales Analysis — Excel Dashboard with Pivot Tables & Charts
A data analytics project covering data cleaning, business analysis and an interactive dashboard built in Excel, based on a sales dataset of around 31,000 rows.

## 🛠️ Tools & Technologies
Excel | Pivot Charts | Pivot Tables 

## Project Overview
This project analyses 31,000+ orders from an Indian e-commerce store to understand customer buying behaviour, top performing sales channels and regional demand patterns. The goal was to clean the raw data and build an interactive Excel dashboard using Pivot Tables and Pivot Charts that a store manager can use to make data driven decisions. This project focuses purely on Excel for data cleaning, pivot table analysis and an interactive dashboard without SQL or Python.

##  📁 Dataset Description
- **Source** - Kaggle 
- **Size** - 31,047 rows × 15 columns (after cleaning)
- **Columns** -  order_id, cust_id, gender, age, age category, date, status, channel, category, size, quantity, currency, amount, ship-state, B2B

##  🧹 Data Quality Issues Found and Fixed

-  Removed **5** columns that were not useful for analysis
- Sorted dates that were in different data types
- Removed **~20** rows with invalid quantity values

##  💡 Key Business Insights
- **Women** account for **65%** of total orders compared to 35% for men.
- The **Adults** age group is the most active buyers among the age groups.
- Highest orders are from **Amazon, Myntra and Flipkart**.
- **Maharashtra, Karnataka and UP** are the top 3 states by orders.

##  📊 Dashboard Preview

![Dashboard Page](https://github.com/bhavyasanoria01-lab/Store-Analysis-Using-Excel-Using-Pivot-Tables-and-Pivot-Charts-/blob/e568ac9714f9e0ee6b310f73d42326f2156beffd/Final%20Dashboard..png)


##  📝 Conclusion
The store should target women in the **Adult** age group from **Maharashtra, Karnataka and UP** by giving discount coupons and offers on **Amazon, Myntra and Flipkart**.

## 📝 Learnings & Challenges
The most valuable technical skill I learned in this project was working with Slicers in Excel and connecting them to multiple Pivot Charts simultaneously. Initially, each slicer was only controlling one chart. I later learned how to use the Report Connections feature in Excel to link a single slicer to all charts on the dashboard, making the entire dashboard interactive and dynamic. This taught me how a well connected dashboard should behave and one filter click should update every visual at once, not just one.

