# Superstore Sales Dashboard

An interactive Power BI dashboard for exploring Superstore sales, orders, profit, and product performance.

## Dashboard preview

![Superstore Sales Dashboard preview](dashboard-preview.png)

## At a glance

The dashboard brings its headline KPIs and sales breakdowns together on one page. The supplied preview shows:

| KPI | Value shown |
| --- | ---: |
| Total sales | 249.12K |
| Total orders | 557 |
| Total profit | 42.03K |
| Profit margin | 0.17 |
| Total quantity | 4K |

Interactive slicers are available for time, region, and product category. Visuals include an annual sales trend and comparisons by category, region, and sub-category.

## Highlights from the preview

- Technology is the largest category in the displayed category chart.
- The West is the leading region in the displayed regional chart.
- Phones and Chairs are the largest sub-categories shown.
- Annual sales rise from 2014 to a peak in 2016, then decline in 2017.

### Data validation note

The KPI cards and charts in the supplied preview do not reconcile: the sales KPI is **249.12K**, while the category and regional chart labels appear to total about **0.89M**. This report records what is visible in the dashboard; it does not resolve the difference. Check the Power BI measures, filter context, and aggregation settings before using the chart totals for business decisions.

## Project files

| File | Description |
| --- | --- |
| [`Superstore_Sales_Dashboard.pbix`](Superstore_Sales_Dashboard.pbix) | Power BI Desktop report |
| [`dashboard-preview.png`](dashboard-preview.png) | Dashboard screenshot |
| [`Superstore_Sales_Report.pdf`](Superstore_Sales_Report.pdf) | Clean, three-page summary with clickable GitHub, video, and LinkedIn links |

## Open the dashboard

1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Download or clone this repository.
3. Open `Superstore_Sales_Dashboard.pbix` in Power BI Desktop.
4. Use the slicers to explore the report by date, region, and category.

## Tools

- Microsoft Power BI Desktop
- Power Query
- DAX
- Sample Superstore data

---

Created by [RAIN CLOUD](https://github.com/gamepatt78).
