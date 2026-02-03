# 🚗 BMW Sales Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![Data](https://img.shields.io/badge/Records-5,000-blue?style=for-the-badge)

## 🎯 Project Overview

A comprehensive **BMW Sales Analytics Dashboard** built with **Power BI**, analyzing sales performance across **26 BMW models**, **5 global regions**, **23 countries**, and **3 sales channels** (Wholesale, Dealership, Online) from **2019 to 2023**. This multi-page interactive dashboard provides actionable insights into revenue trends, model performance, regional distribution, and channel effectiveness.

## 🛠️ Tools & Technologies Used

- **Power BI Desktop** — Multi-page dashboard creation and interactive visualizations
- **Power Query** — Data cleaning and transformation
- **DAX** — Advanced measures and calculated columns
- **Data Modeling** — Star schema with fact and dimension tables
- **CSV Data Sources** — BMW sales data, stock data, country flags, car images, model details

## ✨ Key Features

### Multi-Page Dashboard Structure
- **Dashboard Page 1** — Executive summary with revenue overview, regional breakdown, and model performance
- **Model Details Page** — Individual model analysis with year-over-year trends and detailed metrics
- **Data Model Page** — Star schema architecture showing relationships between fact and dimension tables

### Advanced Analytics
- **KPI Cards** — Total revenue ($376M), quantity sold (15K units), average price (75.6K)
- **Time Intelligence** — Year, month, and weekday analysis (2019-2023)
- **Regional Analysis** — 5 regions (Africa, Asia, Europe, North America, South America) with 23 countries
- **Model Breakdown** — Performance across 26 BMW models from Z4 to electric vehicles (i3, i4, iX, iX3)
- **Channel Performance** — Wholesale (44.1%), Dealership (33.5%), Online (22.4%)
- **Country Insights** — Top performers including USA, Mexico, Canada, Nigeria, Kenya

## 💡 Key Insights

### Sales Performance Overview
- **Total Revenue:** $376,065,225 across all markets
- **Total Quantity Sold:** 15,002 units (5,000 transactions)
- **Average Price:** $75,213 per transaction
- **Price Range:** $30,016 minimum to $119,998 maximum
- **Average Units per Transaction:** 3.0 units
- **Transaction Distribution:** Relatively balanced across years (2019-2023)

### Top Performing Models
1. **BMW Z4:** $17.1M revenue (666 units sold) — Top model by revenue
2. **BMW 3 Series:** $16.2M revenue (609 units sold)
3. **BMW X4:** $16.0M revenue (593 units sold)
4. **BMW M4:** $15.7M revenue (620 units sold)
5. **BMW X1:** $15.6M revenue (604 units sold)
6. **BMW iX:** $15.1M revenue (595 units sold) — Leading electric model
7. **BMW X2:** $14.9M revenue (582 units sold)
8. **BMW 7 Series:** $14.8M revenue (556 units sold)
9. **BMW i3:** $14.7M revenue (611 units sold) — Popular electric model
10. **BMW i8:** $14.7M revenue (615 units sold)

### Regional Performance
- **Africa:** $82.3M (21.9%) — Highest revenue region with 1,091 transactions
- **South America:** $75.3M (20.0%) — 1,007 transactions
- **Asia:** $74.3M (19.8%) — 983 transactions
- **North America:** $73.9M (19.6%) — 986 transactions
- **Europe:** $70.3M (18.7%) — 933 transactions

### Top Countries by Revenue
1. **Mexico:** $25.2M (333 transactions) — Top country
2. **United States:** $25.1M (343 transactions)
3. **Canada:** $23.6M (310 transactions)
4. **Nigeria:** $18.7M (247 transactions)
5. **Kenya:** $16.9M (225 transactions)
6. **Colombia:** $16.3M (216 transactions)
7. **Egypt:** $16.2M (220 transactions)
8. **Spain:** $16.1M (212 transactions)
9. **South Africa:** $15.9M (208 transactions)
10. **Chile:** $15.7M (209 transactions)

### Sales Channel Analysis
- **Wholesale:** $165.8M (44.1%) — Primary channel with 2,215 transactions
- **Dealership:** $126.0M (33.5%) — 1,664 transactions
- **Online:** $84.3M (22.4%) — 1,121 transactions, showing growing digital adoption

