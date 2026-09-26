# Retail Sales Analysis
## Dashboard

![Retail Sales Dashboard](Screenshot%202026-09-25%20124109.png)
## Project Overview

This project analyzes **1,000 retail sales transactions** using Microsoft Excel to understand revenue performance, product demand, customer behavior, branch performance, gender purchasing patterns, and extreme-spend transactions.

The analysis was designed to turn transaction-level sales data into business insights that can support decisions around product performance, customer engagement, branch performance, and sales opportunities.

## Business Questions

The analysis focuses on questions such as:

- Which products generate the most revenue?
- Which product categories have the highest sales volume?
- How does revenue differ between Member and Normal customers?
- How does revenue differ by gender?
- Which branch generates the highest revenue?
- Which product categories show the highest quantity sold?
- How much revenue is associated with extreme-spend transactions?
- Is there a relationship between quantity sold and total transaction value?

## Dataset Overview

The workbook contains a **Dataset** sheet with 1,000 transaction records and 19 columns.

### Core fields

| Field | Description |
|---|---|
| `Sale_Id` | Unique identifier for each sale |
| `Branch` | Branch where the transaction occurred |
| `City` | City associated with the branch |
| `Customer_Type` | Customer segment: Member or Normal |
| `Gender` | Customer gender |
| `Product_Name` | Product purchased |
| `Product_Category` | Product category |
| `Unit_Price` | Price per unit |
| `Quantity` | Number of units purchased |
| `Tax` | Tax amount associated with the transaction |
| `Total_Price` | Total transaction value |
| `Reward_Points` | Reward points earned |
| `Is_Outliers` | Transaction classification: Normal Transaction or Outlier (Extreme Spend) |

The dataset contains:

- **3 branches**
- **3 cities**
- **2 customer types**
- **2 gender groups**
- **5 products**
- **5 product categories**
- **1,000 transactions**
- **10,337 units sold**

There are no missing values in the core analytical fields used in the dataset.

## Tools Used

- **Microsoft Excel**
- Pivot Tables
- Excel formulas and calculations
- Data analysis and visualization
- Dashboard design
- Outlier classification
- Correlation analysis

## Analysis Performed

### 1. Overall Sales Performance

The analysis recorded:

- **Total Revenue:** $118,583.90
- **Total Orders:** 1,000
- **Total Quantity Sold:** 10,337
- **Average Transaction Value:** $118.58
- **Average Quantity per Order:** 10.34

### 2. Revenue by Product

Revenue was distributed across five products:

| Product | Revenue |
|---|---:|
| Shampoo | $27,041.36 |
| Notebook | $24,792.98 |
| Orange Juice | $24,686.46 |
| Detergent | $22,449.07 |
| Apple | $19,614.03 |

Shampoo generated the highest revenue among the five products, while Apple generated the lowest.

### 3. Quantity Sold by Product Category

| Product Category | Units Sold |
|---|---:|
| Personal Care | 2,238 |
| Beverages | 2,183 |
| Stationery | 2,165 |
| Household | 2,010 |
| Fruits | 1,741 |

Personal Care recorded the highest quantity sold, while Fruits recorded the lowest.

### 4. Customer Segment Performance

Member customers generated:

**$63,213.63**

Normal customers generated:

**$55,370.27**

This shows that the Member segment contributed more revenue than the Normal customer segment in this dataset.

### 5. Gender Performance

| Gender | Revenue |
|---|---:|
| Male | $64,318.45 |
| Female | $54,265.45 |

The dataset records higher total revenue from male customers.

### 6. Branch Performance

| Branch | Revenue |
|---|---:|
| A | $42,584.71 |
| C | $40,226.93 |
| B | $35,772.26 |

Branch A recorded the highest total revenue, while Branch B recorded the lowest.

### 7. Outlier Analysis

The dataset classifies transactions into two groups:

- **Normal Transaction:** 985 transactions
- **Outlier (Extreme Spend):** 15 transactions

The 15 extreme-spend transactions represent **1.5% of all transactions** but account for approximately **5.19% of total revenue**.

This makes the outlier group important when interpreting overall sales performance because a relatively small number of transactions contribute a larger share of revenue.

### 8. Correlation Analysis

The workbook analysis shows a positive relationship between **Quantity** and **Total Price**, with a correlation coefficient of approximately:

**0.684**

This indicates that higher quantities purchased tend to be associated with higher transaction values in this dataset.

## Dashboard

The project includes an Excel dashboard presenting the main findings visually, including:

- Total Revenue
- Total Orders
- Total Quantity Sold
- Average Order Value
- Revenue by Product
- Customer Segmentation
- Gender Preference
- Branch Performance
- Outlier Analysis

## Key Insights

1. **Shampoo generated the highest product revenue**, at $27,041.36.
2. **Personal Care had the highest unit volume**, with 2,238 units sold.
3. **Member customers generated more revenue** than Normal customers.
4. **Branch A recorded the highest revenue**, followed by Branch C and Branch B.
5. **Male customers generated higher total revenue** than female customers in the dataset.
6. Only **1.5% of transactions were classified as extreme-spend transactions**, but they contributed approximately **5.19% of total revenue**.
7. Quantity and transaction value show a **positive correlation of approximately 0.684**, indicating that transaction value generally increases as the quantity purchased increases.

## Business Recommendations

Based on the analysis:

- Maintain strong availability and visibility for high-revenue products such as Shampoo.
- Investigate the drivers behind the strong performance of the Personal Care category.
- Use the Member segment's higher revenue contribution to evaluate opportunities for customer retention and loyalty initiatives.
- Review Branch B's performance relative to Branch A and Branch C to identify operational or sales factors that may explain the difference.
- Monitor extreme-spend transactions separately so that unusually large purchases do not obscure normal sales patterns.
- Consider quantity-based promotions or bundled offers where appropriate, given the positive relationship between quantity purchased and transaction value.

## Project Structure

```text
Retail-Sales-Analysis/
│
├── Retail_Sales_Analysis.xlsx
├── README.md
└── screenshots/
    └── retail-dashboard.png
```

## Project Outcome

This project demonstrates the ability to move from **raw transaction data → data analysis → business insights → dashboard communication** using Microsoft Excel.

The focus is not only on creating charts, but on using sales data to understand product, customer, branch, and transaction-level performance.
