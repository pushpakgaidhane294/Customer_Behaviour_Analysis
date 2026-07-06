🛍️** Customer Behavior Analysis**
📌 Project Overview

Customer Shopping Behavior Analysis is a data analytics project that explores customer purchasing patterns, spending habits, and shopping preferences using Python, PostgreSQL, SQL, and Power BI.

The project performs data cleaning, feature engineering, exploratory data analysis (EDA), stores the processed data in PostgreSQL, and creates an interactive Power BI dashboard to generate business insights for better decision-making.

🚀 Features
Data Cleaning and Preprocessing
Missing Value Handling
Feature Engineering
Exploratory Data Analysis (EDA)
PostgreSQL Database Integration
Interactive Power BI Dashboard
Customer Purchase Analysis
Spending Pattern Analysis
Category-wise Sales Analysis
Age Group Analysis

🛠️ Tech Stack
Technology	Purpose
Python	Data Analysis
Pandas	Data Cleaning & Manipulation
PostgreSQL	Database Storage
SQLAlchemy	Database Connection
SQL	Querying Data
Power BI	Dashboard & Visualization
Jupyter Notebook	Analysis Environment

📂 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behaviour_Analysis.ipynb
├── customer_shopping_behavior.csv
├── customer_behaviour_analysis.sql
├── customer_behavior_dashboard.pbix
├── README.md

📊 Dataset
The dataset contains customer shopping information such as:
Customer Age
Gender
Category
Purchase Amount
Payment Method
Review Rating
Discount Applied
Shipping Type
Purchase Frequency
Subscription Status
Season
Location

🧹 Data Preprocessing
The following preprocessing steps were performed:
Checked missing values
Filled missing Review Ratings using median values
Renamed column names
Created Age Groups
Converted Purchase Frequency into numerical days
Removed duplicate information
Prepared data for database storage

⚙️ Feature Engineering
New features created:
Age Group
Young Adult
Adult
Middle-aged
Senior
Purchase Frequency Days
Weekly → 7 Days
Fortnightly → 14 Days
Monthly → 30 Days
Quarterly → 90 Days
Annually → 365 Days

🗄️ Database
The cleaned dataset is exported to PostgreSQL using SQLAlchemy.
Example:

df.to_sql(
    "customer",
    engine,
    if_exists="replace",
    index=False
)

📈 Dashboard Insights
The Power BI dashboard provides insights such as:
Total Sales
Average Purchase Amount
Category-wise Revenue
Customer Age Distribution
Purchase Frequency
Payment Method Analysis
Seasonal Shopping Trends
Shipping Preferences
Review Rating Analysis
Discount Impact on Purchases

💡 Business Insights
Identify top-performing product categories.
Analyze customer spending behavior.
Understand seasonal purchasing trends.
Measure the impact of discounts on sales.
Discover customer demographics.
Support data-driven business decisions.

▶️ How to Run
1. Clone the Repository
git clone https://github.com/pushpakgaidhane294/customer-shopping-behavior-analysis.git
2. Install Dependencies
pip install pandas sqlalchemy psycopg2-binary
3. Open Jupyter Notebook
jupyter notebook
4. Run the Notebook
Execute all cells in:
Customer_Shopping_Behaviour_Analysis.ipynb
5. Open Power BI Dashboard
Open
customer_behavior_dashboard.pbix
using Microsoft Power BI Desktop.

📷 Dashboard Preview
<img width="1325" height="743" alt="Screenshot 2026-07-04 160541" src="https://github.com/user-attachments/assets/e1b479c0-1886-4672-ba98-bcd2b796c077" />


🎯 Future Improvements
Customer Segmentation using Machine Learning
Sales Prediction
Customer Lifetime Value Prediction
Recommendation System
Automated ETL Pipeline


👨‍💻 Author
Pushpak Gaidhane
📊 Aspiring Data Analyst
💻 Python | SQL | Power BI | PostgreSQL
