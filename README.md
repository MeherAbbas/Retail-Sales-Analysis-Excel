# Retail Sales Analysis and Dashboard Using Excel

## Project Overview

This project analyzes 2022 retail order data for a clothing store using Microsoft Excel. The workbook contains an annual report dashboard and supporting summaries covering sales, order volume, customer demographics, order status, sales channels, and state-level sales.

> **Attribution:** This workbook was developed while following a YouTube tutorial. The tutorial is included as a learning reference below. The workbook should be treated as tutorial-based work; any independent changes or additional analysis should be described separately after they are completed.

## Tools Used

- Microsoft Excel
- PivotTables / summarized tables
- Excel charts and dashboard layout

## Workbook Contents

The workbook contains these sheets:

- **VRINDA STORE ANNUAL REPORT** — annual dashboard/report view.
- **SALES VS ORDERS** — monthly sales amount and order-count summary.
- **MEN VS WOMEN** — sales amount summarized by gender.
- **order status** — order counts by status.
- **top 10 states sales** — state-level sales summary.
- **age n gender** — customer age-group and gender summary.
- **top channels** — summary by sales channel.
- **Store** — source data sheet.

## Dataset Overview

The `Store` sheet contains approximately 31,047 data records and 21 columns, including:

- Order ID and customer ID
- Gender, age, and age group
- Order date and month
- Order status and sales channel
- SKU, product category, size, and quantity
- Currency and order amount
- Shipping city, state, postal code, and country
- B2B indicator

The data represents clothing retail orders and includes sales amount and quantity information. It does **not** contain a clearly identified cost-of-goods-sold field, so gross profit and gross profit margin should not be reported unless reliable cost data is added from a documented source.

## Analysis Included

The workbook's summaries cover:

- Monthly sales amount and order count
- Sales by gender
- Order counts by status
- Sales by state
- Age-group and gender breakdown
- Sales-channel summary

## Data Quality Notes

The workbook should be reviewed before using its results for business decisions or presenting it as an independently developed portfolio project.

- Repeated Order IDs may represent multiple line items belonging to one order. Do not remove them automatically; choose the correct counting method for the analysis.
- Category labels have inconsistent capitalization in the source data (for example, `kurta` and `Set`). Standardization may be useful for a revised version.
- Verify PivotTable totals against the source data and document any cleaning or changes made.
- Preserve an unchanged copy of the original workbook before editing it.

## Learning Reference

YouTube tutorial used as a learning reference:

https://youtu.be/gTK5rNhWJyA?si=Yvo08hhLRoc8uf9P

## How to Use

1. Download `Vrinda_Store_Annual_Report.xlsx` from this repository.
2. Open it in Microsoft Excel.
3. Review the `Store` sheet to understand the source records.
4. Open the summary sheets and dashboard to review the reported analysis.

## Possible Improvements

- Document data-cleaning steps and decisions.
- Standardize inconsistent text labels where appropriate.
- Add a clear distinction between order count, line-item count, and quantity sold.
- Validate dashboard totals and clearly state how each metric is calculated.
- Add original analysis and insights, and document those additions separately from the tutorial-based work.

## Project Status

**Tutorial-based learning project.** The workbook is shared as a learning exercise. Additional independent analysis and modifications should be documented as they are completed.
