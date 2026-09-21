
# 💳 Credit Card Financial Analytics Dashboard

## 📌 Overview

The **Credit Card Financial Analytics Dashboard** is a data analytics and business intelligence project designed to analyze credit card customer information and transaction data.

The project uses **PostgreSQL and SQL** for data storage and analysis, along with **Microsoft Power BI** to create interactive dashboards and visualize financial and customer-related insights.

The dashboard provides insights into revenue, transaction trends, customer demographics, card categories, and customer financial behavior.

---

## 🎯 Project Objectives

- Analyze credit card customer and transaction data.
- Understand revenue and transaction trends.
- Examine customer demographics and card categories.
- Identify patterns in customer spending and financial activity.
- Build interactive dashboards using Power BI.
- Perform SQL-based data analysis.
- Develop practical data analytics and business intelligence skills.

---

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| PostgreSQL | Database management and data storage |
| SQL | Data querying and analysis |
| Microsoft Power BI | Interactive dashboards and visualization |
| CSV | Dataset storage and data import |
| Git | Version control |
| GitHub | Project hosting and documentation |

---

## 📂 Project Structure

```text
Credit_Card_Financial_Dashboard/
│
├── README.md
│
├── credit_card.csv
├── customer.csv
├── cc_add.csv
├── cust_add.csv
│
├── SQL Query - Financial Dashboard Data.sql
│
├── Credit Card Financial Dashboard - Customer.pbix
├── Credit Card Financial Dashboard - Transaction.pbix
├── Credit Card Financial Weekly Dashboard.pbix
│
└── images/
    ├── transaction_report.png
    ├── customer_report.png
    └── weekly_analysis.png
```

> **Note:** Update the filenames in this structure to match the exact filenames uploaded to your repository. The PBIX filenames above are examples based on the dashboard file categories.

---

## 📊 Dataset

The project uses customer-related and credit card transaction datasets.

### 1. Customer Data

The customer dataset contains information such as:

- Customer demographics
- Education level
- Marital status
- Customer occupation
- Customer age
- Income
- Customer satisfaction score
- Dependent count
- Customer acquisition details

### 2. Credit Card Transaction Data

The credit card transaction dataset contains information such as:

- Card category
- Annual fees
- Credit limit
- Transaction amount
- Transaction count
- Interest earned
- Revenue-related metrics
- Expenditure type
- Card usage type
- Transaction trends

### 3. Additional Data

Additional datasets are used for weekly analysis and customer-related information.

The CSV datasets are imported into PostgreSQL and connected to Power BI for analysis and visualization.

---

## 🗄️ Database Structure

The project uses PostgreSQL to store and analyze the data.

### Primary Tables

- `public.cc_details` – Credit card and transaction-related information.
- `public.cust_details` – Customer-related information.

> **Note:** Confirm the exact table names in your PostgreSQL database before final submission. The names above reflect the tables visible in your Power BI model.

The tables are connected using the `Client_Num` field to support combined customer and transaction analysis.

---

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Inspection
      ↓
CSV Dataset Preparation
      ↓
PostgreSQL Database Setup
      ↓
Data Import into PostgreSQL
      ↓
SQL Query Execution
      ↓
Power BI Data Connection
      ↓
Data Modeling and Relationships
      ↓
Dashboard Development
      ↓
Data Visualization and Analysis
      ↓