### Yearly Trends (2019-2023)
- **2019:** 990 transactions
- **2020:** 982 transactions (slight decline, likely COVID-19 impact)
- **2021:** 1,034 transactions (recovery and growth)
- **2022:** 1,020 transactions (sustained performance)
- **2023:** 974 transactions

### Model Categories Performance
- **SUV Models (X Series):** Strong performance across X1, X2, X3, X4, X5, X6, X7
- **Performance Models (M Series):** High revenue from M2, M3, M4, M5, M8
- **Electric Vehicles:** Growing presence with i3, i4, i8, iX, iX3
- **Luxury Sedans:** Solid sales from 3 Series, 5 Series, 7 Series, 8 Series
- **Sports Cars:** Z4 leads as top revenue generator

## 📸 Dashboard Screenshots

### Main Dashboard
*Executive overview showing total revenue of $376M, regional distribution across 5 continents, and model performance metrics*

![Dashboard Overview](Dashboard-1.png)

### Model Details Page
*Individual model analysis showing BMW 8 Series with average price of 75.60K, yearly sales trends from 2019-2023, and quarterly revenue breakdown of $1.13bn*

![Model Details](Model-details.png)

### Data Model Architecture
*Star schema showing relationships between fact table (BMW Sales Data), dimension tables (Countries with Flags, Car Images, dim model, dim channel, Calendar, PERIOD), and all measure table*

![Data Modeling](Data-modilling.png)

## 🚀 How to Use

### Prerequisites
1. **Power BI Desktop** — Download from https://powerbi.microsoft.com/desktop/

### Setup Instructions

1. **Clone the repository:**
git clone https://github.com/eslamrezk14/BMW-Sales-Analysis.git
cd BMW-Sales-Analysis

2. **Data Files Required:**
   - `BMW_Sales_Data.csv` — Primary sales transaction data (5,000 records)
   - `BMW_Data.csv` — BMW stock price historical data
   - `Countries-with-Flags-URL.csv` — Country flag images for visuals
   - `Car-Images.csv` — BMW model images for dashboard
   - `Model-details.jpg` — Model visualization reference

3. **Open Power BI Dashboard:**
   - Open the `.pbix` file in Power BI Desktop
   - Refresh data connections if needed

4. **Navigate Dashboard Pages:**
   - **Dashboard:** Main overview with revenue, regional, and model metrics
   - **Model Details:** Drill into specific BMW model performance
   - **Data Model:** View relationships and schema architecture

5. **Apply Filters:**
   - Filter by Year (2019-2023)
   - Filter by Month or specific date ranges
   - Select Region, Country, or Sales Channel
   - Click on specific BMW models for detailed analysis

## 📊 Key Metrics Tracked

| Category | Metric | Value | Description |
|----------|--------|-------|-------------|
| **Financial** | Total Revenue | $376.1M | Complete revenue across all markets |
| **Financial** | Average Price | $75,213 | Mean transaction value |
| **Financial** | Revenue Range | $30K - $120K | Min and max transaction values |
| **Sales** | Total Quantity | 15,002 units | Total BMW vehicles sold |
| **Sales** | Transactions | 5,000 | Total number of sales transactions |
| **Sales** | Avg Qty/Transaction | 3.0 units | Average units per sale |
| **Products** | Models | 26 | BMW model variants tracked |
| **Geography** | Regions | 5 | Continental coverage |
| **Geography** | Countries | 23 | Global market presence |
| **Channels** | Wholesale | 44.1% | Primary sales channel |
| **Channels** | Dealership | 33.5% | Traditional retail channel |
| **Channels** | Online | 22.4% | Digital sales channel |
| **Time Period** | Years | 2019-2023 | 5-year analysis period |

## 📂 Project Structure

BMW-Sales-Analysis/
│
├── Dashboard-1.jpg                    # Main dashboard screenshot
├── Model-details.jpg                  # Model details page screenshot
├── Data-modilling.jpg                 # Data model architecture diagram
├── BMW_Sales_Data.csv                 # Primary sales data (5,000 transactions)
├── BMW_Data.csv                       # BMW stock price historical data
├── Countries-with-Flags-URL.csv       # Country flag image URLs
├── Car-Images.csv                     # BMW model image URLs
├── BMW-Sales-Dashboard.pbix           # Main Power BI dashboard file
└── README.md                          # Project documentation (this file)

## 🗄️ Data Model

**Star Schema Architecture:**

