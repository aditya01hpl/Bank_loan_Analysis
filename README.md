# Bank_loan_Analysis

Monitoring and evaluating key performance indicators (KPIs) pertaining to loan applications and disbursements are part of this Analytics Project. Average Interest Rate, Average Debt-to-Income Ratio (DTI), Total Loan Applications, Total Funded Amount, and Total Amount Received are among the KPIs. In order to give information about the performance of the loan portfolio and the financial stability of the borrowers, each indicator is tracked on a month-to-date (MTD) and month-over-month (MoM) basis.

The project has distinct KPIs for each category to distinguish between good and bad loans. To facilitate data-driven decision-making, a complete Loan Status Grid View is developed to classify and report on these parameters.

---

## Table of Contents

- [Objectives](#objectives)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Key Insights and Findings](#key-insights-and-findings)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Future Work](#future-work)
- [Principal Visualizations](#principal-visualizations)
- [Data Visualization Interfaces](#data-visualization-interfaces)
- [Terminologies Used in Data](#terminologies-used-in-data)
- [Getting Started](#getting-started)
- [Contribution](#contribution)
- [Conclusion](#conclusion)
- [MIT License](#mit-license)

## Objectives

- Provide a comprehensive assessment of the bank's loan portfolio performance, identifying strengths and areas for improvement.
- Discover trends and patterns in loan applications, approval rates, and repayment statuses to optimize lending strategies.
- Evaluate financial health indicators such as Total Funded Amount, Average Interest Rate, and Loan Status to gauge portfolio stability and profitability.
- Support strategic decision-making for enhancing the bank's credit and loan offerings, ensuring alignment with market demands and customer needs.

---

## Data Source

The project is based on a comprehensive [dataset](https://github.com/virajbhutada/Bank-Loan-Analysis-SQL-PowerBI-Excel-Tableau/blob/main/data/financial_loan.csv) stored in SQL Server, encompassing various aspects of bank loans, including loan amounts, issue dates, interest rates, DTI ratios, and loan statuses.

---


## Methodology

Our approach to analyzing the bank loan data involved a multi-step, systematic process designed to ensure thorough data examination and insightful visualization. Below, we outline each stage of our methodology:

### Data Ingestion and Database Creation:

- **Objective**: Establish a robust foundation for data storage and retrieval.
- **Process**: A relational database was created in Microsoft SQL Server to store comprehensive loan data, ensuring data integrity and accessibility.

### Data Analysis and SQL Queries:

- **Objective**: Extract meaningful insights and key performance indicators (KPIs).
- **Process**: SQL queries were meticulously developed to retrieve essential KPIs, including total and monthly loan applications, funded amounts, and average interest rates. This step facilitated the identification of critical trends and performance metrics.

### Data Processing in Excel:

- **Objective**: Perform initial data cleaning and preliminary analysis.
- **Process**: The dataset underwent further cleaning and processing in Excel, which included data validation and the generation of preliminary insights. This step ensured the accuracy and reliability of the data before more advanced analysis.

### Categorization of Loans:

- **Objective**: Classify loans based on repayment performance.
- **Process**: Loans were categorized into 'Good' or 'Bad' based on their repayment status. This classification provided a clear distinction between performing and non-performing loans, which is crucial for risk assessment and management.

### Temporal and Categorical Analysis:

- **Objective**: Examine the data across various dimensions and time frames.
- **Process**: Detailed analysis was conducted based on multiple factors, including issue month, state, loan term, employee length, loan purpose, and home ownership status. This multifaceted analysis enabled a comprehensive understanding of the factors influencing loan performance.

### Visualization:

- **Objective**: Transform data into actionable visual insights.
- **Process**: The results from the SQL queries were visualized using Power BI. These visualizations were designed to ensure data consistency and to provide a clear, graphical representation of the findings. This step was critical for communicating insights effectively to stakeholders.

---


## Key Insights and Findings

- **Total Loan Applications**: Detailed breakdown of total loan applications, including distinctions between Month-To-Date (MTD) and Previous Month-To-Date (PMTD) applications, providing insights into monthly application trends.

- **Total Funded Amount vs. Amounts Received**: Analysis of the bank's liquidity and loan performance, comparing total funded amounts with actual amounts received, highlighting discrepancies and potential financial adjustments.

- **Average Interest Rate and DTI (Debt-to-Income Ratio)**: Examination of borrower financial health through average interest rates and DTI ratios, aiding in assessing borrowers' ability to manage debt obligations.

- **Loan Categorization**: Segmentation of loans into 'Good' and 'Bad' categories based on repayment status, offering a comprehensive view of the loan portfolio's risk profile and potential credit losses.

- **Detailed Breakdowns by Various Factors**: In-depth analysis by loan status, purpose, state, term, and other factors to identify underlying patterns and trends influencing loan performance and customer behavior.

---


## Tools and Technologies Used

- **SQL Management Server**: Used for database management, querying, and data analysis. SQL queries were crucial in extracting key metrics and insights from the loan dataset.
  
- **Excel**: Utilized for data cleaning, processing, and conducting preliminary analyses. Excel provided a platform for validating data integrity and performing initial calculations.

- **Power BI**: Employed for data visualization and dashboard creation. Power BI enabled the creation of interactive dashboards that visualize loan portfolio performance and trends.

---

## Future Work

- **Predictive Modeling**: Implement machine learning models to forecast loan defaults based on historical data patterns and borrower characteristics.
  
- **Demographic Analysis**: Conduct detailed demographic studies to better understand customer segments and tailor loan products to specific market needs.
  
- **Impact of Loan Terms**: Perform deeper analyses on loan repayment rates based on different loan terms (e.g., short-term vs. long-term loans) to optimize loan structures and minimize default risks.

---

## Principal Visualizations

Here are several Screenshots of PowerBI Dashboard:

### Summary Panel
![image](https://github.com/user-attachments/assets/50f4e839-bcad-438c-bedb-9cd78f1c3947)

### Overview Display
![image](https://github.com/user-attachments/assets/5405c162-79d1-4884-8aab-32e0875a5e9d)

### Detailed Insights Interface
![image](https://github.com/user-attachments/assets/d080b706-85cc-4f4c-acdc-23cf701d3193)


ALL indepth SQL Queries to analysis on finansial_data are mentioned in report.

you can find the dash link here : [here!!](https://vitacin-my.sharepoint.com/:u:/g/personal/aditya_mishra2020b_vitstudent_ac_in/ER6ye4cT5dVLojzV6WfO5LsBjq3mNqf8qODDEfsGwGA7VA?e=2bDhS6)





