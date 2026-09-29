## Aries Supermarket Sales Analysis



## Project Overview



This project analyzes three months of supermarket transaction data from Aries branches in Lagos, Abuja and Port Harcourt.



The analysis explores sales performance, product performance, customer behaviour, payment preferences, customer ratings and purchasing patterns to generate insights that can support better business decisions.



## Business Problem



Management needs a clear understanding of which branches and product lines are performing well, how different customer groups are purchasing, and when customers are most active.



This analysis uses transaction data to identify these patterns and provide actionable recommendations around sales, customer engagement and product performance.



## Business Questions



The analysis seeks to answer the following questions:



- Which branch generates the highest total sales?

- Which branch generates the highest gross income?

- How does sales performance change across the three months?

- Which product lines generate the highest sales and quantity sold?

- Do Member customers generate more sales than Normal customers?

*  How does purchasing behaviour differ by gender?

- Which payment method is most commonly used overall and across branches?

- How do customer ratings compare across the branches?

- What are the busiest shopping hours overall, and do peak hours differ by branch?

- Is there a relationship between customer ratings and sales or gross income?

## Dataset Description

The dataset contains supermarket transaction records covering three branches: Lagos, Abuja and Port Harcourt.

| Column | Description |
|---|---|
| Invoice ID | Unique identifier for each transaction |
| Branch | Branch code (A, B, or C) |
| City | City where the transaction occurred |
| Customer type | Customer membership type: Member or Normal |
| Gender | Customer gender |
| Product line | Category of product purchased |
| Unit price | Price of a single unit of the product |
| Quantity | Number of units purchased |
| Tax 5% | Tax amount recorded for the transaction |
| Total | Total transaction amount |
| Date | Date of the transaction |
| Time | Time of the transaction |
| Payment | Payment method used |
| COGS | Cost of goods sold |
| Gross margin percentage | Gross margin percentage recorded in the dataset |
| Gross income | Gross income recorded for the transaction |
| Rating | Customer rating for the transaction |

### Derived Columns

| Column | Description |
|---|---|
| Month | Month extracted from the transaction date |
| Day of Week | Day extracted from the transaction date |
| Hour | Hour extracted from the transaction time |
| Day Type | Categorizes transactions as Weekday or Weekend |## Dataset







## Tools and Technologies



- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook

- Git \& GitHub


## Analysis Approach

The analysis followed a structured approach:

1. *Business Understanding* — Defined the business problem, objectives and key questions.
2. *Data Preparation* — Loaded, inspected and cleaned the branch datasets and created relevant date and time features.
3. *Exploratory Analysis* — Examined branch performance, sales trends, product lines, customer segments, payment methods, ratings and transaction activity.
4. *Advanced Analysis* — Investigated customer segments, product quantity versus sales, weekday versus weekend performance, peak hours by branch and relationships between key variables.
5. *Data Visualization* — Developed business-focused visualizations to communicate key patterns and findings.
6. *Business Insights & Recommendations* — Translated the findings into actionable recommendations and identified additional data that could support future analysis.



## Key Findings



- Port Harcourt recorded the highest total sales at approximately 39.8 million naira.

- January recorded the highest monthly sales at approximately 41.9 million naira, while February recorded the lowest at approximately 35 million naira.

- Food and beverages was the highest-selling product line at approximately 20.2 million naira.

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

- Supermarket_Analysis.ipynb — Main analysis notebook containing data preparation, exploratory analysis, visualizations, advanced analysis and findings.
- Abuja_Branch.csv — Abuja branch transaction data.
- Lagos_Branch.csv — Lagos branch transaction data.
- Port_Harcourt_Branch.csv — Port Harcourt branch transaction data.
- Plots/ — Saved visualizations generated during the analysis.
- README.md — Project documentation, key findings, recommendations and limitations.




## Limitations
- The dataset covers only three months, which limits the ability to identify longer-term trends or seasonal patterns.
- There is no unique customer identifier, so individual customer retention and repeat purchases cannot be determined.

## Conclusion

This analysis provided an overview of sales performance, customer behaviour and purchasing patterns across Aries branches in Lagos, Abuja and Port Harcourt.

The findings highlight differences in branch sales, product performance, customer segments, payment preferences and transaction activity. These insights provide a basis for improving product strategy, customer engagement and branch-level decision-making.

The analysis also highlights the value of collecting additional customer, product, promotion and inventory data to support deeper analysis and more informed business decisions in the future.

