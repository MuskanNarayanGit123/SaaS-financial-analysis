# ![saas (1)](https://github.com/user-attachments/assets/e4f45085-81c5-4e66-8741-546531412376) SaaS Financial Performance Analysis

## 💼 Project Overview
This project analyzes the financial performance of a SaaS (Software-as-a-Service) company by comparing budgeted financial expectations with actual outcomes. It aims to provide clear, data-driven insights into revenue trends, cost overruns, and operational efficiency over time.

## 🎯 Objectives
To answer key questions that provide a clear understanding of:
- Whether the company spent more or less than planned
- Monthly profitability trends
- Revenue sources, top clients, and seasonal trends
- Major cost centers, top vendors, and budget overruns
- Patterns and variances between budgeted and actual figures

## 🛢 Data Overview
The dataset includes actual and budgeted income and expenses from FY 2022 to 2024.

### 1. Transactions
Contains monthly financial records, including client-level revenue and vendor expenses.

  - **Id:** Unique identifier for the transaction
  - **Date:** Date of the transaction
  - **COD_Account:** Code representing the financial account
  - **Account:** Description of the financial account
  - **Short_Class:** Short classification label
  - **Class:** Full classification category
  - **Transaction_Type:** Type of transaction
  - **Name:** Name of the client or vendor
  - **Memo/Description:** Description or memo for the transaction
  - **Revenue/Expenses:** Indicates if the transaction is revenue or expense
  - **Amount:** Monetary value of the transaction

### 2. Budget Data
Contains monthly planned revenue and expenses categorized by account.

  - **Id:** Unique identifier for the budget record
  - **Date:** Date of the budget entry (typically month-end)
  - **COD_Account:** Code representing the financial account
  - **Account:** Description of the financial account
  - **Short_Class:** Short classification label
  - **Class:** Full classification category
  - **Revenue/Expenses:** Indicates if the budget item is revenue or expense
  - **Budget:** Planned or estimated monetary amount for the account

### 3. Accounts
Provides detailed information about financial accounts.

  - **Id:** Unique identifier for the financial account
  - **COD_Account:** Code representing the financial account
  - **Account:** Description of the financial account
  - **Revenue/Expenses:** Indicates if the account is related to revenue or expense
  - **Level 01:** High-level category (Income, COGS, Operating Expenses, Other Income, Other Expenses)
  - **Level 02:** Sub-category (Advertising & Marketing, Recurring Income, Payroll, SaaS COGS, Travel & Entertainment)

The dataset is fully accessible on the FP20 Analytics website and can be viewed via the [link](https://fp20analytics.com/live-challenge/)

## 📖 What’s Inside
This repository includes a PDF version of the Power BI report hosted on the Power BI Service. Use the link below for a quick preview.

- [Dashboard as PDF](https://github.com/MuskanNarayanGit123/SaaS-financial-analysis/blob/main/SaaS%20Financial%20Analysis%20Dashboard.pdf)

## 👩‍💻 Tech Stack
- **Data Visualization:** Power BI
- **Data Analysis:** Power BI, Excel
- **Data Modeling:** Star Schema
- **Tools:** Excel, Power BI Desktop, Power BI Service and Canva

## 🛠️ Data Model Overview
![image](https://github.com/user-attachments/assets/2fddb06e-11f6-4277-82a4-07697cd63396)

## 📷 Dashboard Preview

### 💹 Financial Overview
![Screenshot 2025-05-28 000258](https://github.com/user-attachments/assets/5f48738d-36c2-404d-9f94-a7a2609c311b)

### 💰 Revenue Analysis
![Screenshot 2025-05-28 000326](https://github.com/user-attachments/assets/c8ff05b2-f5de-4a9c-becd-52e3a98397aa)
![Screenshot 2025-05-28 000440](https://github.com/user-attachments/assets/b5819133-0b4f-4f86-a839-a740d84eaf2c)

### 💸 Expense Analysis
![Screenshot 2025-05-28 000347](https://github.com/user-attachments/assets/471ebea5-915f-4d9b-a16f-3818261977f9)
![Screenshot 2025-05-28 000418](https://github.com/user-attachments/assets/bd2c18c4-8c35-4f3a-a1ff-eaf7ce284a5c)

## 💡 Key Insights

### 📈 Strong Revenue Growth:
Revenue grew from ₹3.18M in 2022 to ₹8.68M in 2024 — a 173% increase with steady year-over-year growth. December consistently showed revenue spikes, likely due to clients using leftover budgets or finalizing Q4 goals. January, in contrast, saw a slowdown — possibly due to delayed budgets or fewer new signups.

### 👥 Client Mix Shift:
In 2022 and 2023, GlobalTech was the top contributor. But in 2024, aggregated SMB clients took the lead, contributing ₹2.24M (26%). Still, GlobalTech remained the most valuable individual client with ₹1.46M.

### 🔁 Recurring Revenue Dominance:
Recurring SaaS revenue grew 227% to ₹7.2M by 2024, forming 83% of total revenue. In contrast, non-recurring (product-based) revenue only rose 51%, highlighting the company’s shift toward predictability and stability.

### 📉 Budget Misses:
Most months exceeded revenue goals, except February and November 2024, which missed targets by ₹12.25K and ₹15.70K respectively — small but worth further investigation.

### ⚠️ June–July 2022 Cost Spike:
A revenue jump of 87% (driven by Various SMB acquisitions) led to:
COGS surge of ~2277%
OPEX surge of ~1192%
This was driven by more vendors, increased product costs, and rising salaries.

### 💲 Expense Breakdown (2024):
Salary & Wages accounted for 57% of total expenses (₹4.57M to ADP alone).
Salaries rose 116% in 2023 but were controlled in 2024 with just a 9% increase.
Web Domain & Hosting fees consistently exceeded budget.

### 🏢 Departmental Spending (2024):
Although all revenue was booked under General & Admin, the expense split was:
G&A: 41%
Sales & Marketing: 27%
R&D: 19%
Suggests balanced cost-sharing across strategic functions.

### 📉📈 Profitability Turnaround:
In 2023, despite 92% revenue growth, high COGS (+135%) and OPEX (+105%) caused Net Profit Margin to fall to -22.41%.
In 2024, revenue grew 42%, while costs were restrained:
Gross Margin improved 4%
Operating Income rose 134%
Net Profit Margin recovered to +3.47%, reflecting strong financial discipline.

## 📝 Recommendations

- Focus on upselling and retention within the SaaS segment to deepen recurring revenue, which already contributes 83%.
- Implement client-level tracking for SMBs to monitor silent churn and identify high-value accounts.
- Offer Q4 renewal incentives or staggered billing plans to reduce revenue seasonality between December and January.
- Set cost-control checks during growth spikes to avoid disproportionate rises in COGS and OPEX.
- Explore automation or outsourcing options to manage Salary & Wages, which make up 57% of total expenses.
- Maintain cost discipline from 2024 to keep profitability stable as revenue scales.

## 📎 Links   
📊 [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiN2ZlMTUzNjItZDYxOC00MjY3LWFjMjYtMjUyYjZiYWQ3YjMyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
