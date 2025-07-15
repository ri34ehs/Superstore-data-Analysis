#  Superstore Data Analysis Project

>  An exploratory data analysis (EDA) on retail data from a superstore to uncover business insights on product sales, discounts, customer demographics, and more.

---

##  **About the Dataset**
- **Rows:** 5000 (after cleaning)
- **Columns:** Age, Gender, City, Product Category, Quantity, Unit Price, Discount(%), Payment Method, Total Price
- Covers customer transactions including demographic info, product details, and payment method.

---

##  **Tools & Libraries**
- Python 
- pandas for data manipulation
- seaborn & matplotlib for visualizations
- numpy
- Jupyter Notebook

---

##  **Key Questions Explored**
###  Top product categories by total sales
> Which product categories bring the highest revenue?

###  Average discount by product category
> Which categories get the highest average discounts?

###  Distribution of sales by payment method
> How do customers pay, and which methods generate most sales?

###  Total sales by city
> Which cities are the biggest markets?

###  Average total price by gender
> Do male or female customers spend more on average?

###  Relationship between quantity ordered and total price
> Does buying more always lead to higher total spending?

###  Does giving a higher discount lead to higher total sales?
> Are discounts really boosting sales?

---

##  **Visualizations Included**
- Bar plots (sales by category, payment method, city)
- Boxplots (distribution of numeric features, effect of quantity on total price)
- Scatter plots (discount vs total price, quantity vs total price)
- Histograms & distribution plots
- Correlation heatmap

---

##  **Insights & Findings**
- **Grocery** is the top product category by total sales.
- Average discounts vary slightly by category but don't always increase total sales.
- **Cash**, **UPI**, and **Card** are the most used payment methods.
- **Hyderabad** has the highest total sales among cities.
- Male customers spend slightly more on average than female customers.
- Customers buying higher quantities tend to spend more, but there’s large variation.
- Higher discounts do **not necessarily** lead to higher total price — other factors matter.

---

## ✏ **Data Cleaning & Feature Engineering Steps**
- Removed duplicate rows
- Converted `City`, `Product_Category`, and `Payment_Method` columns to category dtype
- Created new column `Total_price`:
