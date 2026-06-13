# Power BI Portfolio

<img width="1841" height="780" alt="image" src="https://github.com/user-attachments/assets/7f4436d8-36f5-4de3-8c13-d4e975ff488f" />

------------------
-----------------

<img width="1260" height="688" alt="image" src="https://github.com/user-attachments/assets/16aafb6d-8616-485c-adeb-156c1b342ee1" />
------------------
-----------------

<img width="1210" height="703" alt="image" src="https://github.com/user-attachments/assets/800f9032-f26c-4647-8e84-94ac2b8a6b3f" />

------------------
-----------------

<img width="1203" height="713" alt="image" src="https://github.com/user-attachments/assets/5526bb0c-b311-4e42-b2b4-ec1134de8c65" />

------------------
-----------------

<img width="1288" height="636" alt="image" src="https://github.com/user-attachments/assets/f1947276-17eb-477c-bf99-a944b6cac960" />

------------------
-----------------





A collection of end-to-end Power BI projects demonstrating data modeling, DAX development, and business intelligence reporting across retail and e-commerce contexts.

## Projects

| Project | Domain | Pages | Key Features |
|---|---|---|---|
| [AdventureWorks](./AdventureWorks/) | Retail / Bike Shop | 7 | Executive dashboard, map, product & customer detail, AI visuals |
| [Maven Market](./MavenMarket/) | Grocery Retail | 3 | KPI tracking, geo analysis, weekly trending, brand performance |

## Skills Demonstrated

- Data modeling (star schema, relationships, calculated tables)
- DAX measures (KPIs, rolling calendars, MoM comparisons, targets)
- Interactive dashboards with slicers, drill-throughs, and tooltips
- Geographic visualizations (Bing Maps)
- AI-powered visuals (Q&A, Decomposition Tree, Key Influencers)
- Multi-page report design with consistent UX

## Tools

Power BI Desktop · DAX · Power Query · Bing Maps

---

*Projects built as part of a data analytics training program.*




--------

# AdventureWorks Sales Report — Power BI

## Overview

End-to-end Power BI report for AdventureWorks Bike Shop, a fictitious retail company selling bikes, accessories, and clothing. The report covers sales performance from January 2020 to early 2022, with a focus on executive-level insights, product analysis, and customer segmentation.

## Dashboard Pages

| Page | Description |
|---|---|
| **Exec Dashboard** | Top-level KPIs, revenue trending, orders by category, top 10 products |
| **Map** | Geographic distribution of sales by territory |
| **Product Detail** | Drill-down into individual product performance |
| **Customer Detail** | Customer-level analysis and segmentation |
| **Category Tooltip** | Custom tooltip for category-level context |
| **Q&A** | Natural language query interface |
| **Decomposition Tree** | AI visual for root cause analysis |
| **Key Influencers** | AI visual identifying drivers of key metrics |

## Key Metrics

- **Revenue**: $24.9M
- **Profit**: $10.5M
- **Orders**: 25.2K
- **Return Rate**: 2.2%
- **Monthly Revenue**: $1.83M (+3.31% vs. prev. month)
- **Monthly Orders**: 2,146 (-0.88% vs. prev. month)
- **Monthly Returns**: 166 (+1.78% vs. prev. month)

## Key Features

- **Executive KPI cards** with month-over-month variance indicators
- **Revenue Trending** line chart with rolling average and date range slicer (Jan 2020 – Jan 2022)
- **Orders by Category** bar chart (Accessories: 17K, Bikes: 13.9K, Clothing: 7K)
- **Top 10 Products** table with Orders, Revenue, and Return % with conditional formatting
- **Most Ordered / Most Returned** product type highlights (Tires & Tubes / Shorts)
- **AI Visuals**: Q&A, Decomposition Tree, Key Influencers

## Data Model

Star schema with the following tables:

- `Sales Data` — fact table with transaction-level records
- `Returns Data` — return transactions
- `Calendar Lookup` — date dimension with rolling calendar support
- `Customer Lookup` — customer dimension
- `Product Lookup` — product dimension
- `Product Categories Lookup` / `Product Subcategories Lookup` — category hierarchy
- `Territory Lookup` — geographic dimension
- `Measure Table` — centralized DAX measures
- `Price Adjustment (%)` — what-if parameter

## DAX Highlights

- Month-over-month revenue, orders, and returns comparisons
- Rolling 90-day revenue calculations
- Return rate as % of orders
- Dynamic what-if price adjustment parameter

## Tools & Technologies

Power BI Desktop · DAX · Power Query · Bing Maps · AI Visuals (Q&A, Decomposition Tree, Key Influencers)
