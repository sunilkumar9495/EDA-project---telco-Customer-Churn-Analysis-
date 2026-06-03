# Telco Customer Churn Analysis

## Project Overview

Customer churn is one of the most critical challenges faced by telecommunication companies. Retaining existing customers is often more cost-effective than acquiring new ones. This project focuses on performing Exploratory Data Analysis (EDA) on a telecom customer dataset to identify the key factors influencing customer churn and uncover actionable business insights.

The objective of this analysis is to understand customer behavior, identify churn patterns, and determine which services, demographics, and contract types contribute most to customer attrition.

---

## Problem Statement

Telecommunication companies lose revenue when customers discontinue their services. Understanding the reasons behind customer churn can help organizations develop retention strategies and improve customer satisfaction.

This project aims to answer the following questions:

* What factors contribute most to customer churn?
* Are contract type and tenure related to customer retention?
* How do monthly charges and total charges impact churn behavior?
* Which customer segments are more likely to leave the company?
* What business strategies can reduce customer attrition?

---

## Dataset Information

The dataset contains customer demographic information, account details, subscribed services, billing information, and churn status.

### Key Features

* Customer ID
* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn

---

## Project Workflow

### 1. Data Collection

* Imported the Telco Customer Churn dataset.
* Loaded and explored data using Pandas.

### 2. Data Understanding

* Examined dataset structure and feature types.
* Identified categorical and numerical variables.
* Analyzed missing values and inconsistencies.

### 3. Data Cleaning

* Handled missing and invalid values.
* Converted data types where necessary.
* Removed duplicate records.
* Prepared data for analysis.

### 4. Exploratory Data Analysis (EDA)

Performed extensive exploratory analysis including:

* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis
* Churn Distribution Analysis
* Customer Segmentation Analysis
* Correlation Analysis

### 5. Data Visualization

Created visualizations using Matplotlib and Seaborn:

* Count Plots
* Histograms
* Pie Charts
* Bar Charts
* Boxplots
* Heatmaps
* Customer Churn Comparisons

---

## Key Insights

### Factors Associated with Higher Churn

* Customers with month-to-month contracts showed significantly higher churn rates.
* Customers with shorter tenure were more likely to leave the company.
* Higher monthly charges were associated with increased churn probability.
* Customers without online security and technical support services exhibited higher churn rates.

### Factors Associated with Lower Churn

* Long-term contract customers demonstrated stronger retention.
* Customers with multiple subscribed services were more likely to remain loyal.
* Longer-tenure customers showed significantly lower churn behavior.

### Customer Segmentation Findings

* New customers represented the highest-risk churn segment.
* Customers using electronic check payment methods showed higher churn rates.
* Senior citizens displayed different churn patterns compared to other customer groups.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Customer Behavior Analysis
* Data Visualization
* Correlation Analysis
* Business Insight Generation
* Data Storytelling

---

## Business Impact

The insights generated from this analysis can help telecom companies:

* Improve customer retention strategies.
* Identify high-risk customers before they churn.
* Design personalized marketing campaigns.
* Optimize pricing and service offerings.
* Increase customer lifetime value.

---

## Conclusion

This project demonstrates the application of Exploratory Data Analysis to understand customer churn behavior in the telecommunications industry. By analyzing customer demographics, service subscriptions, billing patterns, and contract details, valuable insights were uncovered that can help businesses reduce churn and improve customer satisfaction. The findings highlight the importance of contract type, tenure, service quality, and pricing in influencing customer retention.

---

For GitHub, this pairs very well with your **Life Expectancy Analysis** project because together they showcase:

* Healthcare domain analysis
* Business/customer analytics
* Data cleaning
* EDA
* Visualization
* Insight generation
