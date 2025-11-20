Customer Shopping Behavior Analysis – Data Analytics Project
📌 Overview

This project analyzes customer shopping behavior using a structured data analytics workflow. It covers data loading, exploratory data analysis (EDA), data cleaning, SQL-based insights, and interactive dashboard development. The goal is to uncover patterns in spending, product preferences, customer demographics, and shopping trends, and present the findings through visual dashboards and a final report.

📂 Dataset

Rows: Approximately 3,900

Columns: 18

Contains:

Customer demographics (age, gender, location, subscription status)

Purchase details (item, category, season, price, size, color)

Behavioral indicators (discounts, promo codes, frequency, reviews, shipping type)

Source: Provided as a CSV file (not included due to privacy)

🛠️ Tools & Technologies
Purpose	Tools Used
Programming	Python (Pandas, NumPy, Matplotlib/Seaborn)
Database	PostgreSQL / MySQL / SQL Server
Visualization	Power BI
Reporting	MS Word / PDF
Presentation	Gamma App
Environment	Jupyter Notebook / VS Code
📘 Project Steps
1️⃣ Data Loading

Imported the dataset using pandas

Performed basic structure checks with df.info() and df.describe()

2️⃣ Exploratory Data Analysis (EDA)

Visualized customer demographics

Analyzed spending patterns and product categories

Identified correlations and behavioral trends

3️⃣ Data Cleaning

Handled missing values (imputation using median/mean)

Corrected inconsistent values

Standardized column names to snake_case

Created derived/engineered features (e.g., age groups, purchase frequency)

4️⃣ SQL Analysis

Performed SQL queries after loading cleaned data into a database:

Revenue by gender

Top-selling categories

Customer segmentation

Average purchase amount by age group

Frequency-based customer behavior

Queries were tested across PostgreSQL, MySQL, and SQL Server.

5️⃣ Dashboard Development (Power BI)

Built an interactive dashboard including:

Revenue breakdowns

Customer segments

Product category performance

Review and rating trends

Shipping preference analysis

6️⃣ Report Creation

A structured report summarizing:

Key findings

Insights from EDA

SQL-based results

Dashboard highlights

Business recommendations

7️⃣ Presentation (Gamma App)

Created a clean, modern slideshow summarizing:

Project goals

Methods

Top insights

Visual charts

Actionable recommendations

📈 Key Results & Insights

Identified high-revenue age and gender segments

Top product categories driving majority of sales

Seasonal buying patterns

Key factors influencing customer retention and reviews

Relationship between subscription status and spending

🚀 How to Run This Project
1. Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2. Install Required Python Packages
pip install -r requirements.txt

3. Run the Jupyter Notebook
jupyter notebook

4. Prepare the Database

Create a PostgreSQL/MySQL/SQL Server database

Update connection credentials in the notebook

Execute the SQL upload cell to load the dataset

5. Open the Power BI Dashboard

Open the .pbix file in Power BI Desktop

Refresh to load updated data

6. View the Report & Presentation

Open the final report.pdf / report.docx
[Customer_dashboard_pdf.pdf](https://github.com/user-attachments/files/23658232/Customer_dashboard_pdf.pdf)

View the Gamma presentation link (included in the repo)

📬 Contact

If you have questions or want to discuss this project, feel free to connect!
