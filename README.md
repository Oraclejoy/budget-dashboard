
📊 Project Report: Personal Monthly Budget Dashboard
Tools Used: Google Sheets, SUMIF, INDEX/MATCH, LARGE, Conditional Formatting, Data Visualization
Category: Personal Finance Analytics 

![Budget_Dashboard](DASHBOARD-TEMPLATE.png)
https://github.com/Oraclejoy/budget-dashboard/blob/main/DASHBOARD%20TEMPLATE.png

1. Project Overview
This project involved designing and building a fully functional Personal Monthly Budget Dashboard in Google Sheets. The goal was to create a structured, automated tool that tracks income, expenses, and savings in real time — giving users a clear financial picture at a glance.
The dashboard was built to replicate a professional budget template layout while incorporating advanced spreadsheet logic and interactive visual reporting.

2. Problem Statement
Many individuals struggle to track personal finances effectively because they either use overly complex tools or rely on manual, error-prone methods. The challenge was to build a solution that is:

Easy to use with no technical expertise required
Automated to minimize manual data entry
Visual enough to surface insights quickly
Reliable, with data protection to prevent accidental edits


3. Solution & Key Features
3.1 Budget Structure & Layout
The dashboard was structured around a clean, template-driven layout with clearly separated sections for income sources, expense categories, and savings targets. Each section feeds into a central summary panel that auto-updates as data is entered.
3.2 Formulas & Logic
SUMIF was used to automatically total income and expenses by category, pulling figures from raw data entries and mapping them to the correct budget line items — eliminating the need for manual addition.
LARGE + INDEX/MATCH array formulas were used to dynamically identify and display the top spending categories. This combination allowed the dashboard to rank expenses in real time without sorting the underlying data, keeping the raw records intact.
Protected Ranges were applied to formula cells and structural layout areas to prevent accidental overwrites, ensuring the dashboard remains stable even during regular use.
Conditional Formatting was configured to flag budget overruns visually — cells automatically change colour when spending exceeds the set limit for a category, providing an instant visual alert without any manual checking.
3.3 Data Visualization (4 Charts)
ChartPurposeDonut ChartShows budget allocation by category as a proportion of total incomeBar ChartCompares actual spending vs. budgeted amounts across all categoriesPie ChartBreaks down expense distribution for the monthSpending ChartTracks cumulative or itemised spending trends over the month
All four charts update dynamically as data is entered, turning raw numbers into actionable visual insights immediately.

4. Technical Highlights

Array formula logic using LARGE/INDEX/MATCH to surface top expenses without disturbing source data
SUMIF-driven automation for real-time category totals
Conditional formatting rules tied to budget thresholds for instant visual alerts
Data integrity controls via protected ranges on formula and layout cells
Multi-chart dashboard providing both summary and detailed spending views from a single sheet


5. Results & Impact
The completed dashboard delivers a fully automated personal finance tracking system where a user only needs to input their transactions — all calculations, rankings, alerts, and charts update automatically. Key outcomes include:

Zero manual calculation — all totals and rankings are formula-driven
Instant budget alerts — conditional formatting flags overspending in real time
Clear visual reporting — four chart types cover allocation, comparison, distribution, and trend
Data protection — protected ranges ensure the dashboard stays functional over repeated use


6. Skills Demonstrated
Google Sheets · SUMIF · INDEX/MATCH · LARGE · Array Formulas · Conditional Formatting · Data Visualization · Dashboard Design · Data Integrity · Financial Analytics
