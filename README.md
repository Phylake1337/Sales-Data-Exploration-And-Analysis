# Sales-Data-Exploration-And-Analysis
Analysis and exploration of digital electronics store to answer some specific business questions.

## Table of Contents
* [Introduction](#Introduction)
* [Data](#Data)
* [Business Questions](#Questions)
* [Data-Driven Answers](#Answers)

----
## Introduction
Quick data analysis and exploration for a digital electronics store to answer business questions, to practice a simple real-life data science scenario.

## Data
Data used for the analysis consists of 12 csv files, each file have specific informations about specific month sales, and each file have the following attribute (Order ID, Product,	Quantity Ordered,	Price Each,	Order Date,	Purchase Address) for each ordered item in a specific month.

## Questions
* Q1: What was the best month for sales? How much was earned that month?
* Q2: What city sold the most product?
* Q3: What time should we display advertisements to maximize likelihood of customer's buying product?
* Q4: What products are most often sold together?
* Q5: What product sold the most? Why do you think it sold the most?

## Answers

### Q1: What was the best month for sales? How much was earned that month?
* Sales in the last month of the year is the highest, almost 5 M$.

![](charts/month_vs_sales.png)

### Q2: What city sold the most product?
* San Francisico CA ranked on top of all cities, hence it has the top sales value which is almost 8 M$ for the whole year.

![](charts/city_vs_sales.png)

### Q3: What time should we display advertisements to maximize likelihood of customer's buying product?
 * During Day:  Around 1 AM would be great time each day as the orders tend to decrese around this time.
 * During The Whole year: At the beginning of May, as the orders tend to decrese at May.

![](charts/hour_vs_sales.png)
![](charts/day_vs_sales.png)

### Q4: What products are most often sold together?
  1. Lightning Charging Cable,iPhone 
  2. Google Phone,USB-C Charging Cable .. etc

![](charts/sold_togther.png)
  
### Q5: What product sold the most? Why do you think it sold the most?
* Batteries, Charging Cable .. Maybe cause they are not costy

![](charts/product_vs_sold.png)



