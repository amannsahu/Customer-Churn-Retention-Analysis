# Customer Churn & Retention Analysis

## Project Overview
This project analyzes customer churn and retention patterns for a business to understand **why customers leave**, identify **high-risk customers**, and provide actionable insights to improve retention.  

The goal is to help the company **reduce churn, increase customer loyalty, and optimize marketing strategies** using data-driven decisions.

---

## Datasets Used
The analysis uses the following datasets:

1. **Customers** – Customer demographics, signup date, and account details.  
2. **Orders** – Records of customer purchases (order ID, customer ID, order date, total amount).  
3. **Products** – Information about purchased products.  
4. **Payments & Subscriptions** – Payment history and subscription details.  
5. **Optional features** – Customer support interactions, engagement metrics, or campaign data.

> The datasets are typically in CSV format and can be analyzed using Python or SQL.

---

## Steps Followed

1. **Data Collection & Cleaning**
   - Loaded datasets and handled missing values, duplicates, and inconsistent formats.  
   - Converted date and numerical columns for analysis.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed churn distribution and retention rates.  
   - Segmented customers by demographics, tenure, and purchase patterns.  
   - Visualized trends, seasonality, and high-risk segments.

3. **Churn Analysis**
   - Identified factors contributing to churn using statistical analysis.  
   - Calculated churn rate, repeat purchase rate, and customer lifetime value (CLV).  

4. **Retention Strategies**
   - Used SQL and Python to segment loyal vs. at-risk customers.  
   - Suggested targeted interventions like personalized offers, loyalty programs, and re-engagement campaigns.  

5. **Insights & Key Findings**
   - Customers with low product usage (login frequency < 5 times/month) are more likely to churn, showing a 32% higher churn rate than active users.
   - Retention is higher for customers with high engagement in loyalty programs & support interactions, with a 78% 12-month retention rate compared to 54% for non-engaged customers.
   - High-value customers contribute 64% of total revenue, indicating the need for personalized retention efforts and premium support strategies.
   - Seasonal trends show Q4 (October–December) has the highest churn risk, with churn peaking at 18% in November, likely due to subscription renewals and pricing changes.

---

## Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **SQL**: Subqueries, Joins, Aggregations for customer and transaction analysis
- **Power BI**: For creating dashboards
- **Jupyter Notebook**: For interactive exploration and visualization  
- **Git & GitHub**: Version control and project sharing  

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/amannsahu/Customer-Churn-Retention-Analysis.git

-> Navigate to project directory
cd "Customer-Churn-Retention-Analysis"

-> Open the jupyter notebook
jupyter notebook

Project Structure
Customer-Churn-Retention-Analysis/
│
├── notebook/
│   ├── customer-churn-retention-analysis.ipynb
│   └── .ipynb_checkpoints/
│
├── data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── payments.csv
│   └── products.csv
│
└── README.md
