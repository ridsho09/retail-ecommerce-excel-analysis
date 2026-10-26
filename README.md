# Retail & E-commerce Performance Analysis

## Project Overview

I used Microsoft Excel to clean and analyse a retail and e-commerce dataset containing 600 unique orders. I built PivotTables, charts, and an interactive dashboard to explore delivered order value, product performance, geographic contributions, delivery outcomes, and customer ratings.

## Dashboard Preview

![Retail and E-commerce Performance Dashboard](Retail_Ecommerce_Dashboard.png)

The image is a static preview. Download the Excel workbook to explore the dashboard’s slicers and timeline.

## Business Questions

- Which categories and products contribute the most delivered order value?
- Which states and channels lead recorded delivered performance?
- How does delivered order value vary across the recorded years?
- How are orders distributed across delivery statuses?
- What do available customer ratings indicate?

## Tools and Skills

- Microsoft Excel
- Data cleaning and validation
- Excel formulas
- PivotTables and PivotCharts
- Dashboard design
- Slicers and timeline controls
- Business reporting and recommendations

## Data Preparation

I preserved the original data and prepared a separate working sheet for analysis.

My preparation process included:

- Removing nine duplicate records, leaving 600 unique orders.
- Trimming spaces and standardising customer names and city labels.
- Consolidating supported product-category variants into eight categories.
- Reviewing quantity and date formatting.
- Checking numeric fields and customer-rating ranges.
- Preserving missing ratings as blanks.
- Flagging malformed emails and unusual prices without inventing replacements.
- Calculating order value as Quantity × UnitPrice_NGN.
- Documenting transformations and review items in a cleaning log.

## Main KPIs

These figures represent the full dataset before additional dashboard selections.

| KPI | Result |
| --- | ---: |
| Total orders — all statuses | 600 |
| Delivered orders | 125 |
| Delivered units | 448 |
| Delivered order value | ₦179,339,382.51 |
| Average delivered order value | ₦1,434,715.06 |
| Average delivered-order rating | 3.02 / 5 |
| Rated delivered orders | 86 |
| Delivered rating coverage | 68.80% |

### Metric Definitions

- **Order value:** Quantity × UnitPrice_NGN.
- **Delivered order value:** Sum of order value for orders marked Delivered.
- **Delivered average order value:** Delivered order value ÷ delivered orders.
- **Average delivered-order rating:** Average of populated ratings for delivered orders.
- **Rating coverage:** Rated delivered orders ÷ delivered orders.

Recorded order value does not reflect cash collected, recognised revenue, or profit.

## Key Findings

- **Phones & Tablets** contributed ₦63.98 million, representing 35.67% of recorded delivered order value.
- **Enugu** contributed ₦55.20 million, representing 30.78% of recorded delivered order value.
- **In-Store** led channel value at ₦86.84 million, representing 48.42%.
- **Screen Protector** led product value at ₦53.56 million. One unusually large order accounts for ₦50.09 million of that amount, making source validation essential.
- **Cancelled and Returned** orders together accounted for 34.00% of all orders.
- **Pending and In Transit** orders together accounted for 45.17% of all orders.
- Delivered-order ratings averaged **3.02 out of 5**, with 39 delivered orders unrated.

Delivery-status percentages describe the recorded snapshot. They do not establish delivery speed or outcomes for completed order cohorts.

## Recommendations

1. Validate flagged high-value transactions before using product and geographic rankings for investment decisions.
2. Confirm date provenance before interpreting annual comparisons as established growth.
3. Investigate cancellation and return reasons using additional operational information.
4. Track pending and in-transit orders alongside order age and status timestamps.
5. Improve customer-feedback collection and monitor rating coverage.
6. Assess category, state, and channel performance alongside order counts, units, and future cost information.

## Data Limitations

- The cleaning log retains 205 date-provenance exceptions and 15 price-outlier flags.
- Unusual prices were retained unless evidence supported a correction. They materially affect value totals and rankings.
- Missing ratings were excluded from averages and were not replaced with zero.
- Delivery dates, promised delivery times, costs, and payment-settlement details are unavailable.
- The payment-method and category-rating PivotTables cover all statuses; the primary value and rating KPIs use Delivered orders.

## Explore the Project

- [Download the Excel workbook](Retail-Ecommerce-Excel-Analysis.xlsx)
- [View the dashboard image](Retail_Ecommerce_Dashboard.png)
- The business report and dashboard PDF are available in the repository file list.

### Using the Workbook

1. Download and open the workbook in Microsoft Excel.
2. Open the Dashboard sheet.
3. Use the category, state, and channel slicers and the date timeline to explore the available views.
4. Clear filter selections to return to the full view.
5. Review Pivot Analysis for supporting summaries and the Cleaning Log for preparation details.

## Author

**Shodipo Ridwan Olamilekan**

Data Analyst | Business Intelligence Analyst | Excel, SQL & Power BI

[GitHub Profile](https://github.com/ridsho09)
