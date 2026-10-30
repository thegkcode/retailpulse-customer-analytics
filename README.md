# 📊 RetailPulse – Customer Shopping Behavior Analysis

<p align="center">
  <strong>Transforming Retail Data into Actionable Customer Insights</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
</p>

---

## 📌 Project Overview

**RetailPulse** is an end-to-end data analytics project that explores customer shopping behavior to uncover purchasing patterns, product performance, and customer preferences.

The project transforms raw retail transaction data into meaningful business insights through Python-based data preprocessing, SQL-driven analysis, and interactive Power BI visualizations.

Rather than simply reporting sales figures, RetailPulse focuses on understanding the factors behind customer purchasing decisions, including demographics, discounts, subscriptions, product ratings, and shopping preferences.

## 🎯 Business Objectives

- Analyze customer purchasing patterns and spending behavior.
- Identify revenue contributions across product categories and customer segments.
- Understand the relationship between discounts and purchase amounts.
- Compare purchasing behavior of subscribed and non-subscribed customers.
- Evaluate product performance through customer ratings and reviews.
- Explore customer preferences across demographics and shipping methods.
- Identify opportunities to improve customer engagement and retention.

## 📂 Dataset Overview

The analysis is based on a Customer Shopping Behavior dataset containing:

| Dataset Attribute | Details |
|---|---|
| Total Records | 3,900 |
| Original Columns | 18 |
| Missing Values | 37 |
| Missing Data Field | Review Rating |

The dataset includes customer demographics, product categories, purchase amounts, discounts, subscription status, shipping methods, payment preferences, and review ratings.

## 🛠️ Technology Stack

| Technology | Application |
|---|---|
| Python | Data preprocessing and exploratory analysis |
| Pandas | Data manipulation and transformation |
| MySQL | Relational database management |
| SQL | Business analysis and data querying |
| Power BI | Interactive dashboards and data visualization |
| Jupyter Notebook | Analytical exploration and documentation |

## 🔄 Analytical Workflow

### 1. Data Exploration

- Imported the dataset using Pandas.
- Examined data structure, dimensions, column types, and statistical summaries.
- Identified missing values and potential data quality issues.

### 2. Data Cleaning & Preprocessing

- Handled missing review ratings using median imputation by product category.
- Standardized column names using snake_case.
- Removed redundant columns where appropriate.
- Prepared a structured dataset for further analysis.

### 3. Exploratory Data Analysis (EDA)

- Investigated customer demographics and purchasing patterns.
- Analyzed category-wise sales and spending behavior.
- Explored discount utilization and subscription preferences.
- Examined customer ratings and shipping preferences.

### 4. Feature Engineering

- Created customer age groups to analyze demographic-based purchasing behavior.
- Derived purchase frequency intervals for customer behavior analysis.
- Prepared additional analytical attributes to support SQL-based segmentation.

### 5. SQL Analysis Using MySQL

- Imported the cleaned dataset into MySQL.
- Developed SQL queries to investigate business questions.
- Used aggregations, filtering, conditional logic, and analytical queries to identify customer and product-level patterns.
- Translated query results into business-oriented findings.

### 6. Power BI Dashboard Development

- Designed an interactive dashboard to communicate key analytical findings.
- Developed KPI cards to highlight important customer and purchasing metrics.
- Visualized category-wise revenue, customer demographics, and subscription distribution.
- Incorporated interactive filters for exploring customer segments and purchasing behavior.

## 🔍 Business Questions Explored

The SQL analysis focuses on answering important business questions:

**Customer Behavior & Demographics**

1. Which age groups contribute the most revenue?
2. How does purchasing behavior vary across genders?
3. Which customer segments demonstrate higher purchasing activity?
4. How do repeat purchases relate to subscription behavior?

**Product & Revenue Analysis**

5. Which product categories generate the highest revenue?
6. Which products receive the highest customer ratings?
7. Which products perform best within each category?
8. How does revenue contribution vary across customer segments?

**Discounts & Subscription Analysis**

9. Do customers using discounts have different purchase amounts?
10. Which product categories have higher discount utilization?
11. How do subscribers and non-subscribers differ in purchasing behavior?

**Operational & Customer Insights**

12. How do different shipping methods compare in terms of customer purchases?
13. What insights can be derived from customer ratings and reviews?

## 📊 Power BI Dashboard

The Power BI dashboard brings the analytical findings together in an interactive reporting experience.

**Key Dashboard Components:**

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Customer Subscription Distribution
- Revenue by Product Category
- Customer Distribution by Location
- Revenue by Age Group
- Sales Performance by Product Category
- Sales Distribution Across Age Groups

The dashboard enables users to explore customer segments, compare purchasing patterns, and identify meaningful trends through interactive filtering and visual analysis.

## 💡 Business Value & Analytical Insights

RetailPulse demonstrates how retail transaction data can support business decision-making through:

- **Customer Understanding:** Identifying demographic and behavioral differences across customer segments.
- **Revenue Analysis:** Understanding which product categories and customer groups contribute to sales.
- **Discount Evaluation:** Investigating how promotional discounts relate to customer purchasing behavior.
- **Subscription Analysis:** Comparing the purchasing patterns of subscribed and non-subscribed customers.
- **Product Performance:** Evaluating products through purchase activity and customer ratings.
- **Customer Engagement:** Identifying areas where businesses can further investigate repeat purchases and customer loyalty.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Cleaning and preprocessing real-world datasets using Python and Pandas.
- Performing exploratory data analysis to identify patterns and trends.
- Writing MySQL queries to solve business-oriented analytical problems.
- Applying feature engineering techniques to improve analytical capabilities.
- Connecting structured data analysis with business intelligence reporting.
- Developing interactive Power BI dashboards.
- Communicating analytical findings through a business-focused approach.

## 🚀 Future Enhancements

- Implement cohort analysis to understand customer retention over time.
- Perform customer segmentation using RFM analysis.
- Analyze purchasing trends and repeat customer behavior.
- Introduce more advanced customer lifetime value analysis.
- Enhance dashboard reporting with additional customer engagement KPIs.

---

## 👨‍💻 Author

**Gaurav Kumar**

Computer Science Student | Aspiring Data Analyst

- GitHub: [@thegkcode](https://github.com/thegkcode)

---

<p align="center">
  <strong>Turning Data into Insights. Insights into Better Decisions.</strong>
</p>
