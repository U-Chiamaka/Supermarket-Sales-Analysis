## Aries Supermarket Sales Analysis



## Project Overview



This project analyzes three months of supermarket transaction data from Aries branches in Lagos, Abuja and Port Harcourt.



The analysis explores sales performance, product performance, customer behaviour, payment preferences, customer ratings and purchasing patterns to generate insights that can support better business decisions.



## Business Problem



Management needs a clear understanding of which branches and product lines are performing well, how different customer groups are purchasing, and when customers are most active.



This analysis uses transaction data to identify these patterns and provide actionable recommendations around sales, customer engagement and product performance.



## Business Questions



The analysis seeks to answer the following questions:



1. Which branch generates the highest total sales?

2. Which branch generates the highest gross income?

3-. How does sales performance change across the three months?

4-. Which product lines generate the highest sales and quantity sold?

5-. Do Member customers generate more sales than Normal customers?

*  How does purchasing behaviour differ by gender?

7. Which payment method is most commonly used overall and across branches?

8. How do customer ratings compare across the branches?

9. What are the busiest shopping hours overall, and do peak hours differ by branch?

10. Is there a relationship between customer ratings and sales or gross income?

## Dataset



The dataset contains 1,000 supermarket transactions recorded between January and March 2019 across three branches:



- Lagos

- Abuja

- Port Harcourt

Key fields include:



- Invoice ID

- Branch

- City

- Customer type

- Gender

- Product line

- Unit price

- Quantity

- Tax 5%

- Total

- Date

- Time

- Payment

- COGS

- Gross margin percentage

- Gross income

- Rating



## Tools and Technologies



- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook

- Git \& GitHub



## Key Findings



- Port Harcourt recorded the highest total sales at approximately ₦39.8 million.

- January recorded the highest monthly sales at approximately ₦41.9 million, while February recorded the lowest at approximately ₦35.0 million.

- Food and beverages was the highest-selling product line at approximately ₦20.2 million.

- Member customers generated slightly higher total sales than Normal customers.

- Payment preferences differed across branches. Epay was most frequently used in Abuja and Lagos, while Cash was most frequently used in Port Harcourt.

- Customer ratings were relatively similar across the three branches.

- 7 PM recorded the highest number of transactions overall, with 113 transactions.

- Quantity sold had a strong positive relationship with total sales, with a correlation of approximately 0.71.



## Business Recommendations



Based on the findings, Aries should:



1. Strengthen sales strategies in Abuja and Lagos by reviewing branch-specific customer and product purchasing patterns.

2. Maintain strong availability of Food and Beverages products and consider targeted promotions or product bundles.

3. Review the performance of the Health and Beauty product line and evaluate its product assortment, pricing and promotional strategies.

4. Strengthen Member customer engagement through targeted promotions and loyalty incentives.

5. Maintain reliable and convenient payment options based on payment preferences across each branch.



## Additional Data to Collect



Future analysis would benefit from:



- A unique customer ID

- Product-level cost and profit margin data

- Promotion and discount data

- Customer feedback or comments

- Inventory and stock availability data



## Project Structure



```text

Supermarket Sales Analysis/

│

├── Supermarket\_Analysis.ipynb

├── Abuja\_Branch.csv

├── Lagos\_Branch.csv

├── Port\_Harcourt\_Branch.csv

├── Plots/

│   ├── Average Customer Rating by City.png

│   ├── Customer Rating vs Total Sales.png

│   ├── Gross Income by City.png

│   ├── Monthly Sales Trend.png

│   ├── Payment Methods by City.png

│   ├── Total Sales by City.png

│   ├── Total Sales by Customer Type and Gender.png

│   ├── Total Sales by Product Line.png

│   └── Transactions by Hour.png

│

└── README.md

## Limitations



\- The dataset covers only three months, limiting the analysis of longer-term and seasonal trends.

\- There is no unique customer identifier, so individual customer retention and repeat purchases cannot be determined.

