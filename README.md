# Sales-Performance-Dashboard
<img width="1080" height="483" alt="image" src="https://github.com/user-attachments/assets/717895a4-a626-4b2c-bc0a-20e4587b757e" />

# Sales Performance Analysis (2023 VS 2024)

## Project Background
A consumer electronics retail client requires a direct comparative analysis to measure growth, volume trends, and operational efficiency between the 2023 and 2024 fiscal periods. The primary goal is to determine the effectiveness of sales strategies by quantifying the **Year-over-Year (YoY)** variance across all critical performance indicators.

This project delivers a focused **Excel dashboard** that highlights revenue drivers, cost-to-profit ratios, and product-level market performance between the two fiscal periods.

---

## Key Insights and Analysis
Insights and recommendations are provided across the following key areas:

* **YoY Growth and Profitability:** Quantifying the significant surge in **Total Sales ($475.6k, +30% vs LY)** and **Total Profit ($411.6k, +34% vs LY)**. The data reveals that profit is outscaling sales growth, indicating improved operational margins.
* **Volume vs. Cost Efficiency:** Tracking the relationship between **Quantity Sold (899 units, +24% vs LY)** and **Total Cost ($64.0k, +11% vs LY)**. The disproportionately low increase in cost suggests successful price optimization or reduced procurement expenses.
* **Monthly Volatility:** Detailed tracking of the **Monthly Revenue Trend** to pinpoint demand fluctuations. 2024 shows higher peak volatility, specifically during the massive surges in **April**, **September**, and **October**.
* **Product-Wise Breakdown:** Identifying the primary volume drivers. **Monitors** and **Mice** emerged as the highest contributors to the 2024 revenue growth, while **Keyboards** showed a slight decline in momentum compared to the prior year.

---

## Technical Deliverables

### Interactive Dashboard
The **Sales Performance Dashboard** provides a high-contrast, dark-themed interface designed for executive-level decision-making. It features interactive slicers for **Accessories** and **Electronics**, allowing stakeholders to filter performance by category dynamically.

### Time Intelligence Focus
The project leverages **Advanced Excel Functions** and **Pivot Table calculations** to derive complex Year-over-Year (YoY) variances. Key technical features include:
* **Dynamic Sparklines:** Integrated into KPI cards for immediate trend visualization.
* **Comparative Line Charts:** Overlaying 2023 and 2024 data to identify seasonal shifts.
* **Clustered Bar Charts:** Benchmarking specific product performance to highlight winners and laggards.
* **Zero-External BI Reliance:** All logic and visualizations were built natively in Excel to demonstrate robust data modeling within a spreadsheet environment.

---

## How to Use
1.  **Slicers:** Use the top-right buttons to toggle between **Accessories** and **Electronics**.
2.  **KPI Cards:** Monitor the green/blue indicators to see real-time growth percentages against Last Year (LY).
3.  **Trend Lines:** Hover over the line chart to see specific monthly revenue values for both fiscal years.

## Data Structure & Initial Checks

### Data Overview
The analysis was built entirely within a **single Excel workbook**, using a standard Excel Data Table as the source for all PivotTables and calculations. No data was loaded into the Power Pivot Data Model—all work was completed using native **Excel functionality** to demonstrate core spreadsheet competency and high-performance dashboarding within a flat-file environment.

### Data Cleaning and Preparation
The data cleaning and preparation process utilized native Excel tools, Pivot Tables, and Standard Excel Formulas to derive the core dashboard insights.

* **Data Quality:** The raw transactional data was audited for duplicates and missing values before being converted into a structured Excel Table. This ensured that the **$475.6k Total Sales** and **$411.6k Profit** figures were grounded in accurate, verified records.
* **Field Engineering:** Helper columns were created using text and date functions to standardize product categories and extract fiscal periods (Year/Month) for the trend analysis. This allowed for the seamless comparison of 2023 vs. 2024 across the **Monthly Revenue Trend** chart.
* **Aggregation:** Pivot Tables were used exclusively to aggregate quantity units and revenue figures across various dimensions, such as **Regional Sales Distribution** and **Product-wise Sales Breakdowns**.
* **Time Intelligence (Calculated Measures):** All core KPIs, including **+30% VS LY Sales**, **+24% VS LY Quantity**, and **+34% VS LY Profit**, were derived using Calculated Fields and formula-based helper tables within the Excel workbook. This approach allowed for dynamic period comparisons and the creation of the integrated sparklines without relying on the Power Pivot Data Model.

---

