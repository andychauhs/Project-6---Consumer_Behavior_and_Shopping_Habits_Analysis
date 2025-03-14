# Project-6--Consumer_Behavior_and_Shopping_Habits_Analysis

## Consumer Behavior and Shopping Habits Analysis

### Overview
This project aims to analyze consumer behavior and shopping habits using the "Consumer Behavior and Shopping Habits Dataset" from Kaggle. The analysis focuses on understanding customer profiles, sales performance, and factors influencing purchasing decisions to enhance marketing strategies. By examining various attributes, the project aims to derive actionable insights that can improve customer engagement and optimize business outcomes.

### Technical Environment
- **Database**: MySQL
- **ORM**: SQLAlchemy
- **Data Analysis**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn (K-means clustering)

### Analysis Tasks

1. **Load Data to MySQL Database**
   - **Task**: Import the consumer behavior dataset into a MySQL database for structured analysis.

2. **CRUD Operations Using SQLAlchemy**
   - **Task**: Implement Create, Read, Update, and Delete operations to manage dataset records effectively.

3. **Customer Segmentation**
   - **Analysis**: Use clustering techniques (e.g., K-means) to segment customers based on purchasing behavior, age, gender, location, and frequency of purchases.
   - **Objective**: Understand different customer profiles and tailor marketing strategies accordingly.

4. **Sales Performance Analysis**
   - **Analysis**: Analyze total sales by category, season, or location, creating visualizations to show trends over time using bar charts or line graphs.
   - **Objective**: Identify which categories or locations generate the most revenue.

5. **Purchase Behavior Analysis**
   - **Analysis**: Investigate the relationship between variables such as age, gender, and purchase amount to determine if older customers spend more than younger ones.
   - **Objective**: Identify key factors that influence purchasing decisions.

6. **Review Rating Analysis**
   - **Analysis**: Analyze how review ratings correlate with purchase amounts and customer demographics.
   - **Objective**: Understand what factors contribute to higher ratings and how they influence sales.

7. **Subscription and Retention Analysis**
   - **Analysis**: Explore the impact of subscription status on purchase frequency and amounts, comparing subscribers versus non-subscribers.
   - **Objective**: Identify the benefits of subscription models and improve retention strategies.

8. **Discount Effectiveness**
   - **Analysis**: Evaluate how discounts and promo codes influence purchase amounts, analyzing the average purchase before and after discounts.
   - **Objective**: Determine the effectiveness of promotional strategies.

9. **Payment Method Preferences**
   - **Analysis**: Analyze preferred payment methods across different customer demographics and their relationship to purchase amounts.
   - **Objective**: Tailor payment options to customer preferences to enhance user experience.

10. **Customer Lifetime Value (CLV) Estimation**
    - **Analysis**: Estimate the lifetime value of customers based on their purchase frequency and average purchase amount.
    - **Objective**: Inform marketing budgets and customer acquisition strategies.

### Data Source
The dataset for this analysis is sourced from Kaggle: [Consumer Behavior and Shopping Habits Dataset](https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset/data). It comprises the following columns:
- **Customer ID**: A unique identifier assigned to each individual customer.
- **Age**: The age of the customer.
- **Gender**: The gender identification of the customer.
- **Item Purchased**: The specific product selected by the customer.
- **Category**: The broad classification of the purchased item.
- **Purchase Amount (USD)**: The monetary value of the transaction.
- **Location**: The geographical location of the purchase.
- **Size**: The size specification of the purchased item.
- **Color**: The color variant associated with the purchased item.
- **Season**: The seasonal relevance of the purchased item.
- **Review Rating**: Customer satisfaction assessment of the purchased item.
- **Subscription Status**: Indicates if the customer has opted for a subscription service.
- **Shipping Type**: Specifies the delivery method used for the purchased item.
- **Discount Applied**: Indicates if any promotional discounts were applied.
- **Promo Code Used**: Notes if a promotional code was utilized during the transaction.
- **Previous Purchases**: Information on the frequency of prior purchases made by the customer.
- **Payment Method**: Specifies the mode of payment employed by the customer.
- **Frequency of Purchases**: Indicates how often the customer engages in purchasing activities.

### Project Files
- **README.md**: This document.
- **Retail_business.ipynb**: Python code for analysis.

**Author**: Ho Sing Andy CHAU  
**Email**: hosingchau@outlook.com  
**Date**: 8 JAN 2025
