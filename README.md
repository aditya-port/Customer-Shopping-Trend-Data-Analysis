🛍️ Customer Shopping Trend Data Analysis

🚀 Executive Summary

End-to-end data analytics project analyzing 3,900 customer transactions to uncover insights that drive revenue growth, customer engagement, and retention.

What I did:

Cleaned & transformed raw data using Python
Performed business-driven SQL analysis
Built an interactive Power BI dashboard

Key Insights:

👕 Clothing is the top revenue-generating category
👥 Young Adult & Middle-aged segments drive most sales
❌ 73% customers are non-subscribers → huge opportunity to increase subscription
💸 Discounts increase conversions but not always revenue
🔁 Repeat buyers are more likely to subscribe

Top Recommendations:

Convert non-subscribers via targeted campaigns
Focus on high-performing categories
Optimize discount strategies for profitability
Build loyalty programs for repeat buyers
📊 Dashboard Preview

<img width="1409" height="770" alt="image" src="https://github.com/user-attachments/assets/020b0d29-4680-41df-8764-81616de46cf7" />


🧩 Business Problem

Retail company wants to:

Understand customer purchasing behavior
Identify key drivers (discounts, reviews, seasonality)
Improve engagement, retention, and revenue

Core Question:
How can customer data be leveraged to optimize marketing and product strategy?

⚙️ Methodology
🐍 Python (Data Preparation)
Data cleaning & preprocessing
Missing value imputation (median by category)
Feature engineering:
Age groups
Purchase frequency (days)
Loaded data into PostgreSQL

Reference:

🛢️ SQL (Analysis)
Customer segmentation (New, Returning, Loyal)
Revenue analysis (gender, category, age group)
Discount impact analysis
Subscription behavior insights
Window functions (Top-N products)
CTEs + aggregations
📊 Power BI (Visualization)
KPI Cards:
Customers: 3.9K
Avg Purchase: $59.76
Avg Rating: 3.75
Visuals:
Revenue by category
Sales by age group
Subscription split
Interactive filters (gender, category, shipping)

🧠 Skills Demonstrated
SQL

CTEs, Window Functions
Aggregations & Subqueries
Business-driven querying

Power BI

Data modeling
DAX measures
Interactive dashboards

Python

Pandas (cleaning & transformation)
NumPy
SQLAlchemy (DB integration)
📈 Results & Business Recommendations

🔍 Key Findings
Clothing dominates revenue and sales
Young Adult & Middle-aged customers = highest value
Subscription adoption is low (~27%)
Discounts heavily used but need optimization
Strong link between repeat purchases & loyalty

📊 Metrics
Total Customers: 3,900
Avg Purchase Value: $59.76
Avg Rating: 3.75
Subscription Rate: 27%
Top Category: Clothing

💡 Business Actions
🎯 Target non-subscribers with personalized offers
🔁 Launch loyalty programs for repeat buyers
🛍️ Focus on top-performing categories
💸 Optimize discount strategy for ROI
📦 Personalize recommendations by behavior

📁 Project Structure
├── Customer_Shopping_Behavior_Analysis.ipynb
├── business_questions_answer.sql
├── customer_behavior_dashboard.pbix
├── customer_shopping_behavior.csv
├── README.md
└── Business Problem Statement.pdf

⭐ Why This Project Stands Out
End-to-end pipeline (Python → SQL → BI)
Real-world business problem solving
Actionable insights (not just analysis)
Clean dashboard + structured repository
Strong focus on decision-making impact
