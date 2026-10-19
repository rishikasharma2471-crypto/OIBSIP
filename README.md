# OIBSIP - Data Analytics Internship

This repository has my work for the Data Analytics internship at Oasis Infobyte.

## Level 1 - Task 1: Exploratory Data Analysis on Retail Sales Data

**Notebook:** `Level 1 - Task 1/Rishika_Task1.ipynb`
**Dataset:** [Retail Sales Dataset](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset) by Mohammad Talib on Kaggle (License: CC0 Public Domain)

### About the project
In this project I explored a retail sales dataset to understand how sales change over time, who the customers are, and which products bring in the most money. The dataset has 1000 transactions with details like date, customer age and gender, product category, quantity, price and total amount.

### What I did
- Loaded the data and checked its size, data types and missing values.
- Found the mean, median, mode and standard deviation of the number columns.
- Plotted monthly and quarterly sales trends with line charts.
- Studied customers by age group and gender.
- Found the revenue of each product category and the top 10 best-selling products.
- Made a correlation heatmap.
- Added an extra chart showing the revenue by price per unit.
- Wrote my observations after every chart and ended with business recommendations.

### Key findings
- Sales were highest in May and lowest in September.
- Q4 had the highest sales and Q3 had the lowest.
- Customers are spread fairly evenly across age groups, and male and female customers are almost equal.
- Electronics, Clothing and Beauty earn almost the same revenue.
- Price per Unit has the strongest link with the order value.
- Items priced at 300 and 500 bring about 88% of the total revenue.

### Note on products
The dataset does not have product names, so I treated each Category and Price combination as one product (for example, Clothing @ 300).

### Tools used
Python, pandas, matplotlib, seaborn, Jupyter Notebook
