# Sales Performance & MIS Dashboard | Excel 365

**Excel portfolio project · Sales reporting · Management information systems**

A practical Excel 365 sales analytics project based on **100 sample orders**. It demonstrates data preparation, revenue and order-status KPI design, analysis, dashboard reporting, reconciliation, and business interpretation.

> **Portfolio disclosure:** This is an independent practice project, not employer work experience or live business data.

## Project overview

The dashboard addresses four management questions:
1. How much net sales value comes from delivered orders?
2. Which regions, months, products, and sales executives contribute most?
3. What are the delivery and cancellation rates?
4. Where should managers investigate performance and concentration risk?

## Headline results

| KPI | Result |
|---|---:|
| Recognized revenue (project-defined) | ₹20,35,292.50 |
| Total orders | 100 |
| Delivered orders | 72 |
| Delivery rate | 72% |
| Cancellation rate | 14% |
| Top region by recognized revenue | West |
| Top month | June |
| Top product | Laptop |

**Important reporting assumption:** In this workbook, *recognized revenue* is net sales from orders marked **Delivered** only. This is a simplified management reporting definition, not a universal financial accounting revenue-recognition rule.

## Download and use

**[Excel MIS Dashboard workbook](Sales_Performance_MIS_Dashboard.xlsx)**

Open in **Microsoft Excel 365 Desktop**, enable calculation/recalculation, and start at **`00 Dashboard`**. This workbook is formula-driven; it does not claim to have interactive slicer-controlled PivotCharts.

## Workbook structure

| Sheet | Function |
|---|---|
| `00 Dashboard` | Executive KPIs and visual reporting |
| `01 Raw Transactions` | Original sample transaction records |
| `02 Clean Data` | Prepared data and derived financial measures |
| `03 KPI Scorecard` | Central reporting metrics |
| `04 Regional Analysis` | Regional sales and order performance |
| `05 Monthly Trends` | Month-by-month performance |
| `06 Product Analysis` | Product contribution and concentration |
| `07 Executive Analysis` | Sales executive comparison |
| `08 Data Quality` | Data validation and reconciliation |
| `09 Business Insights` | Interpretation and management follow-ups |
| `10 Project Guide` | KPI definitions, methods, and assumptions |

## Metric definitions

- **Gross sales:** `Quantity × Unit Price`
- **Discount amount:** `Gross Sales × Discount %`
- **Net sales:** `Gross Sales − Discount Amount`
- **Recognized revenue (project KPI):** `Net Sales` for Delivered orders, otherwise zero
- **Delivery rate:** `Delivered Orders / All Orders`
- **Cancellation rate:** `Cancelled Orders / All Orders`

## Skills demonstrated

Excel tables and structured references, data cleaning, conditional logic and aggregations, KPI design, management reporting, trend analysis, operational performance analysis, charting, data quality checks, and documentation.

## Business insights and limitations

- West is the leading region by recognized revenue; investigate whether that reflects order volume, order value, or delivery conversion.
- June is the highest-revenue month; the sample is not sufficient to conclude long-term seasonality.
- Laptop leads product revenue; examine concentration risk and product mix.
- Executive comparisons should consider order mix, transaction values, and sample size, not revenue alone.
- Dataset consists of **100 practice transactions**. Findings are descriptive and should not be generalized to a real business.

## Interview explanation

> I built an Excel-based Sales Performance MIS dashboard using a 100-order practice dataset. I cleaned the source data, calculated gross and net sales, defined delivered-order revenue and operational KPIs, analyzed results by region, month, product, and executive, and documented the reporting assumptions and validation checks.

## Repository contents

- `Sales_Performance_MIS_Dashboard.xlsx` — finished Excel dashboard workbook
- `README.md` — project methodology, key results, and interview summary
- `.gitignore` — excludes temporary Excel lock files
