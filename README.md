# Swiggy SQL Analysis

A SQL-based exploratory analysis of restaurant and menu data from the **Swiggy** dataset. This project answers practical business questions such as identifying high-rated restaurants, top cities, cuisine trends, pricing patterns, and vegetarian/non-vegetarian distribution.

---

## 📌 Project Overview

This project demonstrates how SQL can be used to extract meaningful insights from restaurant data. It includes queries for ranking restaurants, grouping by city and cuisine, comparing prices, and filtering records based on menu categories and dietary preferences.

---

## 🗂️ Dataset

**Table Used:** `swiggy_1`

The dataset appears to contain restaurant-level and menu-level details such as:

* `restaurant_name`
* `city`
* `rating`
* `cuisine`
* `menu_category`
* `item`
* `price`
* `cost_per_person`
* `veg_or_nonveg`

> Note: The exact schema may vary depending on the source of the dataset.

---

## 🎯 Objectives

The main goal of this analysis is to answer common business questions like:

* Which restaurants are highly rated?
* Which city has the most restaurants?
* What is the most common cuisine?
* Which restaurants are the most expensive?
* Which restaurants offer the highest number of categories or items?

---

## ✅ SQL Questions Covered

### 1. Restaurants with rating greater than 4.5

Finds the number of distinct restaurants with a rating above 4.5.

### 2. City with the highest number of restaurants

Identifies the top city based on restaurant count.

### 3. Restaurants containing the word “Pizza” in their name

Counts restaurants whose names include the keyword Pizza.

### 4. Most common cuisine

Finds the cuisine that appears most frequently in the dataset.

### 5. Average rating in each city

Calculates the average restaurant rating city-wise.

### 6. Highest priced item in the “Recommended” category for each restaurant

Shows the maximum item price under the Recommended menu category.

### 7. Top 5 most expensive non-Indian restaurants

Lists the costliest restaurants that serve cuisines other than Indian.

### 8. Restaurants costing above the overall average

Retrieves restaurants whose average cost per person is above the dataset average.

### 9. Restaurants with the same name in different cities

Finds restaurant names that exist in multiple cities.

### 10. Restaurant with the most items in the “Main Course” category

Identifies the restaurant offering the highest number of main course items.

### 11. Fully vegetarian restaurants

Lists restaurants that serve only vegetarian food.

### 12. Restaurant with the lowest average item price

Finds the restaurant with the cheapest average menu pricing.

### 13. Top 5 restaurants with the highest number of categories

Ranks restaurants by the number of distinct menu categories.

### 14. Restaurant with the highest percentage of non-vegetarian food

Finds the restaurant with the largest share of non-veg items.

---

## 🧠 Key SQL Concepts Used

This project includes the use of:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `LIMIT`
* `DISTINCT`
* Aggregate functions like `COUNT()`, `AVG()`, and `MAX()`
* Pattern matching with `LIKE`
* Self-joins
* Subqueries
* `CASE WHEN` conditions

---

## 📊 Insights You Can Derive

Using these queries, you can understand:

* Which locations have the strongest restaurant presence
* Which cuisines are most popular
* Which restaurants are premium-priced
* How vegetarian and non-vegetarian offerings are distributed
* Which restaurants dominate in variety and menu depth

---

## 🚀 How to Run

1. Create the database:

```sql
CREATE DATABASE swiggy;
```

2. Select the database:

```sql
USE swiggy;
```

3. Run the provided SQL queries on table `swiggy_1`.

---

## 📁 Project Structure

```bash
swiggy-sql-analysis/
├── README.md
└── queries.sql
```

---

## ✨ Sample Use Case

This project can be used to practice:

* SQL interview questions
* Data analysis using SQL
* Restaurant and food delivery analytics
* Portfolio projects for GitHub

---

## 📝 Notes

* Some queries use `DISTINCT` because the same restaurant may appear multiple times due to multiple items.
* A few queries may need small corrections depending on the exact table schema and SQL dialect.
* Make sure column names match your dataset before execution.

---

## 👤 Author

Prepared for SQL practice and restaurant data analysis.

---

## ⭐ If you like this project

You can star the repository and use these queries as a template for other dataset analyses.
