# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer purchasing behavior to identify patterns that improve sales performance, customer satisfaction, and retention. It focuses on how demographics, product categories, discounts, payment methods, and seasonal trends influence buying decisions.

---

## Dataset

* 3,900 records and 18 features
* Includes customer demographics, purchase details, product attributes, transaction data, and seasonal factors
* Missing values in `review_rating` handled using category-wise median imputation

---

## Tools and Technologies

* Python (Pandas) – Data cleaning and exploratory data analysis
* PostgreSQL – Data analysis using SQL
* Power BI – Data visualization and dashboard development

---

## Methodology

* Loaded and explored dataset using Pandas (`head`, `info`, `describe`)
* Cleaned data by handling missing values and standardizing column names
* Performed feature engineering (age groups and purchase frequency conversion)
* Integrated dataset with PostgreSQL using SQLAlchemy and psycopg2
* Executed SQL queries for analytical insights
* Built an interactive dashboard in Power BI
* Documented findings through report and presentation

---

## Dashboard

* Displays key KPIs: total customers, average purchase amount, and average review rating
* Provides revenue analysis by category, age group, and gender
* Includes interactive filters for subscription status, season, and category

---

## Results

* Male customers generate higher revenue
* Discounts are effective even for high-value customers
* Footwear and accessories show higher satisfaction
* Subscription status has limited impact on spending
* Express shipping customers spend slightly more
* Young adults contribute the highest revenue
* Credit cards generate the highest revenue
* Fall season performs best

---

## How to Run

* Clone the repository
* Run Python scripts for data cleaning and EDA
* Execute SQL queries in PostgreSQL
* Open the Power BI file to explore the dashboard

---

## Outcome

Demonstrates practical skills in data cleaning, SQL analysis, and dashboard development to generate actionable business insights.
