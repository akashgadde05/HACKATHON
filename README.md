Food Delivery Analysis
Overview

This project analyzes food orders from multiple datasets including orders, users, and restaurant details. The goal is to extract insights such as revenue by city, cuisine performance, Gold member activity, and restaurant ratings.

The analysis was performed using Python and Pandas in a Jupyter Notebook.

Datasets

orders.csv – Contains order details:

order_id, user_id, restaurant_id, order_date, total_amount, restaurant_name

users.json – Contains user information:

user_id, name, city, membership

restaurants.sql – Contains restaurant information:

restaurant_id, restaurant_name, cuisine, rating

Steps Performed

Loaded all datasets into Pandas and SQLite (for SQL file).

Merged datasets into a single merged_df containing all relevant columns.

Cleaned data:

Converted total_amount to numeric

Handled missing values

Analysis performed includes:

Revenue by city and membership

Average order value (AOV) for Gold members

Total orders and revenue per restaurant

Revenue by cuisine and restaurant rating

Orders in top revenue cities

Restaurants with highest AOV (< 20 orders)

Quarter-wise revenue and trends