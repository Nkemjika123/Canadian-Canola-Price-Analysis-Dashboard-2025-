# Canadian Canola Price Analysis Dashboard (2025)

##  Project Overview
This project analyzes **Canola price data in Canada for the year 2025**, using official data from **Statistics Canada**.  
The objective is to demonstrate how **raw data can be transformed into meaningful information** that supports **real-world decision-making** through data cleaning, analysis, and visualization.

The workflow follows a standard analytics pipeline:
- Data sourcing
- Data cleaning (Excel)
- Data modeling & visualization (Power BI)
- Insight generation
- Decision-making support

---

##  Objectives
- Identify a **reliable source of raw data**
- Clean and process agricultural price data
- Create **key performance indicators (KPIs)**
- Visualize trends, patterns, and regional differences
- Enable **actionable, data-driven decisions**

---

##  Data Source
- **Provider:** Statistics Canada (Government of Canada)
- **Dataset:** Farm product prices, monthly
- **Crop analyzed:** Canola
- **Time period:** January 2025 – December 2025

🔗 **Data Link:**  
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210007701

Statistics Canada is a trusted and authoritative source that ensures data accuracy, consistency, and reliability.

---

##  Data Cleaning & Preparation (Excel)

### Steps Taken:
1. Removed irrelevant metadata columns:
   - DGUID, UOM_ID, SCALAR_FACTOR, SCALAR_ID
   - VECTOR, COORDINATE, STATUS, SYMBOL
   - TERMINATED, DECIMALS

2. Renamed columns for clarity:
   - `REF_DATE` → Date
   - `GEO` → Province
   - `Farm products` → Product
   - `VALUE` → Price

3. Ensured correct data types:
   - Date column formatted as Date
   - Price column formatted as numeric (2 decimal places)

4. Checked for:
   - Missing values
   - Duplicate records
   - Inconsistent naming

The cleaned dataset was saved as an Excel file and imported into Power BI.

---

##  Data Processing (Power BI)

Data was processed using:
- DAX measures
- Aggregations
- Filters and slicers

The analysis focuses exclusively on **Canola** to provide deeper, more targeted insights.

---

##  Dashboard

<img width="1160" height="609" alt="Screenshot 2026-01-18 145356" src="https://github.com/user-attachments/assets/5180bda7-3117-4631-aca7-fa0f900e54dd" />

---

##  Key Performance Indicators (KPIs)

### KPI 1: Average Monthly Price
- **Value:** `$631.84`
- Indicates overall market price level and stability.

### KPI 2: Price Trend (%)
- **Value:** `+0.96%`
- Shows a slight upward movement, indicating stable pricing over time.

### KPI 3: Maximum & Minimum Prices
- **Maximum Price:** `$684.00`
- **Minimum Price:** `$575.51`
- Highlights the price range and potential market risk.

---

##  Visualizations

### Line Chart – Price Trend Over Time
- Displays monthly Canola price trends
- Identifies seasonal patterns
- Shows highest price recorded in **August 2025 ($676.61)**

### Bar Chart – Average Price by Province
- Saskatchewan: `$641.73`
- Alberta: `$637.17`
- Ontario: `$616.61`

This visualization highlights regional price differences across provinces.

### KPI Cards
- Average Monthly Price
- Price Change (%)
- Highest Recorded Price
- Lowest Recorded Price

---

##  Interactive Elements
The dashboard includes slicers for:
- Province
- Date

These interactive features allow users to dynamically explore the data and customize their analysis.

---

##  Insights & Patterns Identified
- Canola prices remained **relatively stable** throughout 2025.
- A **seasonal peak** occurred in August.
- Western provinces (Saskatchewan and Alberta) recorded **higher average prices** than Ontario.
- Price volatility was moderate, indicating manageable financial risk.

---

##  Actionable Decisions & Solutions

### Decision 1: Sales Timing Strategy
**Decision:**  
Farmers should time Canola sales around peak pricing periods.

**Solution:**  
By storing harvested Canola and selling during high-price months (e.g., August), farmers can maximize revenue.

---

### Decision 2: Regional Production Focus
**Decision:**  
Agricultural producers and investors should prioritize regions with higher average prices.

**Solution:**  
Increased investment and production in Saskatchewan and Alberta can improve profitability due to stronger market performance.

---

##  Tools Used
- **Microsoft Excel:** Data cleaning and preparation
- **Power BI:** Data modeling, visualization, and dashboard creation
- **DAX:** KPI calculations and measures

---

##  Conclusion
This project demonstrates how agricultural price data can be transformed into actionable information through structured data analysis and visualization.  
By focusing on Canola prices in Canada, the dashboard provides valuable insights that support informed decisions for farmers, investors, and policymakers.

---

##  Repository Contents
- Cleaned Excel dataset
- Power BI dashboard file (.pbix)
- Documentation (README)

---

##  Author
**Nkemjika Princess Onwubuche**  
Data Analyst | Power BI | Excel | Analytics for Decision-Making
