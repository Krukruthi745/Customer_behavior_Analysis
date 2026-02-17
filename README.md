his project analyzes customer shopping behavior using transactional purchase data to uncover spending patterns, customer segments, product preferences, and subscription trends. The goal is to generate actionable insights that can help businesses improve marketing strategies, product positioning, and customer retention.

Dataset

Records: 3,900 transactions

Columns: 18 features

Includes:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Category, Item Purchased, Purchase Amount, Season, Size, Color)

Shopping behavior (Discount Applied, Frequency, Previous Purchases, Review Rating, Shipping Type)

Missing Values: Review Rating column contained missing values (handled during cleaning)

Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

SQL: PostgreSQL / MySQL / SQL Server

Power BI: Interactive Dashboard & KPI visualization

Gamma: PPT creation

IDE/Notebook: Jupyter Notebook / VS Code

Project Workflow / Steps
1. Data Loading (Python)

Imported dataset using Pandas

Checked dataset structure and summary statistics

2. Exploratory Data Analysis (EDA)

Analyzed purchase distribution across categories

Checked customer demographics and spending behavior

Visualized key trends using charts

3. Data Cleaning & Preprocessing

Handled missing values (Review Rating imputation)

Renamed columns for consistency

Removed redundant columns

Verified data consistency

4. Feature Engineering

Created age groups for customer segmentation

Derived purchase frequency metrics

Prepared clean dataset for SQL analysis

5. SQL Analysis (PostgreSQL/MySQL/SQL Server)

Performed business-driven SQL queries such as:

Revenue by Gender

High spending discount users

Top-rated products

Shipping type comparison

Subscribers vs non-subscribers analysis

Discount-dependent products

Customer segmentation (New / Returning / Loyal)

Revenue contribution by age group

6. Power BI Dashboard

Built an interactive dashboard showing:

Total customers and transactions

Revenue and average purchase amount

Category-wise sales distribution

Subscription analysis

Age group revenue contribution

Discount impact insights

7. Report & Presentation

Created a detailed project report summarizing insights

Designed a PPT using Gamma for professional presentation

Dashboard Highlights (Power BI)

Key dashboard components include:

KPI Cards (Total Customers, Avg Purchase Amount, Avg Rating)

Sales by Category

Revenue by Age Group

Subscription status distribution

Gender-based revenue comparison

Results & Insights

Identified high-performing product categories and top-selling items

Analyzed impact of discounts on customer spending

Compared subscriber vs non-subscriber purchase behavior

Segmented customers based on purchase history

Found age groups contributing the highest revenue

Highlighted products most dependent on discounts

How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis

2. Install Required Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

3. Run Python Notebook / Script

Open Jupyter Notebook or VS Code

Run the Python file/notebook for EDA and cleaning

4. Load Data into SQL Database

Create a database in PostgreSQL/MySQL/SQL Server

Import cleaned dataset into a table

Run SQL queries from the sql_queries.sql file

5. Open Power BI Dashboard

Open the .pbix file in Power BI Desktop

Refresh dataset connection if needed

6. View Report & PPT

Report available in project folder

PPT created using Gamma included for presentation

Project Deliverables

✅ Cleaned Dataset
✅ SQL Query File
✅ Power BI Dashboard (.pbix)
✅ Report Document
✅ Gamma PPT Presentation

Author

Kruthi K
📍 Bangalore, India
📧 kruthikru745@gmail.com

🔗 LinkedIn: linkedin.com/in/kruthi-k-aa222725b/
💻 GitHub: github.com/Krukruthi745
