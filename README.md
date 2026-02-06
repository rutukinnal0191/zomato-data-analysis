# Zomato Data Analysis Using Python

# Project Overview

Understanding customer preferences and restaurant trends is essential for making data-driven business decisions in the food industry.
This project performs Exploratory Data Analysis (EDA) on Zomato restaurant data using Python to extract meaningful insights about restaurant popularity, pricing patterns, ratings, and order preferences.

##Objectives

This analysis answers the following business questions:

Do more restaurants provide online delivery compared to offline services?  
Which types of restaurants are most preferred by customers?  
What price range do couples prefer while dining out?  
How ratings vary between online and offline ordering?  

##Dataset Information

The dataset contains restaurant-level details including:
- Restaurant Name
- Restaurant Type
- Online Order Availability
- Votes
- Ratings
- Approximate Cost for Two People

##Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

##Project Workflow

##Import Libraries

Used Python libraries for data manipulation and visualization.

##Data Loading

Loaded dataset using Pandas

##Data Cleaning & Preparation

Checked dataset summary  
Verified missing values  

##Exploratory Data Analysis

##Restaurant Type Popularity

Analyzed restaurant categories to identify most common types.

Insight:

north indian food is ordered highest

##Customer Votes Analysis

Compared customer engagement across restaurant.

Insight:

highly populated restaurant Byg Brewski Brewing Company

##Online Order Availability

Compared number of restaurants providing online ordering.

Insight:

Most restaurants provide online ordering are popular

##Ratings Distribution

Studied rating spread across restaurants.

Insight:

Most restaurants receive ratings between **3.0 to 3.5**

##Cost Preference for Couples

Analyzed pricing trends.

Insight:

Couples prefer restaurants costing around **rs.200 to rs.400**

##(Online vs Offline)

Compared restaurants with and without online delivery.

Insight:

Many Restaurants offer online delivery 

##Restaurant rating (online vs offline)

compared restaurant with and without online delivery

Insight:

restaurant with online delivery have higher ratings

Created  to  crosstab identify ordering behavior.

Insight:
- Dining restaurants mostly receive offline orders  
- Quick service mostly receive online orders  

##Key Business Insights

Dining restaurants are most popular  
Customers engage more with dining-type (north indian) restaurants  
Moderate pricing attracts more customers  
online orders are popular
Online ordering improves restaurant ratings  
quick service earn more from online delivery  

##How To Run The Project

Clone repository:

steps to run this project locally:

git clone 

navigate into the folder cd zomato-data-analysis

pip install pandas numpy matplotlib seaborn

launch jupyter notebook

open and run the notebooks/zomato_analysis.ipynb

