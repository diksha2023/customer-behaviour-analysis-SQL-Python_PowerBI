# customer-behaviour-analysis-SQL-Python_PowerBI
The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

- Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

- Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

- Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

- Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually communicates insights and     actionable recommendations to stakeholders.

---

## Dataset

- **Total Records:** 3,900 purchases  
- **Total Features:** 18 columns  

### Data Includes
- Customer demographics (Age, Gender, Location)  
- Purchase details (Item, Category, Amount, Season)  
- Behavioral attributes (Discount usage, Subscription status, Purchase frequency)  
- Ratings and shipping information  

### Data Quality Notes
- Missing values were found in the **Review Rating** column and handled during data cleaning  
- Columns were standardized for consistency and readability  

---

## Tools & Technologies Used

- **Python** (Pandas, NumPy, Matplotlib)  
- **MySQL** (SQL queries for business analysis)  
- **Power BI** (Interactive dashboard)  
- **Jupyter Notebook**  
- **Gamma AI** (Presentation)  
- **MS Word / PDF** (Project report)  

---

## Project Workflow & Steps

### Data Loading & Cleaning (Python)
- Loaded the dataset using Pandas  
- Checked data structure, types, and summary statistics  
- Handled missing values using median-based imputation  
- Standardized column names (snake_case)  
- Performed feature engineering (age groups, purchase frequency)  
- Removed redundant columns after validation  

### Exploratory Data Analysis (EDA)
- Analyzed purchase trends across product categories  
- Studied customer demographics and spending behavior  
- Identified high-value customers and discount usage patterns  

### SQL Analysis (MySQL)
The cleaned dataset was loaded into a MySQL database to answer key business questions, including:

- Revenue comparison by gender  
- High-spending customers using discounts  
- Top-rated products  
- Subscription vs non-subscription revenue  
- Shipping type impact on purchase amount  
- Customer segmentation (New, Returning, Loyal)  
- Revenue contribution by age group  

---

## Power BI Dashboard
### Dashboard Preview
<img width="892" height="496" alt="Screenshot (195)" src="https://github.com/user-attachments/assets/0ba2afdd-964f-429f-bba4-655db0626aab" />

An interactive **Power BI dashboard** was created to visualize insights clearly and effectively.

### Dashboard Highlights
- Total customers and average purchase value  
- Revenue and sales by product category  
- Subscription status comparison  
- Revenue by age group  
- Filters for gender, category, shipping type, and subscription  

The dashboard enables stakeholders to quickly understand customer behavior and make data-driven decisions.

---

## Key Results & Insights

- Male customers contributed higher total revenue than female customers  
- Subscribers generated higher long-term value despite similar average spending  
- Express shipping users showed slightly higher purchase amounts  
- Loyal customers formed the largest customer segment  
- Young adults and middle-aged customers contributed the highest revenue  
- Certain products were highly dependent on discounts for sales  

---

## How to Use This Project
1. **Clone the repository**
2. **Open Customer_Shopping_Behavior_Analysis.ipynb notebook**

    This file contains:

      - Data Import

      - Data exploration

      - Data cleaning

      - Connection to SQL Database
  
3. **Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server**

      - Create a database in SQL

      - Run Python code to load data into SQL database
  
      - Open **customer_behavior_sql_queries.sql**
  
      - Answer Business Questions using SQL Queries 
      
4. **Connect the SQL Database to Power BI**

      - Open **customer_behavior_dashboard.pbix**
   
      - Create interactive dashboard in Power BI
  
5. **Create Project Report and Presentation**

      - Create project report
   
      - Build presentation deck using Gamma AI
