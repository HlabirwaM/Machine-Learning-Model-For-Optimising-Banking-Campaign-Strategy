# Machine-Learning-Model-For-Optimising-Banking-Campaign-Strategy

This project involves machine learning with the objective of creating a predictive model capable of determining whether a customer will subscribe to a financial product (specifically, a term deposit) using 
data obtained from a Portuguese bank. The entire process adheres to the Cross-Industry Standard Process for Data Mining, with meticulous documentation at each stage. The primary aim is to showcase a comprehensive grasp 
of applying machine learning techniques to address genuine business challenges.

# Step 1: Business Understanding

### Objective
*  Gain a comprehensive understanding of the business problem, define project goals, and explore factors influencing customer subscription behavior.
  
### Key Components

#### Problem Definition:
* Articulate the task: Predict customer subscription ('yes' or 'no') to a financial product, specifically a term deposit, in a Portuguese bank.
* Dive into understanding the factors influencing customer subscription decisions.

### Strategic Business Objectives:
* Develop a predictive model for customer subscriptions.
* Uncover insights into the factors that impact customer subscription behavior.
* Optimize campaign costs while maximizing subscriptions to increase overall income.

### Data Mining Goals:
* Develop a predictive model that accurately classifies customers into 'yes' or 'no' categories.
* Identify and analyze key factors influencing customer subscription decisions.

#### Expected Outcomes
* A precise definition of the business problem with a focus on customer subscription insights.
* Strategic alignment with business objectives, including campaign cost optimization and income maximization.
* In-depth understanding of factors influencing customer subscription behavior, enabling data-driven decision-making.

# Step 2: Data Understanding

### Data Source and Overview
We leverage previous campaign data related to subscribing to a term deposit for a prominent Portuguese bank. This dataset is sourced from Kaggle, presented in CSV format, and consists of two distinct datasets: 'train.csv' and 'test.csv.'

#### Train Data:
* Rows: 45,211
* Columns: 18
* Ordering: Chronological (from May 2008 to November 2010)
#### Test Data:
* Rows: 4,521
* Columns: 18
* Selection: 10% of examples (randomly chosen from 'train.csv')

### Detailed Column Descriptions

* Age (numeric)
* Job: Type of job (categorical: admin, unknown, unemployed, management, housemaid, entrepreneur, student, blue-collar, self-employed, retired, technician, services)
* Marital Status: Marital status categorical: married, divorced, single; note: divorced means divorced or widowed)
* Education: Education level (categorical: unknown, secondary, primary, tertiary)
* Default: Credit default status (binary: yes/no)
* Balance: Average yearly balance in euros (numeric)
* Housing Loan: Has a housing loan? (binary: yes/no)
* Personal Loan: Has a personal loan? (binary: yes/no)

### Related to the Last Contact of the Current Campaign

* Contact: Communication type (categorical: unknown, telephone, cellular)
* Day: Last contact day of the month (numeric)
* Month: Last contact month of the year (categorical)
* Duration: Last contact duration in seconds (numeric)

### Other Attributes

* Campaign: Number of contacts performed during this campaign for this client (numeric, includes the last contact)
* Pdays: Number of days passed since the client was last contacted from a previous campaign (numeric, -1 means not previously contacted)
* Previous: Number of contacts performed before this campaign for this client (numeric)
* Poutcome: Outcome of the previous marketing campaign (categorical: unknown, other, failure, success)

### Output Variable (Desired Target)

* Y - Subscribed a Term Deposit: Binary ('yes' or 'no')

### Missing Attribute Values
* None

### Exploratory Data Analysis (EDA)

Intensive EDA of the data has been conducted using R and SQL. Leveraging these tools, we gained valuable insights into the dataset's characteristics, distributions, and potential correlations. Additionally, a PowerBI dashboard has been developed, providing an interactive and visual representation of key findings.

The data, already in a clean format, facilitated a smooth EDA process, allowing us to dive deep into understanding patterns and trends.

## Data source citation: Citation

This dataset is publicly available for research. It has been picked up from the UCI Machine Learning with random sampling and a few additional columns. S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014.
