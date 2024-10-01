# Supermarket-Sales

![image](https://github.com/user-attachments/assets/c0d2031d-976b-4133-a0ef-966d8a03be3e)

## Overview
This repository contains an analysis of supermarket sales data collected from three branches over a specified period. The dataset includes transactions, customer details, and product information, allowing for detailed analysis of sales, customer behavior, and profitability.

## Dataset
The dataset consists of the following key features:

Invoice id: Computer generated sales slip invoice identification number

Branch: Branch of supercenter (3 branches are available identified by A, B and C).

City: Location of supercenters

Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.

Gender: Gender type of customer

Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and 

lifestyle, Sports and travel

Unit price: Price of each product in $

Quantity: Number of products purchased by customer

Tax: 5% tax fee for customer buying

Total: Total price including tax

Date: Date of purchase (Record available from January 2019 to March 2019)

Time: Purchase time (10am to 9pm)

Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)

COGS: Cost of goods sold

Gross margin percentage: Gross margin percentage

Gross income: Gross income

Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

## Information of the dataset
Rows: 1000

Columns: 17

Data types


Float = 7

Integer = 1

Object = 9

## Technologies Used

Python

Pandas for data manipulation

Matplotlib and Seaborn for data visualization

Jupyter Notebook for analysis and reporting.

## Key Analyses
The analysis includes the following visualizations and insights:

1. Correlation Heatmap: Visualizes the relationships between such as int64','float32.
2. Pie plot:

   Total Sales Distribution by Product Line

   Total Sales by Payment Method
4. Bar Plot:

   City Wise Sales

   Total Sales by Gender

   Total Sales by Customer Type

   Customer Rating Distribution by Product Line
6. Line plot:

   Total Sales by Day of the Week


## Recomendation Based on Analysis:
* Customer Loyalty Programs: If "Member" customers contribute more to revenue, further investments in loyalty programs could be considered to increase repeat purchases.
* Targeted Marketing: Based on product line popularity, you can recommend specific promotional campaigns or discounts to boost underperforming categories.
* Optimizing Payment Methods: If a specific payment method like Ewallet is becoming popular, the store can promote it further by offering incentives for using it.


