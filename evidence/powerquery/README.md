# Power Query (M) – Fact_Expenses Preparation

This section documents the transformation process applied to the **Fact_Expenses** table before loading into the Power BI data model.

The objective was to consolidate multiple financial annexes, standardize structures, integrate exchange rates, and prepare a clean dataset for dynamic P&L reporting.

---

## Data Integration

- Append queries
- Merge queries (account plan expansion)
- Structured consolidation of heterogeneous sources

---

## Data Cleaning & Standardization

The following transformations were applied:

- Data type standardization (Tipo cambiado)
- Column renaming for consistency
- Removal of unnecessary fields
- Creation of calculated columns
- Text normalization

---

## Financial Structuring

To enable accurate reporting and prevent duplication:

- Expansion of Chart of Accounts =
- Expansion of USD Exchange Rate table
- Controlled merge operations
- Duplicate prevention logic
- Structured grouping for BI-ready model


---

## Technical Highlights

- Consolidation of multiple financial sources into a unified fact table
- Controlled merging to prevent expense duplication
- Dynamic year and month column generation
- Preparation of dataset for star-schema modelling

---

## Key Applied Steps (Power Query)

Spanish Version

![Applied Steps](dynamic-PL-statement-sql-powerbi/blob/main/evidence/powerquery/6.fact-expenses.png)