### Technical Highlights
* **Dynamic Visuals:** Leveraged Excel’s shape-based design and conditional formatting to create a high-contrast "Dark Mode" UI.
* **Native Slicers:** Implemented interactive slicers for **Accessories** and **Electronics** to provide a filtered view of the dataset without manual table adjustments.
* **Formula-Driven Logic:** Used `GETPIVOTDATA` and lookup functions to link the front-end KPI cards to the back-end Pivot summaries, ensuring the dashboard updates automatically as the source table grows.
<img width="1309" height="602" alt="image" src="https://github.com/user-attachments/assets/e6e8a468-4fa0-4230-bccd-687565406d5a" />

## Executive Summary (Sales Performance)

The business is delivering robust, high-margin expansion, with **Sales up 30%** and **Profit up 34%** versus the prior year (LY). **Total Sales reached $475.6k** while **Total Profit hit $411.6k**. This performance is exceptionally efficient; while **Quantity sold increased by 24% (899 units)**, the **Total Cost only rose by 11% ($64.0k)**. This indicates that the revenue surge is not just a result of higher volume, but also improved operational leverage and cost management, leading to a significantly healthier bottom line compared to 2023.

---

### YoY Growth and Financial Efficiency

* **Accelerated Revenue Growth:** Sales are **up 30% ($475.6k)** versus the prior year, signaling strong market demand for the current product mix.
* **Outsized Profitability:** Profit growth (**+34%**) is outstripping sales growth, confirming that the business is becoming more profitable as it scales.
* **Volume Expansion:** Quantity sold is **up 24% (899 units)**, showing a healthy increase in physical moving units alongside financial gains.
* **Cost Optimization:** The Total Cost (**$64.0k**) increased by only **11% VS LY**, suggesting successful vendor negotiations or reduced per-unit overhead.
<img width="407" height="217" alt="image" src="https://github.com/user-attachments/assets/c179415b-285b-4d42-bd61-cf635ba74944" />

---

### Regional Sales Distribution

* **Core Hardware Reliance:** **Monitors and Mouse** units are the standout primary drivers of sales volume. Their dominant position in the distribution chart confirms that these electronic devices are the most optimized sales categories with the strongest consumer pull.
* **Secondary Categories:** **Laptops and Printers** contribute moderate volumes. While stable, they represent a significant opportunity for growth if the marketing strategies used for high-performing peripherals are applied here.
* **Underperformers:** **Keyboards and Headphones** show lower relative volume. Specifically, Keyboards appear to be the only category struggling to significantly surpass 2023 levels, indicating a potential market saturation or a need for a product refresh.
<img width="406" height="171" alt="image" src="https://github.com/user-attachments/assets/43ffc370-de62-484a-bbe6-520f32505516" />

---

### Product-Wise Breakdown

* **Growth Drivers:** The **Monitor and Mouse** categories represent the highest revenue contributors, with Monitors alone nearing the **$110k** mark for 2024. These are the most effective product lines for driving the current year’s value surge.
* **Stable Performers:** **Laptops** maintain a consistent contribution, showing steady demand without the high volatility seen in smaller electronic devices.
* **Lagging Categories:** **Printers** show lower volume compared to the leaders, suggesting a need for revised bundling strategies (e.g., pairing printers with laptops) to lift this segment.
<img width="453" height="171" alt="image" src="https://github.com/user-attachments/assets/2cc8fef3-61bf-4dff-ad57-2d7eedf47f8a" />

---

### Business Recommendations

Based on the analysis of high YOY growth, strong profit margins, and specific product-level disparities, the following strategic actions are recommended:

1.  **Capitalize on High-Margin Peripherals:** Since **Monitors and Mouse** devices are driving the bulk of the $475.6k revenue, increase marketing spend and inventory depth for these specific high-velocity items.
2.  **Investigate Keyboard Stagnation:** Conduct a deep dive into the **Keyboard** category to understand why it hasn't shared in the 30% growth seen elsewhere. Determine if this is due to pricing, aging inventory, or competitor pressure.
3.  **Leverage Cost Efficiency:** With costs only rising **11%**, the business has the "breathing room" to offer aggressive promotional discounts on lower-volume items like **Headphones** without threatening overall profitability.
4.  **Optimize Stock for Seasonal Peaks:** Utilize the **Monthly Revenue Trend** to prepare for the massive spikes seen in **April, September, and October**. Ensure supply chain readiness at least 30 days prior to these historical surges.
5.  **Bundle Low-Volume Hardware:** Create "Home Office Bundles" pairing high-demand **Monitors** with slower-moving **Printers or Keyboards** to clear stock and increase the average order value (AOV).

---

**Thank you for reading! Leave a comment if you have any questions about the analysis.**

