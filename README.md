# Customer-Behavior-Analysis
This project focuses on analyzing customer shopping behavior using transactional data to uncover meaningful business insights. The end-to-end workflow includes data loading, exploratory data analysis (EDA), data cleaning, SQL-based analysis using PostgreSQL, and visualization through Power BI, in a detailed report and presentation.
The objective is to understand customer demographics, purchasing patterns, product performance, and subscription behavior to support data-driven business decisions.

__🗂️ Dataset Description__


Total Records: 3,900 transactions

Total Features: 18 columns

Key Data Categories
Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discounts, Promo Codes, Previous Purchases, Purchase Frequency, Review Ratings, Shipping Type

__🛠️ Tools & Technologies Used__


Python: pandas, numpy, matplotlib, seaborn

Database: PostgreSQL

SQL: Business analysis queries

Visualization: Power BI

Documentation: Report (PDF/Word)

Presentation: PowerPoint

__🐍 Python Analysis (EDA & Data Cleaning)__


The initial analysis and preprocessing were performed using Python:

Loaded the dataset using pandas

Conducted exploratory data analysis using .info(), .describe(), and visualizations

Identified and handled missing values in review ratings

Standardized column names for consistency

Performed feature engineering:

Created age groups

Derived purchase frequency metrics

Validated data consistency and removed redundant columns

Exported the cleaned dataset to PostgreSQL for further analysis

__🗄️ SQL Analysis (PostgreSQL)__


After loading the cleaned data into a PostgreSQL database, multiple business-focused SQL queries were executed, including:

Revenue comparison by gender

Subscriber vs non-subscriber spending behavior

High-spending customers who used discounts

Top-rated and most-purchased products

Shipping type impact on purchase value

Customer segmentation (New, Returning, Loyal)

Revenue contribution by age group

Discount dependency analysis by product

__📈 Power BI Dashboard__


An interactive Power BI dashboard was created to visualize key insights:

Revenue and spending trends

Customer segmentation

Product and category performance

Subscription and discount analysis

The dashboard allows stakeholders to filter and explore data dynamically.

__💡 Key Business Insights__


Subscribers contribute higher average revenue than non-subscribers

Loyal customers drive a significant portion of total sales

Certain products rely heavily on discounts

Specific age groups and shipping types generate higher revenue