GitHub Documentation
```

### Workflow Steps

1. Collect and inspect the CSV datasets.
2. Create the PostgreSQL database and required tables.
3. Import customer and credit card data.
4. Execute SQL queries for data analysis.
5. Connect PostgreSQL data to Power BI.
6. Create relationships between relevant tables.
7. Develop interactive dashboard visualizations.
8. Analyze financial and customer-related insights.
9. Document the project and upload files to GitHub.

---

## 📈 Dashboard Features

The Power BI report contains three analysis areas.

### 1. Credit Card Transaction Report

The transaction dashboard provides insights into credit card transaction performance.

**Key metrics:**

- Total Revenue
- Total Interest Earned
- Total Transaction Amount
- Total Transaction Count

**Visualizations include:**

- Revenue by Card Category
- Quarterly Revenue and Transaction Count
- Revenue by Expenditure Type
- Revenue by Education Level
- Revenue by Customer Job
- Revenue by Card Usage Type
- Revenue by Gender and other available categories

**Interactive filters include:**

- Card category
- Gender
- Quarter
- Week start date

---

### 2. Credit Card Customer Report

The customer dashboard focuses on customer demographics and financial behavior.

**Key metrics:**

- Total Revenue
- Total Interest Earned
- Income
- Customer Satisfaction Score

**Visualizations include:**

- Revenue by Customer Job
- Revenue by Salary Group
- Revenue by Top States
- Revenue by Education Level
- Revenue by Age Group
- Revenue by Marital Status
- Revenue by Gender
- Customer-related financial analysis

**Interactive filters include:**

- Quarter
- Card category
- Card usage type
- Gender
- Week start date

---

### 3. Weekly Financial Analysis

The weekly analysis page focuses on financial trends and performance comparisons.

**Analysis includes:**

- Weekly revenue
- Previous week revenue
- Current week revenue
- Revenue growth percentage
- Delinquent account analysis
- Customer job-based activation analysis
- Weekly transaction trends

The weekly dashboard supports the analysis of changes in financial performance over time.

---

## 🖼️ Dashboard Preview

### 1. Credit Card Transaction Report

![Credit Card Transaction Report](images/transaction_report.png)

### 2. Credit Card Customer Report

![Credit Card Customer Report](images/customer_report.png)

### 3. Weekly Financial Analysis

![Weekly Financial Analysis](images/weekly_analysis.png)

> Add your actual Power BI screenshots to the `images` folder using the filenames specified above.

---

## 🧮 SQL Analysis

SQL is used to support data exploration and analysis.

The project includes SQL queries related to:

- Revenue analysis
- Transaction analysis
- Customer information
- Weekly financial performance
- Card category analysis
- Customer-related metrics

The SQL query file is included in the repository for reference.

---

## 🚀 How to Run the Project

### Prerequisites

Install the following tools:

- PostgreSQL
- Microsoft Power BI Desktop
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/Astha13579/Credit_Card_Financial_Dashboard.git
```

Navigate to the project directory:

```bash
cd Credit_Card_Financial_Dashboard
```

### Step 2: Prepare the Dataset

- Review the CSV files included in the repository.
- Verify the column names and data formats.
- Ensure the required datasets are available.

### Step 3: Set Up PostgreSQL

1. Open PostgreSQL or pgAdmin.
2. Create a database for the project.
3. Create the required tables.
4. Import the CSV datasets into the appropriate tables.
5. Execute the SQL queries provided in the repository.

### Step 4: Open the Power BI Dashboard

1. Open Microsoft Power BI Desktop.
2. Open the final `.pbix` file.
3. Verify the data source connections.
4. Update the data source paths if required.
5. Refresh the dataset.
6. Explore the dashboard pages and interactive filters.

> **Important:** The dashboard may require the original data source or updated connection settings when opened on another computer.

---

## 📌 Key Insights and Analysis Areas

The dashboard supports analysis of:

- Revenue and interest earned
- Transaction amount and transaction count
- Card category performance
- Customer job and income patterns
- Customer demographics
- Quarterly and weekly revenue trends
- Customer satisfaction
- Delinquent account distribution

The dashboard is designed to support exploratory analysis and business reporting using the available datasets.

---

## 🎓 Key Learning Outcomes

Through this project, I developed practical experience in:

- Data analysis using SQL.
- Working with PostgreSQL databases.
- Importing and managing CSV datasets.
- Connecting data sources to Power BI.
- Building interactive dashboards.
- Creating charts, tables, and KPI cards.
- Analyzing customer and transaction data.
- Developing business intelligence and reporting skills.
- Managing project files using Git and GitHub.

---

## 🔮 Future Improvements

Potential future improvements include:

- Customer segmentation analysis.
- Additional Power BI dashboard pages.
- Improved data validation and documentation.
- Advanced SQL analysis.
- Customer spending pattern analysis.
- Additional financial performance metrics.
- More interactive reporting features.

---

## 👩‍💻 Author

**Astha**

GitHub: [Astha13579](https://github.com/Astha13579)

---

## ⭐ Project

This project demonstrates the use of PostgreSQL, SQL, and Power BI to develop an interactive credit card financial analytics dashboard.
