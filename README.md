# Customer Behavior Data Analysis

## Project Overview

This project analyzes customer shopping behavior to identify purchasing patterns, customer preferences, and key factors that influence spending.

The analysis combines Python, SQL, and Power BI to transform raw customer transaction data into meaningful business insights.

## Objectives

* Analyze customer purchasing behavior
* Identify spending patterns across different customer groups
* Explore product category performance
* Study the impact of subscriptions and discounts
* Perform business analysis using SQL
* Visualize important insights through an interactive Power BI dashboard

## Project Structure

```text
customer-behavior-data-analysis/
│
├── data/
│   └── Customer_Shopping_Behavior.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── LICENSE
└── README.md
```

## Dataset

The dataset contains customer shopping information, including demographic details, purchase behavior, product categories, subscription status, discounts, payment methods, shipping preferences, and purchase amounts.

### Key Features

* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount
* Location
* Size
* Color
* Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied
* Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

## Tools and Technologies

* **Python** – Data analysis and exploration
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **SQL** – Business analysis and querying
* **Power BI** – Interactive dashboard and reporting
* **Jupyter Notebook** – Exploratory data analysis

## Analysis Workflow

The project follows a complete data analytics workflow:

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
```

## Key Business Questions

The analysis explores questions such as:

* Which product categories generate the highest revenue?
* How does customer spending vary across demographic groups?
* What is the relationship between subscription status and purchasing behavior?
* Which locations and categories contribute the most to sales?
* How do discounts and promotional codes influence purchases?
* Which payment and shipping preferences are most common among customers?

## Dashboard

The Power BI dashboard provides an interactive view of customer behavior and purchasing trends.

It helps visualize:

* Overall customer spending
* Category-wise performance
* Customer demographics
* Subscription patterns
* Discount and promotional activity
* Purchase frequency
* Customer preferences

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Mrityunjay2201/customer-behavior-data-analysis.git
```

### 2. Open the project

```bash
cd customer-behavior-data-analysis
```

### 3. Install Python dependencies

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Run the analysis notebook

Open:

```text
notebooks/customer_behavior_analysis.ipynb
```

using Jupyter Notebook or VS Code.

### 5. Explore SQL analysis

Open:

```text
sql/customer_behavior_sql_queries.sql
```

and execute the queries using your preferred SQL environment.

### 6. Open the dashboard

Open:

```text
dashboard/customer_behavior_dashboard.pbix
```

using Power BI Desktop.

## Repository Contents

| Component | Description                           |
| --------- | ------------------------------------- |
| Data      | Customer shopping behavior dataset    |
| Notebook  | Python-based data analysis            |
| SQL       | Business and customer insight queries |
| Dashboard | Power BI visualization                |
| README    | Project documentation                 |

## Author

**Mrityunjay Tiwari**

GitHub: https://github.com/Mrityunjay2201

---

This project demonstrates an end-to-end data analytics workflow, from data exploration and analysis to SQL querying, visualization, and business insight generation.
