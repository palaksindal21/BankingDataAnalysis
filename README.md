Problem Statement
Financial institutions face significant financial risks due to ineffective assessment of customer financial profiles and credit exposure. This project leverages banking risk analytics to analyze customer demographics, income, loans, deposits, credit-card balances, and risk weightings to identify high-risk customer segments and understand patterns associated with financial exposure. The objective is to transform banking data into actionable insights that support data-driven risk monitoring, customer segmentation, and informed financial decision-making.

Project Objectives
- Analyze overall banking customer and financial performance.
- Identify loan and deposit patterns across different customer segments.
- Analyze customer risk using Risk Weighting.
- Understand the relationship between customer income and financial exposure.
- Analyze credit-card balances across different risk levels.
- Compare financial activity across customer demographics and loyalty classifications.
- Identify high-risk customer segments and their financial exposure.
- Provide interactive filters for easier data exploration.

Key Dashboard Features
- Total Clients: Displays the total number of banking customers analyzed.
- Total Loan: Shows the combined loan exposure from bank loans and business lending.
- Total Deposit: Displays the total amount across bank deposits, saving accounts, and checking accounts.
- Total CC Amount: Shows the total outstanding credit-card balance.
- Saving Account Amount: Displays the total amount held in saving accounts.
- Checking Account Amount: Shows the total amount held in checking accounts.
- High Risk Customers: Identifies customers with higher risk weighting.
- Loan by Risk: Compares loan exposure across different customer risk levels.
- Deposit by Risk: Analyzes deposit amounts across risk categories.
- Risk vs Income: Analyzes the relationship between customer income and risk.
- Risk vs Credit Card Balance: Compares credit-card balances across risk levels.
- Loan by Occupation: Identifies occupations with higher loan exposure.
- Customer Risk Summary: Provides an overview of Low, Medium, and High Risk customers.
- Interactive Filters: Allows users to analyze data by risk category, nationality, occupation, loyalty classification, and fee structure.
- Drill-Through Analysis: Allows users to move from overall risk analysis to detailed customer-level information.

Data Preparation & Analysis
- Loaded the banking dataset into MySQL for structured data storage and analysis.
- Connected to the banking data and performed Exploratory Data Analysis (EDA) using Python.
- Used Pandas and NumPy for data exploration, cleaning, transformation, and statistical analysis.
- Used Matplotlib and Seaborn to visualize customer demographics, financial behavior, loans, deposits, credit-card balances, and risk patterns.
- Analyzed the relationship between Risk Weighting and key financial variables.
- Used the analyzed data to develop an interactive Power BI dashboard.
- Created DAX measures and KPIs for loan, deposit, credit-card, savings, checking accounts, and customer risk analysis.

Key Insights
- Identified customer risk patterns using the Risk Weighting variable and analyzed Low, Medium, and High Risk customer segments.
- Analyzed loan exposure across different risk levels to understand which customer groups contribute more to overall lending exposure.
- Evaluated deposit behavior across risk categories, including bank deposits, saving accounts, and checking accounts.
- Analyzed the relationship between estimated income and financial exposure to understand customer financial profiles.
- Examined credit-card balances across different risk levels to identify variations in customer credit exposure.
- Compared banking behavior across age groups, occupations, nationalities, and loyalty classifications.
- Identified customer segments with relatively higher loan, deposit, and credit-card exposure for closer risk monitoring.
- Developed an interactive dashboard to allow users to filter and drill down into specific customer and risk segments.
- Converted raw banking data into visual KPIs and analytical insights to support data-driven banking and risk-management decisions.

Tools & Technologies
MySQL – Dataset storage and SQL-based data analysis
SQL – Data querying and analysis
Python – Data analysis and preprocessing
NumPy – Numerical analysis and calculations
Pandas – Data manipulation, cleaning, and exploration
Matplotlib – Data visualization
Seaborn – Statistical data visualization
Microsoft Power BI – Interactive dashboard development
Power Query – Data transformation and preparation
DAX – KPI, financial, and risk-related calculations
Exploratory Data Analysis (EDA)
Data Visualization
Risk Analytics
Business Intelligence
