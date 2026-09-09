# Pizza-Sales-Analysis---Python-

# 🍕 Pizza Sales Analysis – Exploratory Data Analysis

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA) of Pizza Sales data** to understand sales performance, customer ordering patterns, popular pizza categories and sizes, and the pizzas that contribute most to overall sales.

The analysis uses Python-based data analysis and visualization techniques to generate meaningful business insights from **48,620 sales records across 12 columns**.

## 🎯 Business Objectives

The main objectives of this project are to:

* Analyze overall pizza sales performance
* Calculate important business KPIs
* Identify the most popular pizza categories and sizes
* Find the top-selling pizzas
* Analyze sales and order trends by day, month, and hour
* Understand frequently used pizza ingredients
* Answer key business questions using data-driven insights

## 📊 Key Performance Indicators

The analysis calculated the following KPIs:

| KPI                         |          Result |
| --------------------------- | --------------: |
| 💰 Total Revenue            | **$817,860.05** |
| 🍕 Total Pizzas Sold        |      **49,574** |
| 🧾 Total Orders             |      **21,350** |
| 💵 Average Order Value      |      **$38.31** |
| 🍕 Average Pizzas per Order |        **2.32** |

These KPIs provide an overall view of the business's sales performance and customer ordering behavior.

## 🔍 EDA Performed

### 1. Dataset Exploration

* Loaded the pizza sales dataset using Pandas
* Examined dataset shape and structure
* Checked column names and data types
* Performed descriptive statistical analysis
* Reviewed numerical and categorical variables

The dataset contains **48,620 rows and 12 columns**, including order information, pizza details, pricing, quantity, size, category, ingredients, and pizza names.

### 2. Ingredient Analysis

Analyzed pizza ingredients by splitting and counting individual ingredients.

The most frequently occurring ingredients include:

* Garlic – 27,422
* Tomatoes – 26,601
* Red Onions – 19,547
* Red Peppers – 16,284
* Mozzarella Cheese – 10,333

### 3. Daily Sales Analysis

Analyzed the number of orders and revenue generated across different days of the week to understand daily ordering patterns.

### 4. Hourly Sales Analysis

Analyzed orders by hour of the day to identify periods with higher customer demand and understand peak ordering times.

### 5. Monthly Sales Trend

Analyzed monthly order volumes to identify changes and patterns in pizza demand throughout the year.

### 6. Pizza Category Analysis

Compared pizza categories based on:

* Percentage contribution to total sales
* Total pizzas sold
* Revenue performance

### 7. Pizza Size Analysis

Analyzed sales across different pizza sizes and categories using a heatmap to understand which **category-size combinations** contribute most to sales.

### 8. Top 5 Selling Pizzas

Identified the **Top 5 pizzas based on quantity sold**.

### 9. Top 5 Pizzas by Revenue

Identified the **Top 5 pizzas based on total revenue generated**.

## 📈 Visualizations

The project includes visualizations for:

* Ingredient frequency
* Orders by day of week
* Revenue by day of week
* Orders by hour
* Monthly order trends
* Sales percentage by pizza category
* Sales percentage by pizza size and category
* Pizzas sold by category
* Top 5 pizzas by quantity
* Top 5 pizzas by revenue

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualization
* **Jupyter Notebook**

## 💡 Business Questions Answered

The analysis addresses the following business questions:

1. What is the total revenue generated?
2. How many pizzas were sold in total?
3. Which pizza category and size perform best?
4. Which are the top 5 performing pizzas?
5. What is the average order value?
6. How many pizzas are sold per order on average?
7. What are the sales trends by day?
8. What are the monthly sales trends?
9. What are the peak ordering hours?
10. Which ingredients occur most frequently?

## 📌 Conclusion

This Pizza Sales EDA project demonstrates how Python and data visualization can be used to transform raw sales data into actionable business insights.

The analysis provides a clear understanding of overall revenue, order volume, customer ordering patterns, pizza category and size performance, ingredient popularity, and top-performing products.

The project can help a pizza business make better decisions related to **product performance, inventory planning, staffing during peak hours, and sales strategy**.
