#☕ Global Coffee Sales & Profitability Analysis (2019 - 2022)
End-to-end analysis of global coffee retail performance (2019-2022). This project leverages a relational Star Schema to uncover insights into revenue drivers, loyalty program ROI, and geographic market penetration across the US, UK, and Ireland.

##📜 Overview
This repository details a comprehensive analysis of a global coffee retail operation's performance over a four-year period. By transforming fragmented raw data into a structured relational model, this project explores how product attributes, geographical locations, and customer loyalty programs influence total revenue and profit margins.

##🎯 Aim
The goal of this analysis is to provide a deep understanding of the business's "Value Drivers." By engineering a functional Star Schema, the project moves beyond basic visualization to provide strategic recommendations aimed at improving average order value (AOV), optimizing inventory for high-margin roasts, and identifying underperforming international markets.

##💡 Key Insights
The analysis highlighted several critical findings regarding market dominance, product preferences, and promotional effectiveness:

Market Concentration & Growth: The United States is the primary engine of the business, generating R35,638.89 (79% of total revenue). In contrast, the United Kingdom represents a significant growth opportunity, currently contributing only R2,798.51.

The Loyalty Paradox: A comparative analysis reveals that Non-Loyalty members actually have a higher average spend per order (R46.48) than Loyalty Card holders (R43.67), suggesting the current loyalty rewards may be cannibalizing margins rather than driving higher volume.

Product Performance: Arabica Medium Roast is the highest-volume product by quantity (358 units), while Excelsa Light Roast emerged as a premium revenue leader, generating R4,796.55 in total sales.

Profitability Metrics: The operation maintains a stable 10.02% profit margin on a total revenue of R45,134.25, with an average order value of R47.16.

##✅ Recommendations
The following strategic recommendations are provided to improve profitability and market share:

Restructure the Loyalty Program: 💳 Transition from flat discounts to a tiered "Points-per-Rand" system to incentivize higher transaction values from the loyalty segment.

Inventory Scaling for Light Roasts: 📈 Data shows that Light Roasts across all coffee types (Arabica, Excelsa, Liberica) are top revenue generators. Increase stock levels for these SKUs to prevent stockouts during peak periods.

Targeted UK Expansion: 🇬🇧 Launch a "US Top-Sellers" promotional bundle specifically for the UK market to increase brand penetration in this lower-performing region.

Dynamic Bundling: 🎁 Pair high-volume movers (Arabica Medium) with high-margin specialty items (Excelsa Light) to recover profit lost on discounted high-volume sales.

##🏗️ Data Architecture (ERD)
The project utilizes a Star Schema to maintain data integrity and optimize query performance:

Fact Table: Orders (Transactional data)

Dimension Tables: Customers and Products

Relationships: Established via Customer ID and Product ID using 1:N (One-to-Many) cardinality.

##🛠️ Tools & Technologies Used
Excel (Power Query): For ETL (Extract, Transform, Load) and data normalization.

Power BI: For DAX measure creation and interactive dashboarding.

Draw.io: For designing the Entity Relationship Diagram (ERD).

##🎥 How to View
📊 Dashboard Preview: > 🔗 View Dashboard File

🏗️ Entity Relationship Diagram: > 🔗 View ERD Diagram

🧹 Cleaned Data: > 🔗 View Cleaned Dataset


