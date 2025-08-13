# Python-Excel-Sales-Analysis

Overview
This project performs Sales Data Analysis using Python and Excel to uncover customer behavior patterns and sales trends.
The analysis focuses on understanding which demographics, regions, and product categories drive the most sales, helping businesses make data-driven decisions.

Tools & Libraries Used
Python

numpy – Numerical operations

pandas – Data manipulation and cleaning

matplotlib – Data visualization

seaborn – Statistical plotting

Excel – Initial dataset storage and quick inspections

Dataset Information
The dataset contains customer purchase records with the following columns:

Column Name	Description
User_ID	:Unique customer ID
Cust_Name	:Name of the customer
Product_ID: Unique product ID
Gender:	Gender of the customer
Age: Age of the customer
Age Group:	Age category (e.g., 18–25, 26–35)
Marital_Status: Married/Unmarried
State:	State of the customer
Zone: Zone/region
Occupation:	Occupation of the customer
Product_Category:	Category of the purchased product
Orders:	Number of orders placed
Amount:	Total purchase amount
Status:	Order status
Unnamed:	Extra unnamed column (removed during cleaning)

Steps Performed
Import Libraries
Imported numpy, pandas, matplotlib, and seaborn for analysis and visualization.

Load Dataset
Loaded the dataset into a Pandas DataFrame.

Initial Inspection

Checked shape, head, and info of the dataset.

Data Cleaning

Dropped irrelevant columns (Status, Unnamed).

Checked for null values and dropped columns with missing data.

Changed data types for consistency.

Verified remaining columns.

Exploratory Data Analysis (EDA)

Gender Analysis

Number of purchases by gender.

Total amount spent by each gender (found which gender spends more).

Age Group Analysis

Distribution of purchases by age group.

Combined age group and gender to see spending patterns.

Grouped age and amount to find highest spending age category.

State-wise Analysis

Top states by number of orders.

Top states by total spending.

Marital Status Analysis

Compared spending between married and unmarried customers.

Occupation Analysis

Identified top occupations contributing to sales.

Product Category Analysis

Most purchased product categories.

Highest revenue-generating products.

Key Insights
Certain genders contribute more to sales revenue.

The 26–35 age group is the biggest spender.

Some states dominate in both order count and revenue.

Married customers tend to spend more than unmarried ones.

Specific occupations have a higher purchase frequency.

A handful of product categories generate the majority of sales.

Visualizations
The project includes visualizations like:

Bar plots for gender, age group, state, marital status, and occupation analysis.

Sorted bar charts for top products and categories.

Conclusion
This analysis provides a deeper understanding of who the customers are, what they buy, and how much they spend.
Such insights can be used to design better marketing strategies, target the right demographics, and optimize inventory.

