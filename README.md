# Retail Sales Analysis: Identifying Revenue Trends & Business Opportunities

## Project Overview

This project analyzes the Sample Superstore retail dataset to identify revenue trends, profitability patterns, customer contribution, and potential business opportunities.

The analysis uses Python, Pandas, data visualization, and SQL to evaluate business performance across product categories, sub-categories, discount levels, regions, and customers.

## Dataset

- **Dataset:** Sample Superstore
- **Source:** [Kaggle - Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Records:** 9,994 rows
- **Features:** 21 columns

The dataset is a sample retail dataset and does not represent verified real-world company performance.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL (SQLite)
- Jupyter Notebook

## Project Workflow

1. Data loading and inspection
2. Data cleaning and validation
3. Feature engineering
4. Exploratory Data Analysis (EDA)
5. Category and sub-category analysis
6. Discount and profitability analysis
7. Monthly and yearly sales analysis
8. Regional performance analysis
9. Customer contribution analysis
10. SQL-based business analysis

## Key Findings

### 1. Overall Business Performance

| Metric | Value |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Total Orders | 5,009 |
| Total Customers | 793 |
| Total Quantity Sold | 37,873 |
| Profit Margin | 12.47% |

### 2. Category Performance

| Category | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Technology | $836,154.03 | $145,454.95 | 17.40% |
| Furniture | $741,999.80 | $18,451.27 | 2.49% |
| Office Supplies | $719,047.03 | $122,490.80 | 17.04% |

Technology generated the highest sales and profit, while Furniture had the lowest profit margin.

### 3. Sub-Category Profitability

- Copiers generated the highest profit: **$55,617.82**.
- Tables recorded the highest loss: **-$17,725.48**.
- Bookcases and Supplies also reported negative profits.
- Copiers had a profit margin of 37.20%, while Tables had a margin of -8.56%.

### 4. Discount Analysis

- Discount levels from 0% to 20% showed positive aggregate profit.
- Discount levels from 30% to 80% showed negative aggregate profit.
- The 70% discount group recorded an aggregate loss of $40,075.36.
- These results show an association between higher discount groups and negative profitability, not proof that discounts directly cause losses.

### 5. Yearly Sales Performance

| Year | Sales | Profit | Sales Growth |
|---|---:|---:|---:|
| 2014 | $484,247.50 | $49,543.97 | — |
| 2015 | $470,532.51 | $61,618.60 | -2.83% |
| 2016 | $609,205.60 | $81,795.17 | 29.47% |
| 2017 | $733,215.26 | $93,439.27 | 20.36% |

2017 recorded the highest sales and profit during the analyzed period.

### 6. Regional Performance

| Region | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| West | $725,457.82 | $108,418.45 | 14.94% |
| East | $678,781.24 | $91,522.78 | 13.48% |
| South | $391,721.90 | $46,749.43 | 11.93% |
| Central | $501,239.89 | $39,706.36 | 7.92% |

West generated the highest profit, while Central had the lowest profit margin.

### 7. Customer Analysis

- Total customers: 793
- Top 10% of customers contributed 30.88% of total sales.
- 155 customers had negative total profit.
- Sean Miller was the highest-sales customer, with $25,043.05 in sales but a negative profit of $1,980.74.

## Business Recommendations

- Review pricing and discount strategies for loss-making sub-categories.
- Investigate the low profitability of Furniture products, particularly Tables and Bookcases.
- Monitor regional profit margins, especially in the Central region.
- Evaluate high-revenue customers who generate negative profit.
- Consider customer contribution when planning retention strategies.

## Limitations

- The dataset is a sample dataset, not verified real-world company data.
- The analysis is observational and cannot establish causation.
- Profitability may be influenced by product mix, order size, discounts, and other factors.
- Further investigation is required before making actual business decisions.

## Author

**Veer Jain**
