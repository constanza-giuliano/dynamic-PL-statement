# Dynamic Income Statement – Power BI

Interactive **Income Statement** built in **Power BI** with dynamic financial logic, including **gross vs net analysis**, **ARS/USD currency switching**, **$ / % views**, and **total vs average periods**. Designed with reusable **DAX measures**, secure data handling, and a focus on accurate **financial analysis** and business decision-making.

## Context
A construction company needed an interactive and reliable **Income Statement** to analyze performance across periods and currencies, while ensuring accuracy and preventing manual edits.

## Objectives
- Build a dynamic **Income Statement**
- Enable **vertical** and **horizontal analysis**
- Allow switching between **ARS / USD**
- Allow switching between **$ / %**
- Allow **Total vs Average** of selected months
- Ensure **data integrity** (no manual modification)

## Tools
- **Power BI**
- **DAX**
- **Power Query**
- **SQL (Firebird via IBExpert)**

## Key Features
- Reusable **DAX** logic using **CALCULATE**, **SWITCH(TRUE())**, and **SELECTEDVALUE**
- Dynamic percentages based on **gross** or **net sales**
- Correct average calculations using **DISTINCTCOUNT**
- Fully interactive report controlled by **slicers**

## Notes on Data
For confidentiality reasons, the **PBIX** and client data are not shared publicly. Screenshots and documentation are provided instead.

## Screenshots
## Screenshots

### P&L Overview
![P&L Overview](overview.png)

### Financial Analysis
![P&L Analysis](global_view_statement.png)

### Dynamic Logic (Currency, Units, Averages)
![P&L Dynamic](arg - % and $.png)

### Dynamic Logic (Currency, Units, Averages)
![P&L Dynamic](usd_and_total_average.png)

