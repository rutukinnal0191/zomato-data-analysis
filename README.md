# Zomato Data Analysis Using Python

## Project Overview

Understanding customer preferences and restaurant trends is essential for making data-driven decisions in the food industry.
This project performs **Exploratory Data Analysis (EDA)** on Zomato restaurant data using Python to uncover meaningful insights about restaurant popularity, pricing strategies, ratings, and ordering behavior.

## Objectives

This analysis aims to answer the following business questions:

* Do more restaurants provide online delivery compared to offline services?
* Which types of restaurants are most common and preferred?
* What price range do customers prefer while dining out?
* How do ratings differ between online and offline ordering?

## Dataset Information

The dataset contains restaurant-level information such as:

* Restaurant Name
* Restaurant Type
* Online Order Availability
* Number of Votes
* Ratings
* Approximate Cost for Two People
* Cuisine Type
* Location

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Workflow

### 1. Import Libraries

Used Python libraries for data manipulation and visualization.

### 2. Data Loading

Loaded the dataset using Pandas.

### 3. Data Cleaning & Preparation

* Removed unnecessary columns
* Checked dataset structure and summary
* Handled missing values in ratings and cost

## Exploratory Data Analysis

### 1. Cuisine Analysis

Identified the most common cuisines offered by restaurants.

Insight:
North Indian and fast food cuisines dominate the dataset, indicating high demand but also strong competition.

### 2. Customer Votes Analysis

Analyzed restaurants with the highest number of votes.

Insight:
Highly rated and popular restaurants receive significantly more votes, indicating strong customer engagement and trust.

### 3. Online Order Availability

Compared restaurants offering online ordering.

Insight:
Most restaurants provide online ordering, showing that it has become a standard service in the industry.

### 4. Ratings Distribution

Analyzed how ratings are distributed across restaurants.

Insight:
Most restaurants fall in the rating range of **3.0 to 3.5**, indicating average performance and scope for improvement.

### 5. Cost Preference for Customers

Studied pricing trends across restaurants.

Insight:
Most restaurants fall in the **₹200–₹400 range for two people**, suggesting customers prefer affordable dining options.

### 6. Online vs Offline Orders

Compared ordering modes.

Insight:
Online orders are more common, highlighting the importance of convenience in customer behavior.

### 7. Ratings: Online vs Offline

Compared ratings based on ordering availability.

Insight:
Restaurants offering online delivery tend to have slightly higher ratings, suggesting better customer satisfaction.

### 8. Restaurant Type vs Ordering Behavior

Analyzed ordering patterns across restaurant types.

**Insight:**

* Quick-service restaurants rely heavily on online orders
* Dining restaurants show a more balanced mix of online and offline orders

## Key Business Insights

* Online ordering is essential for modern restaurant success
* Mid-range pricing attracts the majority of customers
* Most restaurants operate at average ratings, creating opportunities for improvement
* Cuisine type and restaurant category influence customer engagement
* Convenience (online ordering) positively impacts customer satisfaction

## How to Run the Project

### Clone the repository

git clone https://github.com/rutukinnal0191/zomato-data-analysis.git

### Navigate into the folder

cd zomato-data-analysis

### Install required libraries

pip install pandas numpy matplotlib seaborn

### Run the project

* Launch Jupyter Notebook
* Open zomato_analysis.ipynb
* Run all cells
