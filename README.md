# Coffee Shop Sales Dashboard in Excel

## Project Overview

This data analysis project aims to create a centralized and interactive Excel dashboard that provides a comprehensive analysis of coffee shop sales data from 2019 to 2022.
The dashboard will serve as a decision-making tool for coffee shop's management team enabling them to track performance, identify trends and optimize business operations. 

## Data Source
The primary dataset used for this analysis is from Kaggle - <a href="https://www.kaggle.com/datasets/mohammadkaiftahir/coffee-orders-data">Dataset</a> containing three tables: Orders,Products and Customer Information.
## Tools
MS Excel - [Download here](https://microsoft.com)
- Data Cleaning
- Data Analysis
- Data Visualization
## Key Deliverables
The dashboard aims to answer the following key questions raised by stakeholders :
#### Sales Performance
- What are the total sales trends over the years?
- Which months consistently generate the highest and lowest sales?
- How do sales vary across different countries?
#### Product Insights
- Which coffee types generate the most sales and profit?
- What is the profit percentage for each coffee type?
- Are there any pattern in sales based on roast type (eg. Light,Medium, Dark)?
#### Customer Insights
- Who are our top 5 customers in terms of total sales?
- How do sales compare between loyalty card holders and non holders?
#### Operational Insights
- How do product size impact sales?
- Are there regional preferances for certain coffee types or roast types?

## Process
#### 1. Data Preparation
- **Data Cleaning :** 
  - Ensured consistent formatting for dates,product categories and customer details.
  - Removed duplicates and handled missing or invalid entries to maintain data integrity.

- **Data Extraction :**
  - Extracted customer data such as names, emails, loyalty card and countries from the *Customers* table using advanced Excel functions like INDEX-MATCH and VLOOKUP.
  - Retrieved product specific details such as unit price, size, profit, roast type and coffee type from the *Products* table.

- **Enhanced Data Fields :**
  - Introduced new columns *Coffee Type Name* and *Roast Type Name*  by mapping abbreviated names to full names for better visualization and readability.

- **Calculated Metrics :**
  - Added calculated fields like Total Sales *(Quantity * Unit Price)*, Profit, Profit% *((Profit / (Total Sales-Profit) ) * 100)* to measure financial performance.

#### 2. Pivot Tables
- Create pivot tables for each KPI and visualization:
  - **Total Sales over Time :** Displays sales trends over the years 2019 - 2022.
  - **Total Sales by Month :** Analyzes seasonal trends in sales performance by month.
  - **Sales by Country :** Compare sales performce across three countries(Ireland,UK and US).
  - **Sales by Coffee Type :** Visualizes the contribution of each coffee type to total sales.
  - **Top 5 Customers :** Highlights the top customers based on total sales.
  - **Profit % by Coffee Type :** Compares the profitability of each coffee type.
 
#### 3. Visualizations
- Inserted appropriate charts for each KPI(*Total Sales* , *Profit %*)
- Customized colors, labels and titles for readability.

#### 4. Slicers and Filters
- Added slicers for Roast Type, Country, Coffee Type, Loyalty Card and Size and a Timeline to filter on range of dates.
- Connected slicers to relevant pivot tables for interactivity.

## Dashboard
![CoffeSalesDashboard](https://github.com/user-attachments/assets/f642d155-a7f3-4d5e-b79a-8433d40d13b7)

## Business Insights


  
