# Dashboard: MS-Excel

This repository contains a dashboard created in Excel. The purpose of this dashboard is to provide insights and visualizations based on the provided dataset.

# Dataset
The dataset used for this dashboard is located in the file data.csv. It includes columns, such as "index,	Order ID,	Cust ID,	Gender,	Age, Date,	Status,	Channel, 	SKU	Category,	Size,	Qty,	currency,	Amount,	ship-city,	ship-state,	ship-postal-code,	ship-country,	B2B".

# Data Cleaning

* Gender Column Cleaning: The gender column was cleaned by replacing "M" and "W" with "Men" and "Women," respectively.
* Age Group Column: An additional column, "Age Group," was created using the formula =IF(E2>50,"Senior",IF(E2>=30,"Adult","Teenager")). This formula categorizes individuals into different age groups based on their age.
* Month Column Extraction: Another column, "Month," was added by extracting the month data from the "Date" column using the formula =TEXT(G2,"mmm").

# Business Requirements
The dashboard aims to address the following business requirements:

* Comparison of Sales and Orders: Create a single chart to compare sales and orders.
* Month with Highest Sales and Orders: Determine which month had the highest sales and orders.
* Comparison of Purchases by Gender in 2022: Analyze whether men or women made more purchases in 2022.
* Order Status in 2022: Identify the different order statuses in 2022.
* Top 10 States Contributing to Sales: List the top 10 states that contribute the most to sales.
* Relation Between Age and Gender Based on Orders: Explore the relationship between age and gender based on the number of orders.
* Channel Contributing to Maximum Sales: Determine the channel that contributes the most to sales.
* Highest Selling Category: Identify the category with the highest sales.

# Insights for Business

* Women are more likely to make purchases compared to men, accounting for approximately 65% of the total customer base.
* The top three states contributing to sales are Maharashtra, Karnataka, and Uttar Pradesh, collectively representing around 35% of the total sales.
* The adult age group (30-49 years) contributes the most to sales, accounting for approximately 50% of the total.
* The channels contributing the most to sales are Amazon, Flipkart, and Myntra, collectively contributing around 80% of the total sales.

# Recommendations
Based on the insights derived from the analysis, the following recommendations for business-

* Target women customers belonging to the age group of 30-49 years, residing in Maharashtra, Karnataka, and Uttar Pradesh. This can be done by displaying targeted advertisements, offers, and coupons available on Amazon, Flipkart, and Myntra.

# Feedback and Contributions
Feedback and contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.
