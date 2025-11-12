Customer Behavior Analysis – End-to-End Data Analytics Project
📘 Overview

This project focuses on analyzing customer purchase behavior to derive actionable insights that can help improve business strategy, marketing campaigns, and customer retention.

It demonstrates a complete analytics workflow — starting from data loading and cleaning in Python, running advanced SQL queries, building an interactive Power BI dashboard, and summarizing insights through a Gamma presentation.

📊 Dataset

Name: Customer Purchase & Behavior Dataset

Source: Internal / simulated dataset

Format: CSV

Size: ~10,000 records × 12 columns

Column	Description
customer_id	Unique identifier for each customer
gender	Customer gender
age_group	Age segmentation (18–25, 26–35, etc.)
item_purchased	Product name
category	Product category
purchase_amount	Transaction value
discount_applied	Whether discount was used
subscription_status	Subscribed / Non-subscribed
shipping_type	Standard or Express
review_rating	Product review score
previous_purchases	Total previous orders
purchase_date	Transaction date
🛠️ Tools & Technologies
Category	Tools Used
Programming & Analysis	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database & Querying	PostgreSQL / MySQL / SQL Server
Visualization	Power BI
Presentation & Reporting	Gamma
Environment	Jupyter Notebook / VS Code
🔍 Steps & Workflow
1. Data Loading & Exploration (Python)

Loaded dataset using Pandas.

Inspected data types, dimensions, and missing values.

Explored distributions and correlations using Matplotlib and Seaborn.

2. Data Cleaning & Transformation

Removed duplicates and handled missing values.

Standardized column names, formats, and types.

Created new derived columns for segmentation (e.g., revenue group, loyalty tier).

3. SQL-Based Data Analysis

Executed queries in PostgreSQL/MySQL/SQL Server to extract business insights:

Examples from customer_behavior_sql_queries.sql
:

Gender-wise revenue comparison.

Top 5 products by review rating.

Discount impact on spending.

Shipping type vs. purchase behavior.

Customer segmentation (New, Returning, Loyal).

Revenue contribution by age group.

4. Power BI Dashboard

Built an interactive dashboard (customer_behavior_dashboard.pbix) highlighting:

🧾 Total revenue and purchase trends.

👥 Customer segmentation by age, gender, and subscription.

💸 Discount usage and average spend.

🚚 Shipping type impact on order value.

⭐ Top-rated and most purchased products.

5. Reporting with Gamma

Created a visual Gamma presentation summarizing:

Project objectives and dataset overview.

EDA visuals and SQL findings.

Power BI dashboard highlights.

Business recommendations based on insights.

📈 Key Insights

Female customers generated slightly higher total revenue.

Subscribed customers had higher average spend and retention.

Products with discounts didn’t always lead to higher order value.

Express shipping correlated with larger basket sizes.

Loyal customers (10+ past purchases) contributed the majority of revenue.

▶️ How to Run the Project
1. Clone Repository
git clone https://github.com/yourusername/customer-behavior-analysis.git
cd customer-behavior-analysis

2. Set Up Environment

Install dependencies:

pip install -r requirements.txt

3. Run Notebook
jupyter notebook customer_behav_analysis.ipynb

4. Run SQL Queries

Open your database client (PostgreSQL/MySQL/SQL Server).

Import the cleaned dataset into a table named customer.

Execute the queries from customer_behavior_sql_queries.sql
.

5. View Power BI Dashboard

Open customer_behavior_dashboard.pbix in Power BI Desktop.

Update data connections if needed.

6. View Presentation

Open the Gamma link or file to view the final interactive report.

💡 Results

✅ Clean and reliable dataset ready for advanced analytics.
✅ SQL-based insights validating behavioral hypotheses.
✅ Interactive Power BI dashboard for stakeholders.
✅ Executive summary created using Gamma for business storytelling.
