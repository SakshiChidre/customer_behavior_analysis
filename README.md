# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using Python and Pandas. The objective is to explore customer demographics, purchasing patterns, product preferences, reviews, subscriptions, discounts, and purchase frequency.

The project includes data loading, exploratory data analysis (EDA), data cleaning, and feature engineering. The cleaned dataset is prepared for further analysis using SQL and visualization tools such as Power BI.

---

## Dataset

The dataset used in this project is:

`customer_shopping_behavior.csv`

It contains **3,900 customer records** and information related to customer demographics and shopping behavior.

### Main Features

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

---

## Project Objectives

The main objectives of this project are:

- Understand the structure and characteristics of the customer shopping dataset.
- Perform exploratory data analysis.
- Identify and handle missing values.
- Clean and standardize column names.
- Create useful features for customer analysis.
- Prepare the dataset for SQL-based analysis.
- Prepare data for visualization and dashboard development.

---

## Technologies Used

### Programming

- Python

### Libraries

- Pandas

### Database Preparation

- PostgreSQL
- SQLAlchemy
- psycopg2

### Visualization

- Power BI *(planned for dashboard development)*

---

## Project Workflow

### 1. Data Loading

The dataset is loaded into a Pandas DataFrame.

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
