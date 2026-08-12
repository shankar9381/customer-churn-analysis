# 📊 Telco Customer Churn & Customer Profile Analysis – Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

The **Telco Customer Churn & Customer Profile Analysis** project is an interactive Power BI dashboard designed to analyze customer behavior, churn patterns, service usage, contract types, billing information, and customer retention.

The project transforms raw telecommunications customer data into meaningful business insights using **Power Query, data transformation, calculated columns, DAX measures, and interactive Power BI visualizations**.

The primary objective is to help telecom businesses understand:

- Why customers are leaving
- Which customer segments have higher churn risk
- Which services are associated with customer retention
- How contract types affect churn
- How billing and payment methods influence customer behavior
- Which customer groups require retention strategies

---

## 🎯 Business Problem

Customer churn is a major challenge for telecommunications companies.

Losing customers can reduce recurring revenue and increase the cost of acquiring new customers.

This project analyzes customer-level information to identify:

- High-risk customers
- Churn patterns
- Customer demographics
- Service adoption
- Contract behavior
- Billing patterns
- Revenue impact of churn
- Customer retention opportunities

The dashboard provides a centralized view that can support **data-driven customer retention and business decisions**.

---

## 🎯 Project Objectives

The major objectives of this project are:

1. Analyze overall customer performance.
2. Measure customer churn and retention.
3. Identify customer segments with high churn.
4. Analyze churn based on demographics.
5. Understand the impact of contract types on churn.
6. Analyze telecom service adoption.
7. Evaluate billing and payment behavior.
8. Identify high-risk customer groups.
9. Analyze revenue associated with customers.
10. Provide actionable business recommendations.

---

## 🗂️ Dataset

The project uses the **Telco Customer Churn Dataset**.

The dataset contains customer-level information related to:

### Customer Information
- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure

### Services
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

### Contract & Billing
- Contract
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges

### Customer Status
- Churn

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard & Visualization |
| Power Query | Data Cleaning & Transformation |
| DAX | Measures & Calculated Columns |
| Data Modeling | Analytical Model |
| Excel / CSV | Source Dataset |
| GitHub | Project Documentation & Version Control |

---

# 📊 Dashboard Pages

The Power BI report contains **4 major analytical pages**.

## 1️⃣ Customer Profile Analysis

This page provides an overall view of the customer base and important business KPIs.

### Key KPIs

- Total Customers
- Active Customers
- Churn Customers
- Churn Rate
- Retention Rate
- Total Revenue
- Monthly Revenue
- Average Monthly Revenue
- Average Tenure

### Analysis Includes

- Customer profile
- Churn overview
- Revenue overview
- Customer segmentation
- Customer risk analysis

---

## 2️⃣ Customer Demographics Dashboard

This page analyzes customer behavior based on demographic characteristics.

### Key Analysis

- Gender
- Senior Citizen status
- Partner status
- Dependents
- Tenure groups
- Customer segments
- Churn behavior

This helps identify demographic groups that require additional retention attention.

---

## 3️⃣ Service, Contract & Billing Analysis

This page focuses on the relationship between telecom services, contracts, and billing behavior.

### Service Analysis

- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

### Contract Analysis

- Month-to-Month
- One Year
- Two Year

### Billing Analysis

- Monthly Charges
- Total Charges
- Payment Method
- Paperless Billing
- Charge Categories

This page helps identify how service usage and contract structure relate to customer churn.

---

## 4️⃣ Business Insights & Executive Recommendations

The final dashboard page converts the analysis into business-focused insights and recommendations.

It focuses on:

- High-risk customer segments
- Churn drivers
- Retention opportunities
- Revenue impact
- Customer service strategies
- Contract-based retention
- Service-based retention

The goal is to move from **descriptive analytics to actionable business recommendations**.

---

# 🧮 DAX Measures

Several DAX measures were created to support the analysis.

### Customer KPIs

- Total Customers
- Active Customers
- Churn Customers
- Churn Rate %
- Retention Rate %

### Revenue KPIs

- Total Revenue
- Monthly Revenue
- Average Monthly Revenue
- Average Monthly Charges
- Revenue Lost Due to Churn

### Customer Analysis

- Average Tenure
- High Risk Customers
- Internet Service Customers
- Phone Service Customers
- Paperless Billing Customers

These measures allow the dashboard to dynamically respond to filters and slicers.

---

# 🔄 Data Transformation

Power Query was used for data preparation before building the dashboard.

The data preparation process included:

1. Importing the raw dataset.
2. Checking column data types.
3. Validating numerical fields.
4. Handling data quality issues.
5. Creating analytical categories.
6. Preparing customer segmentation fields.
7. Preparing tenure groups.
8. Preparing charge categories.
9. Preparing contract categories.
10. Preparing customer risk categories.

---

# 🧠 Calculated Columns

Additional calculated fields were created to improve business analysis.

### Customer Segmentation

Used to categorize customers into meaningful groups.

### Charge Category

Used to group customers based on their charges.

### Contract Category

Used to analyze customers according to their contract structure.

### Risk Category

Used to identify customers according to their potential churn risk.

### Senior Citizen Status

Provides a more readable customer classification.

### Tenure Group

Groups customers based on their relationship duration with the telecom company.

---

# 📈 Key Business Questions

The dashboard was designed to answer questions such as:

### Customer Churn

- How many customers have churned?
- What is the overall churn rate?
- What percentage of customers are retained?
- Which customer segments have the highest churn?

### Demographics

- Does customer churn differ by gender?
- Are senior citizens more likely to churn?
- Does having a partner affect customer retention?
- Does having dependents influence churn?

### Services

- Which internet services have higher churn?
- Does technical support influence retention?
- Which additional services are associated with customer loyalty?

### Contracts

- Which contract type has the highest churn?
- Are month-to-month customers more likely to leave?
- Does a longer contract improve customer retention?

### Billing

- How does monthly billing relate to churn?
- Which payment methods are commonly used by churned customers?
- Does paperless billing influence customer behavior?

### Revenue

- How much revenue is generated by customers?
- What is the average monthly revenue?
- How much revenue is associated with churned customers?

---

# 💡 Business Insights

The analysis can help telecom organizations identify customers who are more likely to churn and develop targeted retention strategies.

Potential strategies include:

- Offering incentives for customers on short-term contracts.
- Providing targeted retention offers to high-risk customers.
- Improving technical support and service experience.
- Promoting value-added services.
- Monitoring customers with increasing charges.
- Creating personalized retention campaigns.
- Encouraging longer-term contracts.
- Developing targeted strategies for high-risk customer segments.

---

# 🔄 Project Workflow

```text
Raw Telco Dataset
        ↓
Data Cleaning
        ↓
Power Query Transformation
        ↓
Data Validation
        ↓
Calculated Columns
        ↓
DAX Measures
        ↓
Power BI Data Model
        ↓
Interactive Dashboard
        ↓
Business Insights
        ↓
Retention Recommendations
