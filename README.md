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

The project has progressed through the preliminary data-auditing and documentation stage. All eight source files have been inspected, their structures and relationships examined, and key data-quality checks performed.

### Completed

- Created the GitHub repository and established the project folder structure.
- Completed preliminary audits of all eight source files.
- Checked record counts, column structures, missing values, duplicate identifiers, data types, value ranges, and relationships between tables.
- Validated all 12,067 inventory transfer IDs, confirming that each transfer has two corresponding records with matching products, different warehouses, and a net quantity change of zero.
- Validated the `line_count` values for all 18,000 purchase orders against the actual records in `purchase_order_lines.csv`. All counts matched.
- Verified warehouse references across the purchase-order sources.
- Identified data-quality issues and fields requiring further clarification, including undocumented currencies and measurement units.
- Created and reviewed the following documentation workbooks:
  - `data_audit.xlsx`
  - `data_dictionary.xlsx`
  - `data_quality_log.xlsx`

### In Progress

- Preparing the completed documentation workbooks for publication in the GitHub repository.
- Planning the data-cleaning and validation phase.

### Next Steps

1. Publish the documentation workbooks in the GitHub repository.
2. Begin data cleaning and validation while preserving the original source data.
3. Load the cleaned data into MySQL for analysis.
4. Perform exploratory data analysis and supply-chain performance analysis using SQL.
5. Develop interactive dashboards in Power BI.
6. Document findings, insights, and recommendations.
