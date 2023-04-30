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

**Date Table**

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/Date%20table.PNG)

**Time Table**

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/Time%20Table.PNG)
       
· Use DAX formula to copy the price column from PIZZA table to ORDER DETAILS table

· Use DAX formula to create the total price per order column (multiply the Quantity column & Price column)

. Use DAX formula to create different **Calculated Measures**

**Calculated Measures**

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/image%203.PNG)

· As I keep digging for more insight, I continue to iterate to suit my needs

**Data Model**

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/image%204.PNG)


## Solution to the Business Problems

The following are answers to the business question. Gotten from the analysis and visualization

1. We have an average of 59 customer patronage per day and the peak hours are from 12pm to 1pm. Meaning most orders are in the afternoon and are eaten for lunch.            _Heat map shown below_

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/image%205.PNG)

2. The typical number of pizza per order is one (1) pizza. Meaning most orders are just for (1) one pizza quantity

3. The company made a revenue of **$817k**. Sales and revenue was relatively constant between the first to third quarters of the year but revenue dropped a little bit in the fourth quarter of the year which are months September, October and December.                   _check image below_

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/image%206.PNG)

they are the months with the lowest revenue throughout the year after **February** ( which is due to the number of 28 days in it) .

After investigating the reason for drop in sales and revenue. I discovered that:

i. **September** has 2 days without sales (couple with the fact that it has 30 days in it).

ii. **October** has 4 days without sales

iii. **December** was due to low sales in the end of the month i.e from 25th — 31st

4. **Brie Carre pizza** should be taken off the menu due to it having the lowest order and lowest revenue generation.
     _Image below shows the Barie Carre order heat map throughout the year._

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/image%207.PNG)

5. The best selling pizza is the **Classic Deluxe pizza** while the worse selling pizza is **Barie Carre pizza**

6. Our average order value is **$38.31**

## Conclusion

1. The business has an average of 59 customers per day and the hour with the highest sales in bewteen 12pm and 1pm
2. The typical number of pizza per order is just one (1) pizza per order
3. The business made $817k revenue. There were drop in revenue mostly during the fourth quarter due to some holidays during some days of the month
4. **Barrie Carie Pizza** is the pizza with the least order and revenue
5. Best selling pizza is the **Classic Deluxe Pizza**
6. **$38.31** is the average order value (AOV)

## Recommendation

1. The above insight shows most of the customers makes orders in the afternoon showing they are mostly cooperate office worker. There there should be sales promotion to attract more customers too and to also retain the other customers
2. After investigating more on the sales pattern of Barie Carre pizza, i discoverd that the sales should continue due to the fact that it is still in demand but just in relatively small quantity. It has an average of 21 days of order in a month.  


**Below is a Power BI dashboard of the whole dataset**

![](https://github.com/FreshDAnalyst/Pizza-Sales-Analysis/blob/main/pizza%20visuals-4.jpg)


# Abdullahi Mudathir Yusuf 
_Data Analyst_

