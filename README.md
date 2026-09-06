# POWER_BI_DASHBOARD
1. Project Title / Headline

🛒 Mahadav Ecommerce Sales Dashboard  
An interactive Power BI analytics report designed to evaluate e-commerce operations, tracking profitability, transaction volumes, payment preferences, and regional performance.
3. Short Description / Purpose
The Mahadav Ecommerce Sales Dashboard transforms transactional e-commerce sales data into actionable business insights. It enables store managers, financial analysts, and marketing strategists to track revenue, profit margins, customer order sizes, and seasonal category performance across major Indian states and quarterly business cycles.
4. Tech Stack📊 Power BI Desktop:
   Developed responsive dashboard layouts, custom dark neon themes, and cross-filtering visual components.
   📂 Power Query: Performed data transformations, null value handling, column data typing, and table structures across order datasets.
   🧠 DAX (Data Analysis Expressions): Formulated key measures for calculated aggregations including Sum of Profit, Sum of Amount, Sum of AOV, and Sum of Quantity.
   📝 Data Modeling: Established logical schema relationships connecting transaction logs (Details.csv and Orders.csv) with location and category attributes.
   📁 File Formats: Developed using Power BI project files (.pbit/.pbix), backed by CSV datasets, and exported in .png format for repository documentation.
 5. Data Source
Sources:Transactional E-Commerce Order Records (Details.csv and Orders.csv).
Dataset Structure: Contains line-item transaction records encompassing customer names, purchase amounts, profit margins, payment methods (COD, UPI, Credit Card, Debit Card, EMI), product categories/sub-categories, and state-level geographic location tracking.
 6. Features / Highlights
Business Problem
E-commerce businesses frequently struggle to identify which product lines drive net profitability versus those that generate top-line revenue without margin. Understanding customer payment channel choices and regional demand patterns is critical for managing inventory, reducing return rates (RTO), and optimizing cash flow.
Goal of the Dashboard
To provide an intuitive visual interface that enables decision-makers to evaluate profit drivers, track seasonal sales fluctuations, pinpoint top-performing geographies, and analyze product category demand patterns.
Walkthrough of Key Visuals
KPI Summary Cards (Top Left): Displays core store performance metrics—Sum of Profit (13K), Sum of Amount (144K), Sum of AOV (41K), and total unit volume sold (Sum of Quantity: 3,516).
Interactive Slicers (Top Right): Button slicers for quarterly filtering (Qtr 1 to Qtr 4) paired with a dropdown slicer for state-level cross-filtering.
Profit by Month (Bar Chart): Tracks monthly profitability trends, illustrating strong profit peaks in Q1 (January–March) and Q4 (November), alongside mid-year dips.
Sum of Profit by State (Horizontal Bar Chart): Compares profitability across regions, highlighting top performers like Madhya Pradesh and Maharashtra.
Quantity by Payment Mode (Donut Chart): Maps payment distribution—led by Cash on Delivery (COD at 28%) and UPI (14%), followed by Debit Card (8%), Credit Card (7%), and EMI (6%).
Sum of Amount by Customer Name (Bar Chart): Isolates top individual revenue generators such as Harivansh, Madhav, Madan Mohan, and Shiva.
Count of Quantity by Category (Donut Chart): Shows unit sales volume breakdown across core catalog categories: Clothing (63%), Electronics (21%), and Furniture (16%).
Sum of Profit by Sub-Category (Bar Chart): Ranks sub-categories by net return, identifying Printers, Bookcases, and Sarees as key margin drivers.
Business Impact & Insights
Catalog Optimization: Focus marketing investments on high-margin sub-categories like Printers and Bookcases while driving volume through Clothing.
Geographic Targeting: Tailor regional ad spend and logistics operations toward top revenue states like Madhya Pradesh and Maharashtra.
Payment Strategy: Transition customers from high Cash-on-Delivery (28%) reliance toward digital payment methods (UPI/Cards) to decrease order return rates and speed up settlement cycles.  Inventory & Promotions: Adjust promotional strategy during Q2/Q3 to offset seasonal margin compression.
9. Screenshots


    
