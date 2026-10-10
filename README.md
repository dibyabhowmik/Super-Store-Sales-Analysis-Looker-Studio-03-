**Project Overview**

The Superstore Sales & Profit Analytics Dashboard is a two-page Looker Studio project designed to analyze retail sales performance, profitability, order activity, customer segments, regions, categories, and discount behavior.

The first page provides a high-level sales and profitability overview, while the second page focuses on advanced profitability metrics using calculated fields such as Profit Margin, Sales per Order, Profit per Order, and Discount Band.

The dashboard contains 5,111 orders, 38,654 units sold, total sales of 2,326,534.35, and total profit of 292,296.81.

**Objectives:**


- Monitor overall sales, profit, order volume, and quantity sold.
- Analyze sales performance across product categories.
- Compare profitability across categories.
- Understand regional sales distribution.
- Compare sales and profit across customer segments.
- Measure profit margin across categories.
- Analyze the relationship between discounts and profitability.
- Calculate sales and profit per order.
- Build interactive filters for deeper sales analysis.

**Tools Used:**

- Looker Studio
- Google Sheets
- Superstore Sales Dataset
- Calculated Fields
- Interactive Filters
- Data Visualization

**Process:**


1. Imported the Superstore dataset into Google Sheets.
2. Connected the dataset to Looker Studio.
3. Built KPI cards for Total Sales, Total Profit, Total Orders, and Total Quantity.
4. Created sales analysis by category and region.
5. Created profit analysis by category.
6. Compared Sales and Profit across customer segments.
7. Created a yearly sales trend visualization.
8. Developed advanced calculated fields:
   - Profit Margin
   - Sales per Order
   - Profit per Order
   - Discount Band
9. Built a category performance summary table combining sales, profit, profit margin, and order-level metrics.
10. Added interactive filters for Region, Category, Segment, Ship Mode, and Discount Band.
11. Added navigation between the Overview and Advanced Analysis pages.

**Key Insights:**


- The dashboard reports total sales of **2,326,534.35**, total profit of **292,296.81**, **5,111 unique orders**, and **38,654 units sold**. :contentReference[oaicite:10]{index=10}
- **Technology** is the largest sales category, followed by Furniture and Office Supplies. :contentReference[oaicite:11]{index=11}
- Technology also generates the highest total profit, followed by Office Supplies, while Furniture produces substantially lower profit. :contentReference[oaicite:12]{index=12}
- The **West region** has the highest sales, followed by East, Central, and South. :contentReference[oaicite:13]{index=13}
- The Consumer segment contributes the highest sales and profit among the three customer segments, followed by Corporate and Home Office. :contentReference[oaicite:14]{index=14}
- The overall profit margin is approximately **12.56%**. :contentReference[oaicite:15]{index=15}
- Technology has the strongest category-level profit margin at approximately **17.45%**, followed closely by Office Supplies at **17.22%**. Furniture has a much lower profit margin of approximately **2.61%**. :contentReference[oaicite:16]{index=16}
- Technology also has the highest sales per order and profit per order among the three categories shown in the performance table. :contentReference[oaicite:17]{index=17}
- The discount analysis shows a sharp deterioration in profit margin at higher discount levels. The highest discount band shown in the dashboard has a strongly negative profit margin, indicating that heavy discounting is associated with substantially weaker profitability in this dataset. :contentReference[oaicite:18]{index=18}
- Home Office has the highest Sales per Order among the three segments, followed by Corporate and Consumer. :contentReference[oaicite:19]{index=19}
- The yearly sales trend shows fluctuations over the displayed period, with stronger sales around 2022 and 2025 and lower sales in the final displayed year. :contentReference[oaicite:20]{index=20}

**Dashboard Pages**


**Page 1 — Sales Overview Dashboard**

Provides an overview of sales, profit, orders, quantity, yearly sales trend, category performance, regional sales, and customer-segment performance.

**Page 2 — Advanced Sales & Profit Analysis**

Focuses on profit margin, sales per order, profit per order, discount impact, and category-level performance using calculated fields and interactive filters.
