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

The project has progressed through the initial data auditing and documentation stages. The source files have been examined to understand their structure, column meanings, data types, completeness, and relationships before data cleaning and analysis begin.

### Completed

- Created the GitHub repository and established the project folder structure.
- Reviewed the source files and examined the original data dictionary to understand the dataset structure and relationships.
- Completed preliminary data audits of all eight source files:
  - `inventory-supply-chain-v1.0.0-analysis.xlsx`
  - `suppliers.csv`
  - `warehouses.csv`
  - `products.csv`
  - `purchase_orders.csv`
  - `purchase_order_lines.csv`
  - `inventory_movements.csv`
  - `inventory_opening_balances.csv`
- Checked record counts, column structures, missing values, duplicate identifiers, data types, value ranges, and relationships between tables.
- Validated all 12,067 inventory transfer IDs, with all records passing the transfer validation checks.
- Identified data-quality and documentation issues, including inconsistent date representations, numeric values stored as text, undocumented currency and measurement units, and fields requiring further clarification.
- Created `data_audit.xlsx` to document audit checks, findings, potential impacts, and proposed treatments.
- Created `data_dictionary.xlsx`, documenting all 54 columns, 11 table relationships, and 15 business terms.
- Created `data_quality_log.xlsx`, documenting 19 identified data-quality issues, their potential impacts, proposed treatments, and current statuses.

### In Progress

- Completing two outstanding cross-file audit validations:
  - Verifying `warehouse_id` references in the purchase-order workbook against `warehouses.csv`.
  - Validating the workbook's `line_count` values against the actual purchase-order line records in `purchase_order_lines.csv`.
- Reviewing the three documentation workbooks for consistency before publishing them to GitHub.

### Next Steps

1. Complete the outstanding audit validations and finalize the documentation workbooks.
2. Upload the completed documentation to the GitHub repository.
3. Begin data cleaning and validation.
4. Load the cleaned data into MySQL for analysis.
5. Perform exploratory and supply-chain performance analysis using SQL.
6. Develop interactive dashboards in Power BI.
7. Document findings, insights, and recommendations.
