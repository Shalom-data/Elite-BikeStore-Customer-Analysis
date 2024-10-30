# Elite Bikestore Customer Analysis Project


## Project Overview
The Elite Bikestore Customer Analysis Project focuses on analyzing customer data to understand purchasing behaviors and key demographics for a bike store. This project leverages Excel for data cleaning, pivot table creation, and deriving insights. The primary goal is to identify trends that can be used to optimize marketing efforts and improve overall sales strategies.

## Table Of Contents📖
- [Objectives](#objectives)
- [Tasks](#tasks)
- [Tools Used](#tools-used)
- [Metadata](#metadata)
- [Data Preparation](#data-preparation)
- [Analysis](#analysis)
- [Visuals in This Report](#visuals-in-this-report)
- [Insights and Recomendations](#insights-and-recommendations)
- [Conclusion](#conclusion)


## Objectives
The main objective of this project is to:

- Understand customer demographics and purchasing patterns.
- Derive actionable insights to inform marketing and sales strategies.
- Explore relationships between variables such as age, income, and purchase status.


## Tasks
#### Data Cleaning and Transformation

- Clean the Dataset: Address any missing values and ensure consistency in data formats.
- Create additional fields where necessary to support deeper analysis.
  
#### Dynamic Dashboard Setup

- Build a dynamic dashboard using Excel features like PivotTables, Slicers, and PivotCharts.
- Include parameters such as income range, marital status, and region that allow users to explore different customer segments.
  
#### Profitability Analysis

- Analyze the profitability of customer segments based on attributes like marital status, commute distance, and income.

  ## Tools Used
- Microsoft Excel: For data cleaning, calculated fields, analysis, and visualization.


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

## Visuals in This Report

- Below are the general overview of our customer base by Demography and Income
   - Demography Overview
<img width="878" alt="Demography Overview" src="https://github.com/user-attachments/assets/ce7fe95d-f648-4c12-afb9-0afb9e9899d1">

   - Income Overview
<img width="860" alt="Income overview" src="https://github.com/user-attachments/assets/4296a426-c846-4b83-9fea-53c8714d8ee9">

- Below are the filtered visuals for only purchasing customers
  
     - Purchase by Demography
<img width="773" alt="Purchase by Demography" src="https://github.com/user-attachments/assets/540eb9f3-812f-4162-8b37-9e98a4ce9cdb">

- Purchase by Income Level
<img width="746" alt="Purchase by Income2" src="https://github.com/user-attachments/assets/703924a9-99cb-4a79-9b58-586f108b7342">

### Interact with the dashboard [here!](https://1drv.ms/x/c/b19accea551987d7/EeLp4LKiKIZKpaWRUeTtZN0B_fLJa_RLBsww-KSzEy4KCA?e=CYe1Oh)

 
## Insights and Recommendations

1. #### INCOME & PURCHASING BEHAVIOUR

- Marital Status: Married customers have an average income that is 10% higher than single customers.
- Gender: Male customers earn 6% more on average than female customers.
- Buyer vs. Non-Buyer Income: Buyers have an average income that is 6% higher than non-buyers.

##### ACTIONABALE RECOMMENDATION:
Focus on marketing to married and higher-income customers to boost revenue through premium offerings or exclusive packages.

2. #### AGE GROUPS & PURCHASE TRENDS

- Young Adults (25-39) and Middle-aged (40-54) account for 88% of bike purchases (422 out of 481 buyers).
- Despite earning less on average, Young Adults (25-39) lead in purchases.
- Middle-aged customers (40-54) have the highest income but also show strong purchase behavior.

##### ACTIONABALE RECOMMENDATION:
- The Young Adults (25-39) group should be a key focus, even though they have lower incomes. Affordable models, installment plans, or targeted promotions might appeal to this group.
 
- The Middle-Aged (40-54) group represents a high-income, high-purchase segment. Offering premium models or bundling products like accessories or maintenance services could resonate with this group.
 
- Older Adults (55-69) and Seniors (70+) may require a different approach. Offering e-bikes, or promoting health benefits and comfort-related features, might attract more purchases from these age groups.  

3. #### REGION & DEMOGRAPHIC INSIGHTS

- North America (46%) is the largest customer base, followed by Europe (31%) and the Pacific (23%).

##### ACTIONABALE RECOMMENDATION:
- Strengthen marketing in North America while expanding growth opportunities in Europe and the Pacific through targeted campaigns.
- Leverage targeted campaigns toward married customers, especially focusing on couples' promotions or family-oriented packages.

4. #### PURCHASE TREND BY NUMBER OF CHILDREN

- 30% of buying customers have no children, while 40% have 1-2 children.

##### ACTIONABALE RECOMMENDATION:
Create family or group packages to attract more customers with children, possibly offering discounts or incentives for families.

5. #### TREND BY INCOME BRACKET

- Low-income customers make up 63% of buyers, followed by middle-income customers (30%) and high-income customers (7%).

##### ACTIONABALE RECOMMENDATION:
- Introduce flexible payment plans, installment options, or budget bike models to cater to the dominant low-income buyer base and boost sales.

6. #### EDUCATION LEVEL INSIGHTS

- Customers with Bachelor’s degrees form the largest buyer group, followed by those with partial college and high school graduates.

##### ACTIONABALE RECOMMENDATION:
- To further engage customers based on education levels, consider partnerships with educational institutions or offering student discounts. 
- Since the majority of customers have bachelor’s or graduate degrees, creating targeted email campaigns or ads that align with their professional interests could drive more engagement.
  
7. #### LOCATION & PROXIMITY

- 42% of buyers live within 0-1 miles of the store, with a steep drop-off for those living further away.

##### ACTIONABALE RECOMMENDATION:
- Improve delivery options and bolster your online store to attract distant customers who may not visit the store in person.

8. #### TREND BY NUMBER OF CARS OWNED

- 62% of buying customers own 0-1 cars, while 26% own 2 cars.

##### ACTIONABALE RECOMMENDATION:
Highlight eco-friendly transportation benefits and promote bikes as a cost-effective commuting alternative, especially to customers with fewer cars.

 
## Conclusion
- This Excel-based analysis of the Elite Bike Store dataset uncovers key customer insights and provides targeted recommendations to enhance marketing strategies. Focusing on income brackets, age groups, and regional trends allows the business to tailor offerings, while flexible payment options and family packages cater to a broader audience. These data-driven recommendations aim to increase customer engagement, expand market reach, and improve overall profitability.

## How to View the Report
To view the full interactive report, download the .xls file . If you do not have Excel, you can view the screenshots and exported visuals included in this repository.

### Did you read till the last line?, Great to have you!😎👍
### Your feedback will be greatly appreciated, msg me directly on my email [Here!](mailto:umeasiegbushalom@gmail.com) or via [LinkedIn](https://www.linkedin.com/in/umeasiegbu-shalom)

   


  

