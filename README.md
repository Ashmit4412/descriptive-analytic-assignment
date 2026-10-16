## Simplified README – Nike Sales Performance Analysis Project

## 1. Project Overview
This project analyzes Nike sales data using descriptive analytics. It studies best-selling products, discounts, buying patterns, store-zone demand, and inventory risks.

The analysis helps identify high-demand products, possible margin risks, peak buying periods, and products that may run out of stock.

## 2. Objectives
- Identify the best-selling Nike products.
- Analyze discount trends and identify store zones at risk of reducing profit margins.
- Find the busiest buying times and days.
- Compare sales demand across store zones.
- Identify products at risk of running out of stock.
- Provide business recommendations for inventory, staffing, and replenishment.

## 3. Dataset
- Total records: 150 product-day records
- Products: 10
- Categories: 6
- Store zones: 5
- Analysis period: August 1–15, 2026
- Dataset type: Synthetic dataset

Each row represents one product's daily activity in its dominant store zone. The dataset includes units sold, revenue, average discount, customer rating, peak buying time, and remaining stock level.

The dataset is synthetic and was created to reflect realistic sportswear retail patterns. It is not live Nike sales data.

## 4. Tools Used
- Python: Main programming language
- Pandas: Data aggregation and analysis
- NumPy: Numerical analysis
- Matplotlib: Charts and graphs
- Seaborn: Data visualization
- ReportLab: PDF report creation

## 5. Key Findings

| Analysis | Result |
|---|---|
| Total units sold | 10,054 |
| Total revenue | ₹90,642,405 |
| Best-selling product | Nike Air Force 1 '07 – 2,699 units |
| Second best-selling product | Nike Dunk Low Retro – 1,804 units |
| Share of units sold by top product | 26.8% |
| Average discount | 11.6% |
| Product-days exceeding the 15% discount target | 16.7% |
| Peak buying time | Evening, 5 PM–9 PM |
| Units sold during peak buying time | 46.3% |
| Weekend sales compared with average weekday | 54.4% higher |
| Highest-demand store zone | Bandra West – Mumbai, 29.2% of demand |
| Highest margin-risk zone | Banjara Hills – Hyderabad |
| Products at Low Stock or below | 2 out of 10 |
| Out-of-stock product | Nike Tech Fleece Hoodie |

### Best-Selling Products
Nike Air Force 1 '07 was the best-selling product, with 2,699 units sold. It sold 49.6% more units than Nike Dunk Low Retro, which sold 1,804 units.

The top product contributed 26.8% of all units sold. This shows that a single popular product can contribute a large share of demand, so its stock and replenishment need close attention.

### Discount Analysis
The average discount was 11.6%, below the 15% margin-safe target used in the report. However, 16.7% of product-day records exceeded that target.

Banjara Hills – Hyderabad was the clearest margin-risk zone. Its average discount increased from 12.0% to 18.7% during the 15-day period. This trend should be investigated before discounts reduce profit margins further.

### Buying Pattern Analysis
Evening, from 5 PM to 9 PM, was the peak buying period and accounted for 46.3% of all units sold.

Weekend sales volume was 54.4% higher than the average weekday. These patterns can help stores plan staff schedules and prepare stock before busy periods.

### Store-Zone Demand Analysis
Bandra West – Mumbai had the highest demand, accounting for 29.2% of total units sold. The report calculated a Herfindahl-Hirschman Index (HHI) of approximately 2,244, indicating a moderately concentrated market across the five zones.

High-demand zones need suitable stock allocation, staffing, and backup fulfilment plans.

### Inventory Analysis
On the latest day, 8 products were In Stock, 1 was in Low Stock, and 1 was Out of Stock. Nike Tech Fleece Hoodie was out of stock.

Days of Supply estimates how long current stock may last at the average daily sales rate. It is more useful for replenishment planning than looking at stock quantity alone.

## 6. Business Insights
- Give Nike Air Force 1 '07 priority in stock checks and replenishment because it has the highest sales volume.
- Investigate the rising discount trend in Banjara Hills – Hyderabad.
- Schedule more staff during the evening peak and prepare for higher weekend demand.
- Allocate stock and fulfilment capacity according to demand in each store zone.
- Monitor days of supply and reorder points to reduce stockout risk.
- Review discounting and sales trends regularly to identify problems early.

## 7. Future Scope: Predictive Analytics
This project currently focuses on descriptive analytics. The report suggests extending it with predictive analytics in the future:

- **Sales Forecasting:** Predict sales volume by store zone to help plan staffing and stock.
- **Demand Forecasting:** Estimate product demand and help set reorder points.
- **Anomaly Detection:** Flag sudden discount increases or unexpected demand changes.

These are proposed future improvements; the report does not provide predictive model accuracy results.

## 8. Project Folder Structure
Nike-Sales-Analytics/
│
├── README.md
├── dataset/
│   └── nike_sales_data.csv
├── python/
│   ├── analysis.py
│   └── make_charts.py
├── report/
│   └── report.pdf
└── charts/
    └── graphs.png

*Note: Update the folder and script names if your actual project uses a different structure.*

## 9. Data Disclaimer
Live Nike sales data is not publicly accessible for this project. The analysis uses a synthetic dataset representing 10 products across 6 categories and 5 store zones over August 1–15, 2026. The results are illustrative and should not be treated as actual Nike business performance.

## 10. Conclusion
This project uses descriptive analytics to understand Nike product sales, discount trends, customer buying patterns, store-zone demand, and inventory risks. The findings can support better stock planning, staff scheduling, discount monitoring, and replenishment decisions. Sales forecasting, demand forecasting, and anomaly detection are possible future extensions.
