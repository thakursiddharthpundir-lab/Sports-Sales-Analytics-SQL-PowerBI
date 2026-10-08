# 🏆 Sports Sales Analytics — SQL & Power BI

![Power BI]
![SQL]
![Excel]
![Data Analytics]

## 📌 Project Overview

This project is an end-to-end **Sports Sales Analytics** project developed to analyze sales, customers, products, stores, profitability, promotions, delivery performance, and returns.

The project combines:

- **SQL** for data exploration and business analysis
- **Power BI** for interactive dashboards and visualization
- **Excel** for initial data preparation and validation
- **DAX** for KPI calculations and advanced Power BI analysis

The objective is to transform raw sports sales data into meaningful business insights that can support decision-making in areas such as:

- Revenue growth
- Profitability
- Customer segmentation
- Product performance
- Store performance
- Sales channel performance
- Promotion effectiveness
- Discount optimization
- Delivery operations
- Return management

---

# 🎯 Business Objective

The main objective of this project is to answer important business questions related to the performance of a sports retail business.

The analysis focuses on:

1. What is the total sales revenue?
2. How much profit is generated?
3. What is the overall profit margin?
4. Which products generate the highest sales?
5. Which products generate the highest profit?
6. Which product categories perform best?
7. Which brands contribute the most revenue?
8. Which customer segments generate the most sales?
9. Which membership type generates the highest revenue?
10. Which states generate the most sales?
11. Which stores perform best?
12. Which sales channel performs best?
13. Which salespersons generate the highest sales and profit?
14. Which promotions generate the highest revenue?
15. How do discounts affect profitability?
16. What are the most common return reasons?
17. Which products and categories have high return rates?
18. How does delivery time affect customer ratings?
19. How does sales performance change over time?
20. Which products have high revenue but low profitability?

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **PostgreSQL** | SQL analysis and business queries |
| **Power BI** | Interactive dashboard and visualization |
| **DAX** | KPI calculations and measures |
| **Power Query** | Data cleaning and transformation |
| **Microsoft Excel** | Data inspection and preparation |
| **GitHub** | Project documentation and version control |

---

# 📊 Dataset Overview

The dataset contains sports retail transaction-level information covering:

- Orders
- Customers
- Products
- Brands
- Sports categories
- Stores
- Salespersons
- Sales channels
- Payment methods
- Promotions
- Discounts
- Delivery
- Customer ratings
- Returns
- Profitability
- Geographic information
- Time-based information

Each row represents a sales transaction/order record.

---

# 📋 Dataset Columns

The dataset contains the following columns:

| Column | Description |
|---|---|
| `Order_ID` | Unique identifier for each order |
| `Order_Date` | Date on which the order was placed |
| `Order_Time` | Time at which the order was placed |
| `Customer_ID` | Unique customer identifier |
| `Customer_Name` | Name of the customer |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Age_Group` | Categorized age group |
| `City` | Customer city |
| `State` | Customer state |
| `Membership_Type` | Customer membership category |
| `Customer_Segment` | Customer segmentation category |
| `Product_ID` | Unique product identifier |
| `Product_Name` | Name of the product |
| `Product_Category` | Product category |
| `Brand` | Product brand |
| `Sport_Type` | Type of sport associated with product |
| `Quantity` | Number of units purchased |
| `Unit_Price` | Price per unit |
| `Discount_Percent` | Discount percentage applied |
| `Discount_Amount` | Discount amount |
| `Sales_Amount` | Original sales amount before discount |
| `Final_Amount` | Final amount paid after discount |
| `Cost_Price` | Cost of the product |
| `Profit` | Profit generated from the transaction |
| `Store_ID` | Unique store identifier |
| `Store_Name` | Name of the store |
| `Sales_Channel` | Channel through which the order was placed |
| `Payment_Method` | Payment method used |
| `Salesperson` | Salesperson responsible for the transaction |
| `Delivery_Type` | Type of delivery |
| `Delivery_Days` | Number of days taken for delivery |
| `Customer_Rating` | Rating given by the customer |
| `Return_Status` | Whether the order was returned |
| `Return_Reason` | Reason for return |
| `Promotion_Campaign` | Promotion/campaign applied |
| `Quarter` | Financial/calendar quarter |
| `Month` | Month of transaction |
| `Year` | Year of transaction |

---

# 🔄 Data Analytics Workflow

The project follows an end-to-end analytics workflow:

```text
Raw Dataset
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
SQL Analysis
     ↓
Business Questions
     ↓
Power BI Data Model
     ↓
DAX Measures
     ↓
Interactive Dashboard
     ↓
Business Insights
     ↓
Recommendations
