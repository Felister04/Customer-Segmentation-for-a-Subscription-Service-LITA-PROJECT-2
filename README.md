# Customer Segmentation for a Subscription Service


## Project Overview
This project aims to analyze customer data to identify segments and trends for a subscription service. The main goal is to understand customer behavior, track subscription types, and identify trends in cancellations and renewals. The final deliverable is an interactive Power BI dashboard that presents these insights.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Data cleaning and preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Analysis](#analysis)
  1. Excel Analysis
  2. SQL Analysis
  3. Power BI Dashboard
- [Results and Insights](#results-and-insights)
- [Recommendations](#recommendations)


## Objectives
The main objectives of this project are:

To analyze customer data to find segments, subscription patterns, and trends.
To identify key metrics such as average subscription duration and popular subscription types.
To visualize customer segments, cancellations, and subscription trends in Power BI for interactive analysis.

## Dataset
Source: The primary dataset used for this analysis is the “customer_data.csv” file
Description: The dataset includes customer information, subscription details, cancellation status, duration and other relevant attributes.

## Tools Used
- Excel: For initial exploration, pivot tables, and formula calculations.
- SQL (SQL Server): For querying key insights and identifying customer segments.
- Power BI: For creating an interactive dashboard to present findings.

## Data cleaning and preparation 

In the initial data preparation phase, we performed the following task
1. Data loading and inspection
2. Handling duplicates and missing values
3. Data cleaning and formatting

## Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- what subscription type are top sellers?
- what region are top performers?
- what is the overall subscription trend?


## Analysis
## 1. Excel Analysis
Goal: Conduct initial exploration to identify subscription patterns.

### Steps:
- Analyzed customer data with pivot tables to find patterns in subscription types.
- Calculated average subscription duration and identified the most popular subscription types.
- Created additional reports for insights into customer demographics and trends.

## 2. SQL Analysis
Goal: Extract key insights using SQL queries.

### Queries:
- Retrieve the total number of customers from each region.
- Find the most popular subscription type by the number of customers.
- Identify customers who canceled their subscription within 6 months.
- Calculate the average subscription duration for all customers.
- Identify customers with subscriptions longer than 12 months.
- Calculate total revenue by subscription type.
- Find the top 3 regions by subscription cancellations.
- Determine the total number of active and canceled subscriptions.

## 3. Power BI Dashboard
Goal: Visualize the findings in an interactive dashboard.

### Visualizations Included:
- Customer Segmentation: Breakdown of customers by subscription type and region.
- Subscription Trends: Analysis of active vs. canceled subscriptions.
- Cancellations and Renewals: Visual representation of cancellations by region and subscription length.
- Slicers: Interactive slicers for filtering by subscription type, region, and status.

## Results and Insights

- Popular Subscription Types: Basic is the most popular subscription
![Subscription type performance by revenue](https://github.com/user-attachments/assets/18f0fb5a-458f-4d47-bb16-43806d14e46e)

  
- Regional performance: East is the best performing region
![Screenshot (50)](https://github.com/user-attachments/assets/c903b0d6-cc5c-4173-b150-a416091160df)


- Subscription Trends: 
![Screenshot (51)](https://github.com/user-attachments/assets/2dc92896-d7a5-48e0-95c4-54ce081ed49c)

- Slicer, showing the subscription types for easy interaction
![Screenshot (54)](https://github.com/user-attachments/assets/ea994c01-d065-43ee-a06e-c73c71426b5d)



### Recommendations

Based on the analysis, we recommend the following actions:
- Consider giving discount for the premium and standard sunscription type, in other for this subscription types to penetrate the market
- invest in marketing and promotion in all the regions
