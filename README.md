# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

This project analyzes customer churn for a telecom company using **SQL Server, Power BI, and Excel**. The dataset contains **7,043 customer records** with demographic, service usage, billing, contract, and churn information.

The objective is to identify customer churn patterns, understand key churn drivers, and provide actionable insights to support customer retention.

---

## 🎯 Project Objectives

- Identify patterns that differentiate churned and retained customers.
- Analyze the key factors contributing to customer churn.
- Calculate important business KPIs related to churn and revenue.
- Build interactive Power BI dashboards for business reporting.
- Provide data-driven recommendations to improve customer retention.

---

## 🗂️ Dataset

**Source:** Kaggle

- **Total Records:** 7,043
- **Attributes:** 23
- **Target Variable:** Churn (Yes/No)

### Key Data Categories

- **Demographics:** Gender, Senior Citizen, Partner, Dependents
- **Services:** Phone Service, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming
- **Billing & Contracts:** Monthly Charges, Total Charges, Payment Method, Contract Type, Paperless Billing
- **Support:** Administrative and Technical Tickets

---

## 🛠️ Tools & Technologies

- **SQL Server** – Data cleaning, transformation and analysis
- **Power BI** – Data modeling, DAX, KPI analysis and dashboards
- **Microsoft Excel** – Preliminary data validation and analysis

---

## 🔄 Project Workflow

### 1. SQL Server

- Imported the raw telecom customer dataset into SQL Server.
- Created staging and cleaned tables.
- Handled missing and NULL values.
- Converted problematic data types.
- Performed exploratory SQL queries.
- Analyzed customer segments, churn patterns and revenue.

### 2. Power BI

- Imported the cleaned SQL Server data into Power BI.
- Performed data transformations and categorization.
- Created calculated measures using DAX.
- Developed KPIs for churn, retention and revenue.
- Built interactive dashboards for customer analysis.

### 3. Excel

- Performed preliminary data checks.
- Validated dataset values and structure.
- Used Excel for basic data inspection before analysis.

---

## 📈 Key KPIs

| KPI | Value |
|---|---:|
| Total Customers | 7,043 |
| Churned Customers | 1,868 |
| Churn Rate | 26.5% |
| Average Monthly Charges | $64.8 |
| Total Revenue | $16.1M |

---

## 🔍 Key Insights

- Fiber Optic customers showed a relatively high churn rate.
- Electronic Check users showed higher churn compared with several other payment methods.
- Customers with long-term contracts showed lower churn levels.
- Customers with partners or dependents showed lower churn levels.
- Auto-pay customers showed lower churn compared with Electronic Check users.
- Adoption of services such as Online Security, Online Backup, Device Protection and Tech Support was relatively low among churned customers.
- Churn rates were broadly similar across male and female customers.

---

## 💡 Business Recommendations

### Service Improvement
- Investigate service quality, pricing and downtime concerns among high-churn segments.
- Consider loyalty offers and bundled services for high-risk customer groups.

### Payment Optimization
- Encourage customers to adopt auto-pay payment methods.
- Consider suitable incentives for customers switching from Electronic Check.

### Contract Strategy
- Promote long-term contracts through discounts and bundled services.
- Provide retention offers for customers approaching contract renewal.

### Service Adoption
- Increase awareness of Online Security, Backup, Device Protection and Tech Support.
- Consider introductory trials or bundled offers to increase service adoption.

---

## 📊 Power BI Dashboard

The project includes interactive dashboards covering:

### Overall Customer Dashboard
- Total Customers
- Churned Customers
- Churn Rate
- Revenue
- Customer Segments
- Service and Contract Analysis

### Churned Customer Dashboard
- Churn by Internet Service
- Churn by Payment Method
- Churn by Contract
- Churn by Demographics
- Service Adoption Analysis

---

## 📁 Project Structure

```text
Telecom-Customer-Churn-Analysis/
│
├── README.md
│
├── SQL/
│   └── Telecom_Customer_Churn.sql
│
├── PowerBI/
│   └── Telecom_Customer_Churn.pbix
│
├── Excel/
│   └── Telecom_Customer_Churn.xlsx
│
├── Dataset/
│   └── dataset.csv
│
└── Images/
    ├── dashboard-overview.png
    └── churn-dashboard.png
