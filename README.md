# Elite Bikestore Customer Analysis Project


## Project Overview
The Elite Bikestore Customer Analysis Project focuses on analyzing customer data to understand purchasing behaviors and key demographics for a bike store. This project leverages Excel for data cleaning, pivot table creation, and deriving insights. The primary goal is to identify trends that can be used to optimize marketing efforts and improve overall sales strategies.


## Objective
The main objective of this project is to:

- Understand customer demographics and purchasing patterns.
- Derive actionable insights to inform marketing and sales strategies.
- Explore relationships between variables such as age, income, and purchase status.


## Tasks
#### Data Cleaning and Transformation

- Clean the Dataset: Address any missing values and ensure consistency in data formats.
- Calculated Fields: Create additional fields such as customer lifetime value and average purchase frequency to support deeper analysis.
  
#### Dynamic Dashboard Setup

- Interactive Dashboard: Build a dynamic dashboard using Excel features like PivotTables, Slicers, and PivotCharts.
- Adjustable Parameters: Include parameters such as income range, marital status, and region that allow users to explore different customer segments.
  
#### Profitability Analysis

- Segment Profitability: Analyze the profitability of customer segments based on attributes like marital status, commute distance, and income.
- Advanced Metrics: Calculate metrics such as revenue per customer, profit per purchase, and segment-wise profitability using advanced Excel functions.


## Metadata
The dataset consists of customer information collected by the Elite Bikestore. It contains the following columns:

- **Customer ID:** Unique identifier for each customer.
- **Age:** Customer's age.
- **Income:** Annual income of the customer.
- **Marital Status:** Indicates whether the customer is married or single.
- **Gender:** Customer's gender.
- **Purchased Bike:** Whether the customer purchased a bike (Yes or No).
- **Purchase Status:** Numeric indicator where 1 represents purchase, and 0 represents no purchase.
- **Number of Children:** Number of children the customer has.
- **Commute Distance:** Distance the customer lives from the bike store.
- **Region:** Geographical region where the customer resides.
- **Car Ownership:** Number of cars owned by the customer.


## Data Preparation
Data preparation involved:

- Cleaning and organizing the dataset in Excel.
- Addressing missing values and ensuring consistency in data formats.
- Improved data clarity by expanding abbreviations in marital status & gender Column(e.g., M to Married, S to Single, M to Male & F to Female).
- Adding a Purchase Status column to facilitate binary analysis (1 for purchases, 0 for non-purchases).
- Grouping age into categories:
  - Young Adults (25-39)
  - Middle-Aged (40-54)
  - Older Adults (55-69)
  - Seniors (70+)
- Grouping income into three categories: Low, Medium, High.
- Creating pivot tables to analyze various dimensions such as age, income, and purchase status.


## Analysis
#### Age Group Segmentation

- The customers were segmented into four age groups: Young Adults (25-39), Middle-Aged (40-54), Older Adults (55-69), and Seniors (70+).
- Pivot tables were used to determine the total bike purchases by each age group.
  
#### Income Segmentation
- Income was grouped into three categories: Low, Medium, and High.
- Analyzed the relationship between income levels and bike purchases.

#### Purchase Analysis
- Examined the proportion of customers who purchased bikes versus those who didn’t.
- Analyzed additional variables like gender, marital status, car ownership, and commute distance to identify potential trends.

  
## Key Insights

1. Key Age Groups: Young Adults (25-39) and Middle-Aged customers (40-54) account for **88%** of bike purchases, making them crucial for marketing.
2. Income vs. Purchases: There is no strong correlation between higher income and bike purchases. For example, Young Adults lead in purchases despite lower average income, indicating other factors like lifestyle may play a role.
3. Marital Status: Married customers have a 10% higher average income than single customers, and married males represent the largest buyer group.
4. Gender: Male customers have a 6% higher average income than female customers, but both genders exhibit similar purchasing patterns.
5. Geographical Distribution: **North America** is the largest customer base **(46%)**, followed by **Europe (31%)** and the **Pacific region (23%)**.
6. Commute Distance: Most customers who purchased bikes live within 0-1 miles of the store (42% of buyers), indicating proximity is a factor in purchases.
7. Car Ownership: 62% of buyers own 0-1 cars, suggesting bike purchases are higher among those with fewer cars.

   
## Tools Used
- Microsoft Excel: For data cleaning, calculated fields, analysis, and visualization.

  
## Conclusions
The analysis reveals that:

- Age and proximity are significant factors influencing bike purchases, with Young Adults and Middle-Aged customers making the majority of purchases.
- Income alone is not a primary driver for bike purchases; instead, lifestyle factors may play a stronger role.
- Geographical targeting could help improve sales in specific regions like North America, where the majority of customers are located.
