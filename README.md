#  SQL Projects — Pizza Sales & Walmart Sales Analysis

##  Tools Used
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Advanced-blue?style=for-the-badge)

---

##  Project 1 — Pizza Sales Analysis

###  Business Problem
A pizza restaurant chain wants to understand its sales performance, 
identify top-performing products, and uncover customer purchasing 
patterns to drive better business decisions.

###  Key Business Questions Answered
- What is the total revenue generated?
- Which pizza size and category sells the most?
- Which pizzas contribute the most to revenue?
- What are the peak ordering hours?
- How does cumulative revenue grow over time?

###  Key Findings

| Metric | Result |
|--------|--------|
|  Total Revenue | **$817,860** |
|  Best Selling Size | **Large (L) — 18,526 orders** |
|  Top Revenue Category | **Classic — $220,053** |
|  Analysis Method | CTEs, Window Functions, JOINs |

### SQL Techniques Used
- **JOINs** — combining orders, pizzas and pizza_types tables
- **CTEs** — breaking complex queries into readable steps
- **Window Functions** — calculating cumulative revenue over time
- **GROUP BY & Aggregate Functions** — revenue and count by category
- **ORDER BY & LIMIT** — ranking top performers

###  File
 [View Pizza Sales SQL Queries](Pizza_Sales.sql)

---

##  Project 2 — Walmart Sales Analysis & Forecasting

### Business Problem
Analyse Walmart branch sales data to identify peak sales periods, 
top product lines, and revenue-driving customer segments to support 
strategic business decisions.

### Key Business Questions Answered
- Which product lines generate the most revenue?
- What are the peak sales periods by time of day and day of week?
- Which customer segments drive the most revenue?
- How does sales performance differ across branches?

### SQL Techniques Used
- **Feature Engineering** — created time of day, day of week, month columns
- **CTEs** — structured multi-step analysis
- **Aggregate Functions** — revenue and count by product line
- **GROUP BY & HAVING** — segment-level analysis
- **Window Functions** — branch performance comparisons

### Files
 [View Walmart Sales SQL Queries](Sales_Trends_at_Walmart.sql)
 [View Dataset](Sales_Trends_at_Walmart.csv)

---

## Skills Demonstrated
- Advanced SQL query writing and optimisation
- Business problem framing and analytical thinking
- Data cleaning and feature engineering in SQL
- Translating SQL results into business insights
- Working with real-world messy datasets

---

##  Author
**Sivani Masani**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sivanimasani/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SivaniMasani)


