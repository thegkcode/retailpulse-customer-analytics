# 📊 RetailPulse – Customer Insights Dashboard

## 📌 Project Overview

**RetailPulse** is an end-to-end retail data analytics project focused on understanding customer purchasing behavior and identifying meaningful business insights from shopping data.

The project explores customer demographics, purchasing patterns, product categories, subscription preferences, discount usage, shipping methods, and customer reviews.

Using Python, SQL, PostgreSQL, and Power BI, raw shopping data is transformed into meaningful insights and interactive visualizations that help support data-driven business decisions.

## 🎯 Business Objectives

- Understand customer purchasing behavior and spending patterns.
- Analyze revenue and sales performance across product categories.
- Explore customer preferences based on age and gender.
- Examine subscription patterns and customer loyalty indicators.
- Evaluate discount usage and its relationship with customer spending.
- Analyze customer reviews and product ratings.
- Present key findings through an interactive Power BI dashboard.

## 📂 Dataset Overview

The project uses a customer shopping behavior dataset containing:

- **3,900** purchase records
- **18** original columns
- **37** missing values in the review rating field

The dataset includes information about customer demographics, product purchases, discounts, subscriptions, shipping preferences, payment methods, and review ratings.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Data cleaning and preprocessing |
| Pandas | Data manipulation and analysis |
| PostgreSQL | Database storage and querying |
| SQL | Business analysis and data extraction |
| Power BI | Interactive dashboard and visualization |
| Jupyter Notebook | Exploratory data analysis |

## 🔄 Project Workflow

**1. Data Loading**
- Imported the dataset using Python and Pandas.
- Examined the dataset structure, columns, and data types.

**2. Data Cleaning & Preprocessing**
- Identified and handled missing review ratings using median imputation by product category.
- Standardized column names using snake_case.
- Removed redundant columns where appropriate.

**3. Exploratory Data Analysis**
- Explored customer demographics and purchasing patterns.
- Examined product category performance.
- Investigated customer preferences and spending behavior.

**4. Feature Engineering**
- Created age groups to analyze customer behavior across different age segments.
- Derived purchase frequency in days for further analysis.

**5. SQL Analysis**
- Loaded the processed data into PostgreSQL.
- Wrote SQL queries to answer business questions and extract actionable insights.

**6. Power BI Dashboard**
- Built an interactive dashboard to visualize customer metrics, revenue trends, category performance, and customer distribution.
- Added filters to explore the data across different customer segments.

## 📊 Key Business Analysis

The SQL analysis covers questions such as:

1. What is the revenue contribution by gender?
2. Do customers using discounts have higher purchase amounts?
3. Which products receive the highest ratings?
4. How do shipping types compare?
5. How do subscribers and non-subscribers differ?
6. Which product categories have higher discount usage?
7. How can customers be segmented based on their purchase behavior?
8. What are the top-performing products in each category?
9. How do repeat purchases relate to subscription behavior?
10. Which age groups contribute the most revenue?

## 📈 Power BI Dashboard

The interactive dashboard provides a visual overview of customer shopping behavior.

**Dashboard Highlights:**

- Total number of customers
- Average purchase amount
- Average review rating
- Customer subscription distribution
- Revenue by product category
- Customer distribution by location
- Revenue by age group
- Sales by product category
- Sales by age group

### Dashboard Preview

<!-- Add your dashboard screenshot at assets/dashboard-preview.png -->

<p align="center">
  <img src="assets/dashboard-preview.png" alt="RetailPulse Power BI Dashboard" width="100%" />
</p>

## 📁 Repository Structure

```text
retailpulse-customer-analytics/
│
├── data/
│   └── customer-shopping-behavior.csv
│
├── notebooks/
│   └── customer-behavior-analysis.ipynb
│
├── sql/
│   └── customer-behavior-analysis.sql
│
├── powerbi/
│   └── retailpulse-powerbi-dashboard.pbix
│
├── docs/
│   ├── business-problem-statement.pdf
│   ├── customer-behavior-analysis-report.pdf
│   └── retailpulse-project-presentation.pptx
│
├── assets/
│   └── dashboard-preview.png
│
├── requirements.txt
└── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/thegkcode/retailpulse-customer-analytics.git
```

### 2. Navigate to the Project Directory

```bash
cd retailpulse-customer-analytics
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Explore the Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

### 5. Run SQL Analysis

- Set up a PostgreSQL database.
- Import the processed dataset.
- Execute the SQL queries available in the `sql/` directory.

### 6. Explore the Dashboard

Open the `.pbix` file using Microsoft Power BI Desktop.

## 💡 Key Learnings

- Practical experience with real-world data cleaning and preprocessing.
- Improved understanding of exploratory data analysis using Pandas.
- Writing SQL queries to solve business-oriented questions.
- Working with PostgreSQL for structured data analysis.
- Designing interactive dashboards in Power BI.
- Translating raw data into meaningful business insights.

## 🔮 Future Improvements

- Add more advanced customer segmentation techniques.
- Explore customer retention and purchasing trends over time.
- Improve dashboard storytelling with additional business KPIs.
- Incorporate more datasets to expand the analysis.

## 👨‍💻 Author

**Gaurav Kumar**

Computer Science Student | Aspiring Data Analyst

- GitHub: [@thegkcode](https://github.com/thegkcode)

---

<p align="center">
  <strong>If you find this project interesting, consider giving it a ⭐!</strong>
</p>
