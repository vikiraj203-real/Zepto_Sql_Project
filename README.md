# Zepto_Sql_Project
📌 Project Overview
The goal is to simulate how actual data analysts in the e-commerce or retail industries work behind the scenes to use SQL to:

✅ Set up a messy, real-world e-commerce inventory database

✅ Perform Exploratory Data Analysis (EDA) to explore product categories, availability, and pricing inconsistencies

✅ Implement Data Cleaning to handle null values, remove invalid entries, and convert pricing from paise to rupees

✅ Write business-driven SQL queries to derive insights around pricing, inventory, stock availability, revenue and more

**Data Exploration**
Counted the total number of records in the dataset

Viewed a sample of the dataset to understand structure and content

Checked for null values across all columns

Identified distinct product categories available in the dataset

Compared in-stock vs out-of-stock product counts

Detected products present multiple times, representing different SKUs

**🧹 Data Cleaning**
Identified and removed rows where MRP or discounted selling price was zero

Converted mrp and discountedSellingPrice from paise to rupees for consistency and readability

 **📊 Business Insights**
Found top 10 best-value products based on discount percentage

Identified high-MRP products that are currently out of stock

Estimated potential revenue for each product category

Filtered expensive products (MRP > ₹500) with minimal discount

Ranked top 5 categories offering highest average discounts

Calculated price per gram to identify value-for-money products

Grouped products based on weight into Low, Medium, and Bulk categories

Measured total inventory weight per product category9
