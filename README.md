# Inventory-Performance-Analysis-Report
##  Summary
This report presents an analysis of current inventory performance across a 350 Product ID portfolio spanning five product categories. The dataset was analyzed using Excel-based inventory tracking methods to evaluate stock health, supplier reliability, and capital efficiency.
The analysis identifies three priority issues. First, 30.3% of products are currently at or below their reorder threshold, with 36 items fully out of stock, a level of exposure that warrants immediate replenishment action. Second, capital efficiency is uneven. Third, several suppliers carry lead times exceeding 30days, introducing replenishment risk for categories with high stockout exposure, particularly Kitchen items.
Recommended actions include prioritizing reorders for high-velocity products nearing depletion, renegotiating or diversifying away from high-lead time suppliers feeding stockout prone categories, and reviewing pricing or promotional strategy for slow-moving Office Supplies stock to free up capital. 

# Introduction
Effective inventory management directly affects a retail company’s profitability, customer satisfaction, and operational efficiency. Excess stock ties up working capital and increases holding costs, while insufficient stock results in lost sales and damaged customer trust. For a multi-category retailer operating across Electronics, Office Supplies, Household Goods, Kitchen Items, and Personal Care, the challenge is compounded by differing demand patterns, price points, and supplier reliability across categories.
This report analyzes a 350-product inventory dataset to assess current stock health, identify replenishment risk, evaluate supplier performance, and surface opportunities to improve capital efficiency. The objective is to translate raw inventory data into actionable business recommendations that support more proactive, data-driven stock management.

# Methodology
The analysis was conducted on a dataset of 350 Product ID, each recorded with unit cost, selling price, current stock level, reorder threshold, maximum stock capacity, supplier lead time, monthly demand, and inventory status, across 32 suppliers spanning 17 countries.
Data was processed in Microsoft Excel using a combination of conditional logic (IF, nested IF), aggregation functions (SUMIF, COUNTIF, AVERAGEIF), and a custom-built tracking dashboard. Five derived metrics were calculated to extend the raw data:

•	Reorder Flag: identifies products at or below their reorder threshold.

•	Stock Cover (days): current stock divided by average daily demand, indicating how long existing stock will last.

•	Slow-Mover Flag: Products with more than 90 days of stock cover, indicating low sales velocity relative to stock held.

•	Supplier Lead Time Risk: classifies suppliers as Low, Medium, or High risk based on average delivery lead time.

•	Stock Value: unit cost multiplied by current stock, used to assess capital tied up by category.
These metrics were aggregated into category-level and supplier level summaries to support the findings below.

# Key Findings
1.	Overall Stock health: of 350 products, 244 (69.7%) are adequately stocked, 70 (20.0%) are at low stock, and 36 (10.3%) are fully out of stock. Closely matching expected healthy-inventory benchmarks, though the out-of-stock segment still represents a meaningful revenue risk.
 
2.	Capital Distribution by Category: Total inventory value across the products is $5,594,442. Electronics holds the largest share at $2,488,549 (44,5% of total value), driven by higher unit costs rather than higher stock counts. Kitchen Items ($1,148,535) and Household Goods ($959,612) follow, with Office Supplies and Personal Care holding comparatively modest value ($558,450 and $439,296 respectively) due to lower per-unit cost.
 
3.	Stockout concentration: Out of stock incidents are not evenly distributed. Kitchen Items accounts for 13 of the 36 stockouts (36%), despite holding only 71 of 350 product IDs, a disproportionate share suggesting either underestimated demand or insufficient reorder buffers in this category. New York Household Goods is the single largest contributor to stockouts among suppliers, linked to 3 affected products.

4.	Slow-moving inventory: 65 product IDs (18.6%) qualify as slow-moving, with more than 90 days of stock cover at current demand. Office Supplies is disproportionately affected, accounting for 19nof the 65 slow-moving items (29%) despite representing only 20% of total Product IDs, indicating overstocking or declining demand in this category that is tying up capital without generating proportional sales.

5.	Supplier lead time risk: The majority of suppliers operate within acceptable lead time ranges (under 14 days), but a subset falls into the high-risk category. Categories sourced from these suppliers carry elevated stockout exposure, since slow replenishment compounds the impact of demand spikes.

# Conclusion
The inventory portfolio is broadly healthy, with roughly 70% of products adequately stocked, but two structural issues merit attention: stockout risk is concentrated in Kitchen Items, and capital inefficiency is concentrated in Office Supplies. Addressing supplier lead times for high-risk categories ad rebalancing stock levels for slow-moving products would meaningfully improve both service levels and working capital efficiency without requiring an increase in total inventory investment.
