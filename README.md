# Retail-Sales-Dashboard

## 1. Project Title / Headline
RetailPulse: National Retail Sales & Profitability Optimization Dashboard
A dynamic, interactive corporate intelligence tool built to track end-to-end multi-category retail performance—focusing on monthly sales velocities, profit margin trends, geographic revenue distribution across districts, and product sub-category velocity profiling.

## 2. Short Description / Purpose
The RetailPulse Dashboard is a visually engaging and deeply analytical Power BI reporting workspace designed to help commercial directors, product catalog managers, and financial analysts monitor retail business health. By consolidating raw transactional registers into structured metrics, this dashboard breaks down revenue share by core categories like Technology, Office Supplies, and Furniture, exposes monthly financial performance tracking, and profiles product sub-category demands. This tool is intended for use by retail operations leads and marketing strategists who want to eliminate underperforming inventory segments and transition into data-driven market expansion.

## 3. Tech Stack
The dashboard architecture is engineered using the following core business intelligence tools and technologies:

=> Power BI Desktop – The main authoring environment used for canvas design, corporate standard UI/UX visualization mapping, and active layout configuration.

=> Power Query – The data transformation and structural cleaning layer used to parse transaction records, link regional district attributes, and standardize product classification buckets.

=> DAX (Data Analysis Expressions) – Used for constructing baseline expressions (such as Total Sales, Cumulative Profits, Quantity Counters, and dynamic profit margin ratios across fiscal months).

=> Data Modeling – Optimized Star Schema model connecting the core transactions ledger table (Database) with specialized categorical dimensions (including item matrices like TOP 5 Sub-Cat Sales, temporal lines like KPI Growth and Filters, and localized components) to ensure fluid cross-filtering.

=> File Format – .pbix for core development workspace deployment, backed by .xlsx/.csv database assets.

## 4. Data Source
=> Source: Internal Enterprise Resource Planning (ERP) Sales Journal & Point-of-Sale (POS) Operational Ledger.

=> Structure: The metrics are calculated using an itemized retail dataset containing detailed transactional records. The metadata tracks critical parameters: Order IDs, Order Timestamps, Customer Segment categories (Consumer, Corporate), Geographic layers (Districts like Dhaka, Chittagong, Kishoreganj, Meherpur), core Product Categories (Furniture, Office Supplies, Technology), Sub-Categories (Phones, Chairs, Storage, Binders, Tables), numerical values (Sales, Quantities, Discounts, and net Profits), and Shipping profiles.

## 5. Features / Highlights

## STEP 1 - Start with the Business Problem
The executive leadership and retail merchandising teams faced significant coordination blindspots regarding seasonal margin leakages and uneven category performance. Although overall sales numbers appeared robust, the business could not easily pinpoint why net profits did not scale uniformly across all product segments, which inventory types carried heavy discounting structures at the expense of profitability, or which regional divisions were underperforming relative to their population size. Without unified visualizations, the team risked over-allocating capital toward slow-moving categories that bloated warehouse holding costs.

## STEP 2 - Define the Goal of the Dashboard
The main objective of this dashboard was to deploy an end-to-end "Retail Single Source of Truth" that monitors sales velocity, validates category profit contributions, and maps regional demand centers. It focuses on evaluating the exact relationship between gross revenue generated and net profits captured, tracking monthly demand shifts (from slower cycles like February up to peak windows like September and November), and highlighting top-performing sub-categories to optimize procurement cycles.

## STEP 3 - Walk Through the Key Visuals
=> Executive Summary KPI Blocks: Positioned prominently at the header for immediate operational status verification, tracking Total Sales (1,342,420 BDT), Total Net Profit (175,234 BDT), Total Units Sold (23,733 Quantity), and Total Order Transactions (5,999 Count).

=> Monthly Sales vs. Profit Velocity Chart: A continuous trend visual plotting seasonal variations across months—showing clear revenue spikes in September (163K Sales / 20.7K Profit) and November (194.5K Sales / 14K Profit), contrasted against baseline low-velocity cycles like February (43.1K Sales / 6.6K Profit).

=> Category Contribution Shares: A set of structured layout components dividing business weight by core lines, proving that Technology holds the largest sales share (37.1%) and the highest profit yield (90.4K BDT), followed by Office Supplies (32% Sales / 74.7K Profit), while Furniture reveals a margin red flag (30.8% Sales but only 9.9K Profit).

=> Top 5 Sub-Category Performance Ladder: A horizontal bar visual ranking the absolute revenue drivers of the inventory line, identifying Phones (184.3K BDT) and Chairs (179.4K BDT) as the leading products, followed closely by Storage (128.4K BDT), Binders (122.4K BDT), and Tables (121.7K BDT).

=> Geographic Revenue Heatmap: A data-driven localized visualization mapping store revenues across districts, calling out high-yielding market hubs like Kishoreganj (53.2K BDT) and Chuadanga (48K BDT) compared to developing nodes.

## STEP 4 - Highlight the Insight
By cross-filtering the Category Contribution Share against the Top 5 Sub-Category Performance Ladder, a major commercial discrepancy was discovered: although the Furniture category holds more than 30% of total company sales volume, its actual profit conversion is dangerously low, generating only 9.9K BDT in net profit. The visuals showed that while big-ticket items like Chairs and Tables generate massive top-line sales revenue, aggressive discount strategies or high underlying procurement costs within the Furniture line are heavily eroding business margins. In contrast, Technology and Office Supplies act as highly efficient cash drivers.

## STEP 5 - Show the Business Impact
Equipped with these visual insights, the corporate steering committee can take targeted operational actions to protect profit margins. Leadership can immediately adjust product pricing and reduce excessive discounting parameters on low-margin Furniture lines, reallocate seasonal marketing spend toward high-yielding Technology groups (especially leading into peak buying cycles like September), and customize geographic inventory distributions to perfectly match verified high-performing district demand hubs like Kishoreganj.

## SCREENSHORTS/DEMOS
Example:<img width="1363" height="702" alt="Retail Sales Dashboard" src="https://github.com/user-attachments/assets/810b78f9-9cac-47a9-96c0-774886e0153f" />



