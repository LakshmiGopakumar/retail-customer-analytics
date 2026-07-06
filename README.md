**Retail Customer Analytics**

This is my end‑to‑end retail analytics project where I cleaned the data, merged multiple datasets, analysed everything using SQL, and built a Power BI dashboard. This project explores customer behaviour and sales patterns in a retail environment. The goal is to understand what drives purchases, how different customer groups behave, and which products or categories contribute most to overall performance.

I built this project to strengthen my data analysis skills and to show my ability to work with real datasets, SQL queries, and visualisation tools.


**Project Structure**

data/                - raw and cleaned CSV files  

notebooks/           - Python cleaning + merging  

sql/                 - all SQL queries  

powerbi/             - final dashboard  


**Project Overview**

The dataset includes customer details, purchase history, product information, and transaction patterns. I cleaned and prepared the data, explored trends, and created visual summaries that highlight key insights. The analysis focuses on:

Customer demographics

Spending behaviour

Product performance

Seasonal or category‑level trends

Patterns that could help improve marketing or inventory decisions

This project helped me strengthen my data cleaning, EDA, and visualization skills while working with a practical retail scenario.

**Data Preparation (Python)**

I cleaned and merged the customer, product, and order datasets.
During the cleaning process, I created additional columns such as:

age_group

month_name

is_high_margin

is_high_footfall

After processing everything, I exported the final dataset as final_dataset.csv.

**SQL Analysis (MySQL)**

I created a database called retail_analytics and imported the final dataset into MySQL. It is grouped into clear sections:

1. Monthly Trends

2. Category Insights

3. Store Insights

4. Customer Insights

5. Payment Insights

6. Product Insights

7. Margin & Footfall

8. Operational Insights

9. Advanced Insights


All SQL queries are saved in:
sql/05_SQL_Analysis.sql

**Power BI Dashboard**

My dashboard includes:

-Monthly revenue & profit

-Category performance

-Store comparison

-Customer age groups

-Payment method breakdown

-Top products

-Margin & footfall analysis

-Order status overview

Dashboard file:
powerbi/Retail_Analytics_Dashboard.pbix

**Tech Stack & Tools**

Python(Pandas, NumPy)

Matplotlib, Seaborn

Jupyter Notebook / VS Code

MySQL Workbench

Power BI

Git & GitHub 
