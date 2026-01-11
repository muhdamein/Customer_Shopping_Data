# Customer_Shopping_Data
Customer Shopping Behavior Analysis

Author: Muhd Amein
Year: 2025

🔍 Project Overview

This project analyzes customer shopping behavior using transactional retail data covering 3,900 purchases across multiple product categories. The objective is to extract actionable insights related to customer demographics, purchasing habits, discount usage, product performance, and subscription trends, supporting data-driven business decisions.

The project demonstrates a full data analytics workflow, from data cleaning and feature engineering to SQL-based analysis and interactive dashboarding.

📊 Dataset Summary
Total Records: 3,900
Total Columns: 18

Key Features:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

Data Quality:
37 missing values in the review_rating column (handled during data cleaning)
🐍 Exploratory Data Analysis (Python – Jupyter Notebook)

The data preparation and exploration phase was performed using Python (pandas, NumPy):
Loaded and inspected dataset structure and summary statistics
Handled missing values by imputing median review ratings per product category
Standardized column names to snake_case

Performed feature engineering:
Created age_group to segment customers by age
Derived purchase_frequency_days from purchase history
Identified redundant features (promo_code_used) and removed them
Loaded the cleaned dataset into PostgreSQL for advanced SQL analysis

🗄️ Data Analysis with SQL (PostgreSQL – pgAdmin 4)
Business-driven SQL queries were used to answer key analytical questions, including:
Revenue comparison by gender
High-spending customers despite discount usage
Top-rated products by average review score
Impact of shipping type on purchase value
Spending behavior of subscribers vs non-subscribers
Products most dependent on discounts
Customer segmentation (New, Returning, Loyal)
Top-performing products per category
Subscription likelihood among repeat buyers
Revenue contribution by age group

📈 Data Visualization (Power BI Dashboard)
An interactive Power BI dashboard was built to visualize:
Revenue trends
Customer segments
Product performance
Discount and subscription behavior

The dashboard enables stakeholders to explore insights dynamically and supports business decision-making.

🛠️ Tools & Technologies
Python: pandas, NumPy, Jupyter Notebook
Database: PostgreSQL, pgAdmin 4
Visualization: Power BI

Skills Demonstrated: Data Cleaning, EDA, Feature Engineering, SQL Analytics, Dashboard Design
