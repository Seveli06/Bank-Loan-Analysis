# End-to-End Bank Loan Analysis Project

This project focuses on end-to-end analysis of bank loan data using MS SQL Server and Power BI. It involves importing data, creating databases, writing SQL queries, and generating Power BI reports to track key loan metrics, evaluate loan performance, and monitor borrower behavior.

## Project Structure

### Part 1: MS SQL Server
- **Data Import & Database Creation**: Importing loan data and setting up the database.
- **SQL Queries**: Writing and executing SQL queries to cross-check results with Power BI calculations.

### Part 2: Power BI

#### Dashboard 1: Summary
- **KPIs Requirements**:
  1. **Total Loan Applications**: Tracks total loan applications, Month-to-Date (MTD), and Month-over-Month (MoM) changes.
  2. **Total Funded Amount**: Analyzes the total funded amount, MTD, and MoM variations.
  3. **Total Amount Received**: Tracks the total received from borrowers, MTD, and MoM changes.
  4. **Average Interest Rate**: Calculates the average interest rate and monitors MoM fluctuations.
  5. **Avg Debt-to-Income Ratio (DTI)**: Tracks the average DTI and MoM variations.

- **Good vs Bad Loan KPIs**:
  - **Good Loan**: Percentage, applications, funded amount, and received amount.
  - **Bad Loan**: Percentage, applications, funded amount, and received amount.

- **Loan Status Grid View**: A comprehensive grid view by loan status, with metrics like total loan applications, total funded amounts, MTD data, and DTI.

#### Dashboard 2: Overview
- **Charts**:
  1. **Monthly Trends by Issue Date** (Line Chart): Analyzes seasonality and long-term trends.
  2. **Regional Analysis by State** (Filled Map): Assesses regional lending activity.
  3. **Loan Term Analysis** (Donut Chart): Distribution of loans across term lengths.
  4. **Employee Length Analysis** (Bar Chart): Shows loan metrics by borrower employment length.
  5. **Loan Purpose Breakdown** (Bar Chart): Breakdown of loans by purpose.
  6. **Home Ownership Analysis** (Column Chart): Analyzes the impact of home ownership on loan applications, funded amt and amt received.

#### Dashboard 3: Details
- **Details Dashboard**: A comprehensive dashboard for accessing detailed loan data, including borrower profiles, loan performance, and key metrics.

## Technologies Used
- **MS SQL Server** for data import, database creation, and SQL queries.
- **Power BI** for data visualization and reporting.

## Repository Includes
- SQL queries for loan data analysis.
- Power BI report files for interactive visualizations and dashboards.

---

