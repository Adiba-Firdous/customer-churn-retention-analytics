# Customer Churn & Retention Analytics

An end-to-end Data Analytics project analyzing customer, subscription, billing, support, and satisfaction data to identify patterns associated with customer churn and highlight potential customer retention opportunities.

## 📌 Project Overview

Customer churn is a major business challenge for subscription-based companies. This project analyzes customer behavior and service-related factors to understand which customer segments show higher observed churn and what factors are associated with customer retention.

The project combines:

- Python for data cleaning and exploratory analysis
- Pandas and NumPy for data manipulation
- SQLite for structured data storage
- SQL for business-oriented analysis
- Power BI for interactive dashboard development
- Jupyter Notebook for analysis and documentation

---

## 🎯 Business Objectives

The main objectives of this project are to:

- Measure the overall customer churn rate
- Analyze churn across different contract types
- Compare churn across subscription and plan types
- Analyze cancellation reasons
- Examine the relationship between churn and customer tenure
- Analyze monthly charges and customer lifetime value (CLTV)
- Investigate complaints and customer satisfaction (CSAT)
- Identify customer segments that may require retention attention
- Translate analytical findings into business recommendations

---

## 📊 Dataset

The project uses customer, subscription, billing, and support information.

### Main Data Areas

- Customer demographics
- Subscription details
- Contract type
- Plan type
- Subscription source
- Monthly charges
- Customer Lifetime Value (CLTV)
- Churn score
- Churn flag
- Complaint count
- Customer Satisfaction Score (CSAT)
- Cancellation information
- Customer tenure

### Dataset Note

The original dataset contained 21 customers.

For portfolio-level exploratory analysis, the dataset was expanded to 200 customer records using synthetic data augmentation while preserving the original schema, categories, and general data patterns.

Therefore, the expanded dataset should be considered **synthetic/augmented data for analytical practice**, not real-world customer data.

---

## 🗂️ Project Structure

```text
customer-churn-retention-analytics/
│
├── README.md
│
├── data/
│   └── customer_churn_200_customers.csv
│
├── notebooks/
│   └── customer_churn_analysis.ipynb
│
├── sql/
│   └── churn_business_analysis.sql
│
└── .gitignore


| Tool / Technology | Purpose                             |
| ----------------- | ----------------------------------- |
| Python            | Data analysis and processing        |
| Pandas            | Data cleaning and transformation    |
| NumPy             | Numerical analysis                  |
| Matplotlib        | Data visualization                  |
| Seaborn           | Statistical visualization           |
| SQLite            | Database management                 |
| SQL               | Business analysis                   |
| Power BI          | Dashboard development               |
| Jupyter Notebook  | Analysis environment                |
| Git & GitHub      | Version control and project sharing |




🔍 Analysis Performed
1. Data Quality Analysis

The dataset was checked for:

Missing values
Duplicate customer IDs
Data consistency
Churn logic
Date fields
Customer-level support information
2. Churn Analysis

Churn was analyzed across:

Overall customer base
Contract type
Plan type
Subscription type
State
Cancellation reasons
3. Customer Behavior Analysis

The project examines:

Customer tenure
Monthly charges
Customer Lifetime Value (CLTV)
Churn score
4. Customer Experience Analysis

Customer experience was analyzed using:

Complaint activity
Average CSAT
Support interactions
Customer-level support summaries


📈 Key Findings

Based on the 200-customer augmented analytical dataset:

Overall Churn
Total customers: 200
Active customers: 148
Churned customers: 52
Overall observed churn rate: 26%
Contract Type

Observed churn was substantially higher among monthly-contract customers than annual-contract customers.

Monthly contract churn rate: 55.26%
Annual contract churn rate: 8.06%
Plan Type

Observed churn rates:

Basic: 52.83%
Standard: 18.18%
Premium: 14.29%
Subscription Type

Observed churn rates:

Referral: 76.36%
Paid: 20.00%
Organic: 0%

These results are based on the augmented dataset and should not be interpreted as representative population estimates.

Complaints

Churned customers recorded substantially more complaints than active customers:

Active customers: 0.28 average complaints
Churned customers: 1.33 average complaints

This suggests a strong association between higher complaint activity and customer churn in the analyzed dataset.

Customer Satisfaction

Average CSAT was substantially different between active and churned customers:

Active customers: 87.76
Churned customers: 30.01

This indicates a strong observed association between customer satisfaction and churn in the analyzed dataset.

Customer Lifetime Value

Average CLTV:

Active customers: 961.41
Churned customers: 389.65

Churned customers had substantially lower observed CLTV than active customers.

Tenure

Average tenure:

Active customers: 60.15 months
Churned customers: 52.29 months

Churned customers had lower average tenure in this dataset.


Business Recommendations

Based on the observed patterns, businesses could consider:

Monitor monthly-contract customers
Develop targeted retention campaigns for customers on monthly contracts.
Improve customer support experience
Investigate recurring complaints and identify common service issues.
Prioritize low-CSAT customers
Use satisfaction scores to identify customers who may require proactive engagement.
Investigate early-tenure churn
Improve onboarding and early customer engagement.
Protect high-value customers
Monitor customers with high CLTV and signs of dissatisfaction.
Analyze cancellation reasons
Use cancellation feedback to identify recurring product or service problems.
🧮 SQL Analysis

The project includes business-focused SQL queries using SQLite.

SQL techniques include:

SELECT
WHERE
GROUP BY
CASE
Aggregations
JOIN
LEFT JOIN
Common Table Expressions (CTEs)
Customer-level support aggregation

Example business questions include:

Churn by contract type
Churn by state
High-CLTV churned customers
High monthly-charge churned customers
Low-CSAT churned customers
Cancellation reasons
Support-heavy customers
Customer-level summaries
📊 Power BI Dashboard

The Power BI dashboard is designed to provide an interactive view of:

Total customers
Active customers
Churned customers
Churn rate
Churn by contract type
Churn by plan type
Churn by subscription type
Cancellation reasons
Customer satisfaction
Customer behavior indicators

Dashboard files and screenshots can be added to the repository after the Power BI report is completed.

📓 Jupyter Notebook

The notebook contains the complete analytical workflow:

Business objective
Dataset overview
Database exploration
Data quality assessment
Data cleaning
Churn definition
Support data aggregation
Customer-level analytical dataset
KPI analysis
Exploratory data analysis
Customer behavior analysis
Customer experience analysis
Correlation analysis
SQL business analysis
Business insights
Recommendations
Limitations
Conclusion
🚀 Future Improvements

Potential future enhancements include:

Building a complete interactive Power BI dashboard
Adding dashboard screenshots
Developing customer segmentation
Building a churn prediction model
Applying machine learning classification algorithms
Creating customer risk categories
Automating data refresh
Adding retention campaign tracking
👩‍💻 Author

Adiba Firdous

MCA Student | Data Analytics Enthusiast

Skills demonstrated in this project:

Python • SQL • SQLite • Pandas • NumPy • Data Analysis • Data Visualization • Power BI • Git • GitHub
