# Pizza-Sales-Analysis

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/image%201.PNG)

## Introduction

I came across the dataset on the marven analytics website and I admire how the data is and how I can help to use my analytics skill solve those business questions to practice my skills in data cleaning, data modelling, analysis and data visualization.

**The tool for this project will be Power BI.**

**Power BI concept applied:**

· DAX concepts

· Data Modelling: Star schemas(*-1)

# Problem Statement

The company has the following questions and problem to solve with the data.

· How many customers do we have each day? Are there any peak hours?

· How many pizzas are typically in an order?

· How much money did we make this year? Can we identify any seasonality in the sales?

· Are there any pizza we should take off the menu or any promotion we could leverage?

· What are our best and worst selling pizzas?

· What’s our average order value?

# Data Sourcing

Not until I understand the above mentioned question did I went ahead to get the data from maven analytics website. I then downloaded the CSV file extract it into power BI for cleaning, modelling analysis and visualization.

It contains 4 sheets/tables:

1. ORDER DETAILS with 999+ rows and 4 columns

2. ORDERS with 999+ rows with 3 columns

3. PIZZA TYPES with 33 rows and 4 columns

4. PIZZA with 96 rows and 4 columns

# Data Transformation/Cleaning

Data was efficiently cleaned and transformed with the Power Query Editor of Power BI.

· Datatype for IDs changed from “WHOLE NUMBER” to “TEXT”

· I used the first row as header in the PIZZA TYPES table

· Converted price column from decimal to dollar

· As I keep digging for more insight, I continue to iterate to suit my needs

# Data Modelling 

· To create a star schemas(1-*),I need to merge all columns in ORDERS table with the ORDER DETAILS table

· Use DAX formula to create a DATE and TIME table for better modelling and date/time analysis

 Date Table     |     Time Table
 :-------------:|:---------------:
 ![](
       
