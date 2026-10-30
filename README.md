# Supply Chain Performance and Inventory Optimization Analysis

## Project Overview

This project focuses on analyzing supply chain operations, inventory management, and data quality using a dataset containing supply chain-related information.

The goal is to understand how data analysis can help identify inventory issues, evaluate operational performance, and support better business decisions.

**Project Status:** In Progress

## Objectives

- Audit the dataset to identify missing values, duplicates, inconsistent data types, and unusual values.
- Develop a data dictionary describing the dataset's tables, columns, and business meanings.
- Document data quality issues, their potential impact, and the proposed treatment for each issue.
- Analyze supply chain and inventory performance using SQL.
- Develop an interactive Power BI dashboard to communicate findings and recommendations.

## Tools and Technologies

- **Microsoft Excel:** Data auditing, profiling, and documentation.
- **SQL:** Data querying and analysis.
- **Power BI:** Data visualization and dashboard development.
- **GitHub:** Project documentation and version control.

## Planned Deliverables

1. Data audit workbook (`data_audit.xlsx`)
2. Data dictionary (`data_dictionary.xlsx`)
3. Data quality log (`data_quality_log.xlsx`)
4. SQL analysis scripts
5. Power BI dashboard and business recommendations

## Project Workflow

1. Understand the business context and dataset structure.
2. Audit the original data without modifying it.
3. Create the data dictionary and document data quality issues.
4. Determine appropriate treatments for identified issues.
5. Perform SQL-based analysis.
6. Build a Power BI dashboard and communicate actionable insights.

## Data Quality Approach

The original dataset will be preserved during the initial audit. Identified issues will be documented before any cleaning or transformation is performed. Decisions about treatment will be based on the meaning of the data and the business context.

## Expected Outcome

The project aims to demonstrate practical skills in data auditing, data documentation, SQL analysis, business intelligence, and communicating data-driven recommendations.

*Note: Findings and recommendations will be added as the analysis progresses.*

## Current Progress and Next Steps

The project is currently in the data-auditing and documentation stage. The source files are being examined to understand their structure, column meanings, data types, completeness, and relationships before data cleaning and analysis begin.

## Current Progress and Next Steps

### Completed
- Created the GitHub repository and established the project folder structure.
- Reviewed the source files and examined the data dictionary to understand the dataset structure and relationships.
- Completed preliminary data audits of the purchase-order workbook and the following CSV tables:
  - `suppliers.csv`
  - `warehouses.csv`
  - `products.csv`
  - `purchase_orders.csv`
  - `purchase_order_lines.csv`
- Checked record counts, column structures, missing values, duplicate identifiers, data types, value ranges, and relationships between tables.
- Identified data-quality and documentation issues, including inconsistent date representations, undocumented currency and measurement units, and fields requiring further clarification.
- Documented preliminary findings and proposed treatments in the data audit workbook.

### In Progress
- Auditing the remaining source tables:
  - `inventory_movements.csv`
  - `inventory_opening_balances.csv`
- Completing the data dictionary and data-quality log.
- Reviewing relationships and validating references across the dataset.

### Next Steps
1. Complete the preliminary audit of all source files.
2. Finalize the data dictionary and data-quality log.
3. Begin data cleaning and validation.
4. Load the cleaned data into MySQL for analysis.
5. Perform exploratory and supply-chain performance analysis using SQL.
6. Develop interactive dashboards in Power BI.
7. Document findings, insights, and recommendations.
