# ApnoMart Sales & Profitability Dashboard

## Project overview
This Business Intelligence project analyzes 1,200 ApnoMart sales records using Power BI. The dashboard is designed to help business leaders review revenue, profit, category performance, regional performance, monthly trends, customer segments, and payment methods.

**Tool:** Power BI Desktop  
**Dataset:** `apnomart-sales-data.csv`  
**Analysis period:** 1 May 2026 – 28 October 2026  
**Prepared by:** Pavan  
**Program:** ApnoAI Data Analytics Intern · October 2026

> **Period note:** The assignment specifies the title “ApnoMart Q2 2026 Executive Dashboard,” but the supplied dataset covers May through October 2026. The report should clearly display this actual date range and should not present the full period as Q2-only performance.

## Key performance indicators
| KPI | Result |
|---|---:|
| Total Sales | ₹1,62,61,998.30 |
| Total Profit | ₹44,19,736.17 |
| Unique Orders | 1,200 |
| Overall Profit Margin | 27.18% |

Profit margin is calculated as total profit divided by total sales.

## Dashboard visuals
- KPI cards: Total Sales, Total Profit, Total Orders, and Profit Margin
- Sales by Category (bar chart)
- Sales Trend over Time (monthly line chart)
- Profit by Region (bar chart)
- Region and/or Category slicers
- Advanced options: Discount vs Profit scatter chart and Sales by Payment Method donut chart

## Three strategic insights
1. **Revenue pattern:** Furniture is the largest category by sales at ₹35.18 lakh (about 21.63% of total sales). July is the strongest month at ₹29.58 lakh. Review the drivers of July demand and use validated demand patterns to guide inventory planning.
2. **Profitability pattern:** Office Supplies has the highest category profit margin at about 34.80%, while Electronics has the lowest at about 18.88%. Investigate Electronics' discounting, product mix, and costs before changing pricing or promotions.
3. **Customer and payment behavior:** Corporate customers contribute ₹43.11 lakh (about 26.51% of sales), the largest customer-segment share. Cash is the largest payment method by sales at ₹35.74 lakh (about 21.98%). Review segment-level retention opportunities and payment preferences before investing in targeted campaigns.

## Strategic recommendation
Prioritize profitable growth: protect the strong margin in Office Supplies, investigate the causes of Electronics' lower margin, and use monthly and segment-level performance to plan inventory and marketing budgets. Test any discount changes on a limited scale and measure both sales and profit before expanding them.

## Files in this repository
- `dashboard.png` — screenshot of the completed Power BI dashboard
- `insights.pdf` — executive insights and recommendation
- `ApnoMart_Executive_Dashboard.pbix` — editable Power BI report (optional but recommended)
- `README.md` — project overview and findings

## Data-quality notes
The supplied CSV contains 1,200 rows and 15 columns. The initial check found no missing values and 1,200 unique Order_ID values. These findings describe the supplied file; they do not independently verify the business's source systems.
