# Bank Loan Report – Power BI Project

A comprehensive Business Intelligence (BI) report built using **Power BI** to analyze and monitor loan applications, funding, repayments, and borrower metrics. This project helps banks and financial institutions make data-driven decisions by providing insights into loan portfolio performance and borrower behavior.

---
## Repository Structure
- `Bank_Loan_Report.pbix` – Power BI dashboard file
- `Terminologies.md` – Definitions of all dataset fields
- `Problem_Statement.md` – Business problem and reporting requirements
- `README.md` – Project overview
---
##  Domain Knowledge
The project is based on real-world banking operations. It covers:
- Loan application and funding lifecycle
- Key borrower information and financial indicators
- Metrics like DTI (Debt-to-Income Ratio), interest rates, and loan term
- Differentiation between Good vs. Bad Loans
Details are provided in [Domain_Knowledge.md](Domain_Knowledge.md).
---
## Key Features
### Dashboards Included:
#### 1. Summary Dashboard
Provides a high-level snapshot using KPIs:
- Total Loan Applications (including Month-to-Date & MoM changes)
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI

**Good vs Bad Loan KPIs**:
- Application %, Funded Amount, and Amount Received by loan status

**Loan Status Grid**:
- Summary metrics by loan status category (e.g., Fully Paid, Current, Charged Off)

---

#### 2. Overview Dashboard
Interactive visualizations for deeper analysis:
- Monthly Trends (Line Chart)
- State-Wise Lending (Filled Map)
- Loan Term Distribution (Donut Chart)
- Employment Length Analysis (Bar Chart)
- Loan Purpose Breakdown (Bar Chart)
- Home Ownership Impact (Tree Map)

Each visual supports drill-through functionality and tooltips.

---

#### 3. Details Dashboard
Provides granular data in table format for all loan records:
- Loan ID, Amount, Interest Rate, Income, DTI, etc.
- Useful for audits and operational tracking

---

## 📚 Documentation

- [Terminologies.md](Terminologies.md): Explanation of all dataset fields
- [Problem_Statement.md](Problem_Statement.md): Dashboard and visual requirements

---

##  Tools & Technologies

- Power BI Desktop
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- Excel/CSV as data source

---

##  Exporting the Report

To export the report to PDF:

- **Power BI Desktop**:  
  `File > Export > Export to PDF`

- **Power BI Service**:  
  Open report → `dashboards/exported`

📁 Exported files are saved in your browser’s default download folder:
- Example: `C:\Users\<YourName>\Downloads`



