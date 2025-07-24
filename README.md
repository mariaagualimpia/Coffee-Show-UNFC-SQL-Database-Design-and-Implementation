# Coffee Show UNFC: SQL Database Design & Implementation

A relational database project designed to support business intelligence, customer loyalty, and operational growth for a chain of coffee shops.

---

## Project Overview

This project demonstrates the creation and deployment of a fully normalized SQL database for a fictional coffee brand. It captures essential business transactions, customer and employee details, product performance, store analytics, loyalty rewards, and behavioral insights, all structured for scalability and analysis.

---

## Objectives

- Design a normalized SQL schema with 11 interrelated entities
- Track product sales, store performance, and customer behaviors
- Implement a loyalty system and reward redemption logic
- Use advanced SQL queries for business insights and strategic decision-making
- Explore seasonal and demographic trends using transaction data

---

## Database Architecture

**Entity-Relationship Model includes:**

- Customers, Stores, Employees, Products, Transactions, Rewards
- Relational structure with foreign keys, constraints, and views
- Data integrity through normalization (3NF) and referential design

**Core Tables:**
- `product`, `product_category`, `transaction`, `transaction_item`, `customer`
- `employee`, `store`, `location`, `review`, `loyalty_reward`, `customer_reward`

---

## SQL Capabilities Used

- **DDL** – Database & table creation with constraints
- **DML** – Data insertion, updates, deletions for daily operations
- **DQL** – Analytical views for sales, customer behavior, reward usage
- **DCL** – User permissions and privilege management

---

## Analytical Insights

| Topic                 | Key Insights |
|-------------------------|----------------|
| Customer Spending       | Grouped into 4 tiers; high-spending customers buy more frequently |
| Gender Analysis         | Purchasing behavior is consistent across genders |
| Store Performance       | Manitoba & Ontario lead in total sales; Quebec needs strategic focus |
| Seasonal Trends         | February, June, and September require targeted promotions |
| Product Popularity      | Snacks & Iced Coffee dominate; Wednesdays show low sales |
| Loyalty Rewards         | "Barista for a Day" is most redeemed; experiential rewards seem to be succesful |

---

## Featured Queries

- **Customer Segmentation** using CTEs, windows functions, and NTILE()
- **Store-Level Analysis** to identify top-performers & slow hours
- **Sales Trends** by month/day/hour with seasonal breakdown
- **Reward Analytics** with customer preferences and redemption ranking

---

## Repository Structure

| Folder | Contents |
|--------|----------|
| `/Data/` | Dataset (Excel format) |
| `/ER Diagram/` | Entity Relationship Diagram for database structure |
| `/Report/` | PDF report with insights and visuals |
| `/SQL Code/` | SQL scripts used for data exploration and analysis |

---

## Contact

Name: Maria Agualimpia  
Email Address: mariaagualimpia24@gmail.com  
LinkedIn: https://www.linkedin.com/in/maria-agualimpia-11a535129/

---

## Permissions & Security

- Admin roles created using DCL for employees and reporting users
- Privileges assigned based on operational responsibilities
- Users can be granted/revoked access based on security protocols

