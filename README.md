# global-sales-performance-analysis
End-to-end business intelligence project: Data auditing, ABC analysis, and regional performance reporting using Advanced Google Sheets.
Global Sales Performance & ABC Analysis
Project Overview
This project is an end-to-end analysis of global transaction data. I conducted a full data audit, resolved critical integrity issues, and performed a multidimensional analysis to provide strategic business recommendations.
Tools: Google Sheets (Advanced), Pareto Analysis, Data Modeling. 

<img width="720" height="1040" alt="Visuals" src="https://github.com/user-attachments/assets/2f213829-5d8e-40a0-9943-70141d06adb1" />

🛠️ Data Audit & Integrity (The "Cleaning" Phase)
I identified and mitigated several high-risk data issues:
Date Parsing Risks: Resolved date-as-text issues and standardized MM/DD/YYYY formats to prevent chronological analysis failure.
Geographic Attribution: Identified a 5–7% data gap where country codes were missing; standardized these as "Unknown Country" to maintain dataset balance while acknowledging the gap.
Type Conversion: Converted financial strings into numeric formats to allow for accurate margin calculations.
📈 Key Analysis Findings
The Pareto Principle (ABC Analysis): Identified that Office Supplies is the primary revenue driver, while Clothes and Baby Food represent high-margin (up to 67%) opportunities for growth.
Market Concentration: Discovered that the top 20 countries drive approximately 82% of revenue, highlighting a high-concentration risk model.
Operational Efficiency: Classified shipment turnaround times; identified that high-revenue markets in Europe often face logistical bottlenecks compared to mid-tier efficient markets.
💡 Strategic Recommendations
Diversification: Reduce over-reliance on the European market by targeting high-margin categories in emerging regions.
Data Capture: Implement stricter validation at the point of sale to eliminate the "Unknown Country" data gap.
