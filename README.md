# Project01_DA
Exploratory data analysis of a food delivery dataset to understand delivery performance, customer satisfaction, and order patterns.
# Food Delivery Data Analysis

## Project Overview
This project performs exploratory data analysis (EDA) on a food delivery dataset to understand customer ordering behavior, delivery performance, and factors affecting customer satisfaction.

The analysis explores relationships between delivery distance, waiting time, customer ratings, and menu categories.

---

## Dataset
The dataset contains information about food delivery orders including:

- Order ID
- Transaction time
- Menu category
- Order price
- Delivery distance (km)
- Waiting time (minutes)
- Customer rating
- Customer complaints
- Promotion status
- Order status

---

## Objectives
The main objectives of this project are:

- Understand customer ordering patterns
- Analyze delivery performance
- Explore the relationship between delivery distance and waiting time
- Investigate factors affecting customer ratings
- Identify potential operational improvements

---

## Data Cleaning
The following preprocessing steps were performed:

- Checked and handled missing values
- Removed duplicate records
- Verified data types
- Cleaned the dataset for analysis

---

## Exploratory Data Analysis
Several visualizations were created to understand the dataset, including:

- Orders by menu category
- Distribution of order prices
- Delivery distance vs waiting time
- Waiting time vs customer rating
- Complaint level distribution

Libraries used for visualization:

- Pandas
- Matplotlib
- Seaborn

---

## Key Insights
Some insights discovered during the analysis:

- **Ayam** is the most frequently ordered menu category.
- Delivery waiting time generally increases with delivery distance.
- Longer waiting times tend to be associated with lower customer ratings.
- Most customers report **no complaints**, indicating generally good service quality.

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure
food-delivery-analysis

├──Raw data
│ └── synthetic_fooddelivery_dataset.csv

├── notebooks
│ └── kaggle.ipynb

├── Transformed Data
│ └──food_delivery_clean.csv

├── Food Delivery Dashboard

└── README.md



---

## Future Improvements

Possible next steps for this project:

- Build a predictive model to estimate delivery time
- Create an interactive dashboard
- Perform sentiment analysis on customer reviews

---

## Author
Data analysis project created as part of my learning journey in data analytics.
