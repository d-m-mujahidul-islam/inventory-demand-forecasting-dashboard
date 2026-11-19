# Inventory & Demand Forecasting Executive Dashboard

An Excel-based supply chain analytics model featuring ABC-XYZ inventory classification, Single Exponential Smoothing (SES, $\alpha = 0.3$) demand forecasting, and an interactive dark-themed executive dashboard.

## Dashboard Preview
![Executive Dashboard Preview](dashboard-preview.png)

## Key Features
- **ABC-XYZ Inventory Segmentation:** Classifies SKUs by value/revenue contribution and demand variability to guide inventory policy decisions.
- **Demand Forecasting (SES, $\alpha = 0.3$):** Compares actual demand against smoothed forecasts and tracks model accuracy (MAPE).
- **Interactive Controls:** Product selection dropdown, slicers, and dynamic linked KPI/SKU profile cards.
- **Excel Techniques Used:** Power Query, Pivot Tables, `INDEX`/`MATCH` (or `XLOOKUP`), dynamic formulas, linked shapes, and custom dark UI formatting.

## How to Use
1. Download `Inventory_Demand_Forecasting_Model_v1.0.xlsx`.
2. Open in Microsoft Excel and enable editing/content if prompted.
3. Select a product or adjust filters/slicers on the dashboard to explore SKU-level forecasts, segmentation, and portfolio KPIs.
