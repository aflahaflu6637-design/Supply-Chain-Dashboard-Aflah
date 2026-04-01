# Supply Chain Performance & Risk Analysis Dashboard

## Project Overview
Interactive Power BI dashboard built to analyze supply chain performance using the **DataCo Supply Chain Dataset** (180,519 records). 

The dashboard provides end-to-end visibility into On-Time Delivery (OTD), shipment delays, logistics efficiency, profitability trends, and regional performance.

## Objective
To identify bottlenecks in the supply chain, improve On-Time Delivery rate, reduce delays, control logistics costs, and increase profitability through data-driven insights.

## Dashboard Pages

1. **Cover Page** – Project introduction
2. **Executive Overview** – High-level KPIs, trends, and On-Time vs Late distribution
3. **Delivery Performance** – Detailed delay analysis by shipping mode and region
4. **Profitability Analysis** – Profit trends, margin, and profit by product category
5. **Regional & Shipping Insights** – Regional OTD% and profit performance

## Key Features
- Interactive slicers (Year, Quarter, Product Category, Shipping Mode, Order Region)
- Star Schema data model with proper time intelligence (`Dim_Date` table)
- DAX measures for OTD%, Late Delivery Rate, Profit Margin, YoY trends, etc.
- Conditional formatting and professional visuals

## Technologies Used
- Power BI Desktop
- Power Query (for data cleaning and transformation)
- DAX (Measures and Calculated Columns)
- Star Schema Data Modeling

## Dataset
- **Name**: DataCoSupplyChainDataset.csv
- **Rows**: 180,519
- **Original Columns**: 53
- **Source**: Kaggle - DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS

## Key Insights
- Overall On-Time Delivery (OTD) rate is **45.17%**
- Late Delivery Rate is **54.83%**
- Standard Class shipping has the highest number of late orders
- Profit is concentrated in a few categories (Fishing is the top contributor at ₹0.76M)
- Significant variation exists across regions and shipping modes

## Deliverables
- `Supply_Chain_Dashboard_Aflah.pbix`
- `Supply_Chain_Dashboard_Full_Report_Aflah.pdf`
- `Supply_Chain_Analysis_Report_Aflah.pdf`
- `Dataset_Assessment_Aflah.pdf`
- BRD & FRD Documents

## Author
**Aflah**  
Power BI Intern Project  
April 2026

---

**How to use it:**

1. Open **TextEdit** on your Mac.
2. Go to **Format → Make Plain Text**.
3. Paste the entire text above.
4. Save as: `README.md` (make sure the extension is `.md`, not `.txt`).

Would you like me to make any changes to this README before you save it?

Or is this version fine?

Just say **"This is good"** or tell me what you want to add/remove. 

After that, we can finalize the folder and GitHub push.