### Fact Table
- **BMW_Sales_Data** — Central fact table with sales transactions
  - Date, Year, Model, Revenue, Quantity Sold, Region, Country, Channel
  - 5,000 records spanning 2019-2023

### Dimension Tables
- **Countries with Flags URL** — Country dimension with flag image URLs
  - Country, Country code, Flag, Region
  - 23 countries across 5 regions

- **Car Images** — BMW model images dimension
  - img, Model
  - Visual references for all 26 BMW models

- **dim model** — Model dimension
  - img, Model, model id
  - Model categorization and metadata

- **dim channel** — Sales channel dimension
  - Channel, channel id
  - 3 channels: Wholesale, Dealership, Online

- **Calendar** — Date dimension
  - Date, Month, Monthnum, Qtr, Weekday
  - Time intelligence support

- **PERIOD** — Period dimension
  - PERIOD, PERIOD Fields, PERIOD Order
  - Custom period analysis

- **all measure** — Calculated measures table
  - Column, AVG PRICE, AVG PRICE FORMATTED
  - Qty sold, QTY sold Area Sparkline (no one...)
  - QTY sold growth, Qty sold fy, Qty sold variance
  - Qty sold Variance % arrow

### Relationships
- BMW_Sales_Data ↔ dim model (Many-to-One via Model)
- BMW_Sales_Data ↔ dim channel (Many-to-One via Channel)
- BMW_Sales_Data ↔ Calendar (Many-to-One via Date)
- BMW_Sales_Data ↔ Countries with Flags URL (Many-to-One via Country)
- Car Images ↔ dim model (One-to-One via Model)

## 🎓 Skills Demonstrated

- **Data Visualization** — Multi-page interactive dashboards with executive KPIs
- **Data Modeling** — Star schema design with fact and dimension tables
- **ETL Processes** — Data integration from multiple CSV sources
- **Advanced DAX** — Custom measures for sales metrics and time intelligence
- **Business Intelligence** — Revenue analysis, regional performance, channel optimization
- **Visual Design** — Professional dashboard layout with consistent branding
- **Interactive Filtering** — Year, month, region, country, channel, and model slicers
- **Geospatial Analysis** — Regional and country-level performance tracking
- **Time Intelligence** — Year-over-year trends, monthly patterns, quarterly analysis
- **Sales Analytics** — Channel effectiveness, model performance, pricing analysis

## 📈 Business Value

This BMW Sales Analytics solution enables:

- **Executive Decision Making** — $376M revenue overview with key performance indicators
- **Regional Strategy** — Identify high-performing regions (Africa 21.9%, South America 20.0%)
- **Product Portfolio Optimization** — Top models (Z4 $17.1M, 3 Series $16.2M, X4 $16.0M)
- **Channel Strategy** — Wholesale dominance (44.1%) vs growing Online presence (22.4%)
- **Market Expansion** — Country-level insights for targeted growth (Mexico, USA, Canada top 3)
- **Inventory Planning** — Model demand patterns and quantity sold trends
- **Pricing Strategy** — Average price analysis ($75K) and transaction value distribution
- **Performance Tracking** — Year-over-year trends from 2019-2023
- **Electric Vehicle Strategy** — EV model performance (i3, i4, iX, iX3) analysis
- **Competitive Positioning** — Model category performance across SUVs, sedans, sports, and EVs

## 📬 Contact Information

**Eslam Rezk**  
*Data Analyst | Business Intelligence Specialist*

- **GitHub:** https://github.com/eslamrezk14
- **LinkedIn:** [Your LinkedIn Profile URL]
- **Email:** [Your Email Address]
- **Portfolio:** [Your Portfolio Website]

---

**⭐ If you found this project helpful, please consider giving it a star!**

**💼 This project demonstrates expertise in Power BI, data modeling, DAX, business intelligence, and sales analytics. Open to collaboration and feedback.**

---

## 📝 License

This project is available for educational and portfolio purposes. Please provide attribution if you use or reference this work.

## 🙏 Acknowledgments

- BMW sales data used for analytical demonstration purposes
- Power BI community for visualization best practices
- Data modeling principles from Kimball methodology (star schema)

---

**Last Updated:** February 2026  
**Dashboard Version:** 1.0  
**Data Period:** 2019-2023 (5 years)  
**Total Records:** 5,000 transactions  
**Total Revenue Analyzed:** $376,065,225
