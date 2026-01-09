# Credit Card Financial Analysis Dashboard

## Project Description
An interactive Power BI dashboard designed to provide real-time insights into credit card operations. This project integrates data from SQL databases to analyze key performance metrics, including revenue, transaction volume, and customer demographics, enabling data-driven decision-making for financial stakeholders.

---

## Technical Stack
* **Data Visualization:** Power BI Desktop 
* **Database:** SQL (PostgreSQL/SQL Server)
* **Data Modeling:** DAX (Data Analysis Expressions) 
* **Data Processing:** SQL Querying and Power Query

---

## Database Schema & ETL
The project utilizes a relational database structure consisting of two primary tables:
* **`cc_detail`**: Stores transactional data including `Card_Category`, `Annual_Fees`, `Interest_Earned`, and `Total_Trans_Amt`.
* **`cust_detail`**: Stores demographic information such as `Customer_Age`, `Gender`, `Income`, `Education_Level`, and `Customer_Job`.

Data was imported from CSV files and synchronized with Power BI to ensure real-time reporting capabilities.

---

## Key Performance Indicators (KPIs)
* **Total Revenue:** $55.4M
* **Total Interest Earned:** $7.9M 
* **Total Transaction Amount:** $45M 
* **Total Transaction Count:** 657K 
* **Total Income:** $577M 
* **Customer Satisfaction Score (CSS):** 3.19 

---

## Dashboard Insights

### 1. Transaction Report
* **Card Category Performance:** The "Blue" card is the primary revenue driver, contributing $46.2M.
* **Expenditure Patterns:** "Bills" represent the highest expenditure type ($14M), followed by "Entertainment" ($10M) and "Fuel" ($9M).
* **Usage Method:** "Swipe" transactions are the most popular, accounting for $35M in revenue compared to "Chip" ($17M) and "Online" ($3M).
* **Quarterly Trends:** Revenue peaked in Q3 at $14.2M with a transaction count of 166.6K.

### 2. Customer Report
* **Demographics:** The 40-50 age group is the most profitable segment.
* **Top States:** Texas (TX), New York (NY), and California (CA) contribute significantly to the total revenue. 
* **Job Roles:** Self-employed individuals ($14M) and Businessmen ($11M) lead in revenue contribution. 
* **Education Level:** Graduates are the largest contributor by education, accounting for $22M in revenue. 
* **Marital Status:** Married customers contribute slightly more revenue ($14M) than single customers ($13M).

---

## How to Run
1. **SQL Setup:** Execute the script in `SQL Query - Financial Dashboard Data.sql` to create the `ccdb` database and tables.
2. **Data Import:** Use the `COPY` commands within the SQL script to load your local CSV data into the tables.
3. **Power BI:** Open the Power BI file, navigate to 'Get Data', and connect to your SQL Server instance to populate the visualizations. 
