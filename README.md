# Exploratory Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Recommendations](#recommendations)

### Project Overview

This data analysis project aims to provide insights into the sales performance of an E-commerce company over the past year. By analyzing various aspects of the sales data, we seek to identify the trends make data driven recommendations and gain a deeper understanding of the company's performance.

### Data Sources

Sales Data: The primary dataset used for this analysis is the file, containing detailed information about each sale made by the company

### Tools

- Microsoft Excel Workbok :- Data Cleaning, Data Analysis & Data Visualization.

### Data Cleaning/Preparation

In the initial data preparation phase, the following tasks were performed.

1. Data loading & inspection.
2. Handling missing values.
3. Data cleaning & formatting.

### Exploratory Data Analysis(EDA)

EDA involved exploring the sales data to answer key questions, such as;

- In which month was the highest sales produced?
- Who made the most purchases- men or women?
- What are different order status?
- List top 5 states contributing to the sales?
- Which channel is contributing to maximum sales?
- Which is the highest selling category?
- Compare the sales and orders.
- Relation between age and gender based on number of orders.

### Data Analysis

include some interesting code/features worked with

```excel

#NewCloumn

=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))

#New Column

=TEXT(G2,"mmm")
```

### Results/Findings

1. Month of March had the most peak sales(1.9M).
2. Women are more likely to buy compared to men(~65%).
3. Maharashtra, Karnataka & Uttar Pradesh are the top 3 states(~35%).
4. Adult age group (30-49yrs) is max contributing (~50%).
5. Amazon, Flipkart & Myntra channels are max contributing(~80%).

### Recommendations

- Target women customers of age group (30-49yrs) living in Maharashtra, Karnataka & Uttar Pradesh by showing ads/offers/coupons available on Amazon, Flipkart & Myntra.
