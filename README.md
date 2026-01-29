Sales Analysis Insights & Recommendations
1️⃣ Insight: Total Sales Over Time
Total sales from 2017 to 2020 = 9,955,862

Highest sales were in 2019, followed by a significant decline in 2020.

Some months, such as January, June, and July, have low sales.

Recommendation

Develop a seasonal sales plan to optimize inventory and avoid product shortages during peak months.

Study the reasons for the sales decline in 2020 and improve performance during weaker months through promotional campaigns.

Action Taken

We thoroughly cleaned the data to ensure the accuracy of sales figures for each year and month.

We included null or unknown values ​​as "Unknown" to prevent any erroneous figures in the analysis.

We created a Pivot Table sorted by Year and Month to ensure the accuracy of the data.

2️⃣ Insight: Top Suppliers
Top Sales Suppliers:

CROWN IMPORTS = 1,736,309

ANHEUSER BUSCH INC = 1,441,131

MILLER BREWING COMPANY = 1,512,585

Other suppliers have significantly lower sales.

Recommendation

Focus on large suppliers to establish long-term agreements and improve the supply chain.

Suppliers with lower sales → Evaluate their continued viability and improve cooperation terms.

Action Taken

Supplier names have been cleaned up, removing spaces and typos to ensure they display correctly in the Pivot Table.

A Pivot Table has been created for each supplier to accurately display total sales.

3️⃣ Insight: Sales by Item Type
Beer = 7,101,457 (Highest Sales)

Wine = 1,903,483

Liquor = 897,597

Dunnage = -121,307 (Negative Value)

Very small products (REF/STR_SUPPLIES) have a low contribution

Recommendation

Support winning products (Beer and Wine) through inventory and marketing.

Review negative products (e.g., Dunnage) to identify the causes of returns or losses.

Revise strategies for small products to improve profitability.

Action Taken

Power Query data has been cleaned up: any rows without a product type have been removed and empty values ​​have been marked "Unknown".

Ensure the Pivot Table calculates a Sum instead of a Count to guarantee accurate total sales for each product type.

4️⃣ Insight: Retail vs. Warehouse Sales
Some suppliers have significantly higher Warehouse sales than Retail sales (e.g., CROWN IMPORTS).

Some suppliers have a better balance between Retail and Warehouse sales.

Recommendation

Boost sales through Retail for products concentrated in Warehouse.

Use promotions and marketing to increase sales to the end consumer.

Improve inventory management to reduce unsold products in Warehouse.

Action Taken

A dual-value Pivot Table was created showing both Retail and Warehouse Sales for each supplier.

Values ​​were formatted to ensure accurate analysis and clear channel comparisons.

5️⃣ Data Cleaning & Preparation
Action Taken

Remove any rows without Item_Type or Supplier and add "Unknown" to empty values.

Trim and clean all columns to remove any invisible spaces or symbols.

Ensure all numeric values ​​(Total_Sales, Retail_Sales, Warehouse_Sales) are decimal numbers in Power Query. Pivot Tables are set up so that Sum calculates total sales, not Count.

Final number formatting: Remove brackets, use Thousand Separator, Decimal Places appropriate.

#####!!!!!!Result: All Pivot Tables are accurate, with no erroneous or blank numbers.

Charts are ready to display performance over time, by suppliers, by products, and by sales channels.
