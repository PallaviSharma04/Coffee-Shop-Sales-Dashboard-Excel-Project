# Coffee Shop Sales Dashboard in Excel

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Key Deliverables](#key-deliverables)
- [Process](#process)
- [Dashboard](#dashboard)
- [Business Insights](#business-insights)
- [Recommendations](#recommendations)

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
**Sales Performance**
- The **highest total sales** were recorded in **2021**, reaching **$13.7k**, driven primarily by **Arabica coffee**.
- **Arabica sales** show a steady increase over the years, while **Excelsa** has maintained consistent revenue.

**Product Performance**
- **Excelsa** and **Liberica** are the **most sold coffee types**, with **Liberica** achieving the **highest profit percentage** at approximately **15%**.
- **Light Roast** is the **most popular roast type**, generating the highest sales.
- The **2.5 kg size** is the **most purchased product size**, contributing significantly to overall sales.

**Customer Insights**
- The **majority of sales** are from **non-loyalty card holders**, indicating a need to enhance the loyalty program's effectiveness.
- The **top 5 customers** based on total sales are **Allis,Brenn,Terri,Nealson and Don**.

**Geographical Trends** 
- **USA** contributes **79% of total sales**, making it the most significant market:
  - **Arabica** is the most popular coffe type.
  - **Light Roast** and **Medium Roast** are the most preferred roast types.
- **Ireland**:
  - **Liberica** is the most purchased coffee type.
  - **Dark Roast** and **Light Roast** are the most popular roast types.
- **UK**:
  - **Excelsa** leads sales.
  - **Light Roast** and **Medium Roast** are the most preferred roast types.
 
## Recommendations 
Based on the analysis we recommend the following actions:
- Increase marketing efforts and promotions around **Arabica coffee** in regions showing rising sales trends especially in campaigns tailored to the US market.
- Ensure consistent stock availibility for **Excelsa** and **Liberica** coffee types as they are among the most sold. Also highlight **high profitability of Liberica** in marketing campaigns to encourage it's sales further.
- Promote **Light Roast** coffee as the top choice through special offers and continue offering **2.5 kg sizes** and explore additional large-size options.
- Offer exclusive discounts or rewards for loyalty card users to boost participation, as most sales come from **non-loyalty card holders**.
- Focus on the **USA market** as 79% of total sales come from this region.
