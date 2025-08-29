# Advanced-Data-Analytics-using-SQL
This repository offers a well-structured collection of SQL scripts tailored for data exploration, analytics, and reporting. It encompasses a wide range of analyses, including database exploration, key measures and metrics, time-based trends, cumulative insights, and segmentation. Designed with data analysts and BI professionals in mind, the scripts enable efficient exploration, segmentation, and in-depth analysis of relational databases. Each query is crafted around a specific analytical objective while highlighting best practices in SQL. This makes the collection a practical resource for enhancing analytical workflows and generating actionable insights.

🎯 Task:- As a Data Analyst, I need to perform Exploratory Data Analysis to derive insights and interpret the findings with the use of different Advance Analytics techniques shown in image below, for which used the different functions in SQL such as Complex Queries, Aggregation, Window function, CTE, Subqueries and Views. So we will dive deep into each one, step by step.
![image_alt](https://github.com/shraddhasangave99/Advanced-Data-Analytics-using-SQL/blob/main/Project%20Roadmap_new.png?raw=true)

## 1] Change over Time (Trends) Analysis
#### 🎯Purpose:
A) To track trends, growth, and changes in key metrics over time.
 
B) For time-series analysis and identifying seasonality.
 
C) To measure growth or decline over specific periods.
#### 🚩Formula Used: ∑[Measure] by [Date Dimension]
#### 🔍SQL Task: Analyse Sales performance over time.

## 2] Cumulative Analysis
#### 🎯Purpose:
A) To calculate running totals or moving averages for key metrics.
 
B) To track performance over time cumulatively.
 
C) Useful for growth analysis or identifying long-term trends.
#### 🚩Formula Used: ∑[Cumulative Measure] by [Date Dimension]
#### 🔍SQL Task: Calculate the total sales per month and the running total of sales over time.

## 3] Performance Analysis
#### 🎯Purpose:
A) To measure the performance of products, customers, or regions over time.
 
B) For benchmarking and identifying high-performing entities.
 
C) To track yearly trends and growth.
#### 🚩Formula Used: Current[Measure]-Target[Date Dimension]
#### 🔍SQL Task: Analyse yearly performance of products by comparing each product's sales to both avg sales performance and the previous year's sales.

## 4] Part-to-Whole (Proportional) Analysis
#### 🎯Purpose:
A) To compare performance or metrics across dimensions or time periods.
 
B) To evaluate differences between categories.
 
C) Useful for A/B testing or regional comparisons.
#### 🚩Formula Used: ([Measure]/Total[Measure])*100 by [Dimension]
#### 🔍SQL Task: Which categories contribute the most to overall sales?

## 5] Data Segmentation Analysis
#### 🎯Purpose:
A) To group data into meaningful categories for targeted insights.
 
B) For customer segmentation, product categorization, or regional analysis.
#### 🚩Formula Used: [Measure] by [Measure]
#### 🔍SQL Task: Segment products into cost ranges and count how many products fall into each segment?

## 6] Customer Report
#### 🎯Purpose:
A) This report consolidates key customer metrics and behaviors.

#### 🔍SQL Task:  
1. Gathers essential fields such as names, ages, and transaction details.
2. Segments customers into categories (VIP, Regular, New) and age groups.
3. Aggregates customer-level metrics:
	total orders
	   - total sales
	   - total quantity purchased
	   - total products
	   - lifespan (in months)
4. Calculates valuable KPIs:
	    recency (months since last order)
		- average order value
		- average monthly spend
   
## 7] Product Report
#### 🎯Purpose:
A) This report consolidates key product metrics and behaviors.

#### 🔍SQL Task:  
 1. Gathers essential fields such as product name, category, subcategory, and cost.
 2. Segments products by revenue to identify High-Performers, Mid-Range, or Low-Performers.
 3. Aggregates product-level metrics: total orders - total sales - total quantity sold - total customers (unique) - lifespan (in months)
 4. Calculates valuable KPIs: recency (months since last sale)  - average order revenue (AOR) - average monthly revenue
