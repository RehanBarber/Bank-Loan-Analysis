# Bank-Loan-Summary-and-Overview-Excel-Dashboard
# Overview

This repository contains an analysis of a bank loan dataset with 38,572 entries, focusing on loan performance, borrower demographics, and key financial metrics. The data was processed in Excel to generate summaries, dashboards, and visualizations. Primary goals: Identify risk factors, repayment trends, and opportunities for lending optimization.
Dataset Source: Provided Excel file ("Bank Loan Summary and Overview Dashboard.xlsx") with sheets for raw data, design calculations, and dashboards.

# Primary KPIs

Total Loan Applications: 38,572, 
Total Funded Amount: $435,733,175, 
Total Amount Received: $473,043,890. 

# Secondary KPIs

Average Interest Rate: 12.05%, 
Average Debt-to-Income (DTI) Ratio: 13.33%, 

Good Loan Percentage: 86.17% (Applications: 33,239; Funded: $370,200,950; Received: $435,759,127), 

Bad Loan Percentage: 13.83% (Applications: 5,333; Funded: $65,532,225; Received: $37,284,763). 


# Loan Status Breakdown:

Fully Paid: 32,141 (83.32%)
Current: 1,098 (2.85%)
Charged Off: 5,333 (13.83%)


# Term Distribution:

36 months: 28,234 (73.18%)
60 months: 10,338 (26.82%)



# Major Findings

Geographic Distribution: Top states include California (6,893 applications, 17.87%), New York (3,701, 9.60%), and Texas (2,661, 6.90%). Lower activity in states like Iowa (5) and Maine (3) suggests regional lending biases or market opportunities.

Loan Purposes: Debt consolidation is the most common (18,214 or 47.22%), followed by credit card refinancing (4,998 or 12.96%) and other (3,824 or 9.91%). This indicates a focus on consumer debt relief.

Employment Length Insights: Borrowers with 10+ years of experience (8,868 or 22.97%) have better repayment rates. Shorter tenures (e.g., <1 year: 4,574 or 11.86%) correlate with higher charged-off rates, emphasizing the need for tenure-based risk scoring.

Home Ownership Trends: Renters dominate (18,438 or 47.81%), with higher average DTIs than mortgage holders (17,195 or 44.58%). This could inform targeted products for renters.

Temporal Trends: Peak applications in November (20,850 or 54.05%) and October (11,197 or 29.03%). Month-over-Month growth from August to September was 221.83% in funded amount, possibly due to end-of-year financial planning.

Risk Highlights: Bad loans have higher average interest rates (13.88%) and DTIs (14.00%) compared to good loans (11.64% rate, 13.17% DTI). Charged-off loans total $65.5M funded but only $37.3M received, representing significant losses.

# Methodology

Data Processing: Used Excel pivots, formulas, and charts from the "Design" sheet for aggregations (e.g., SUM, AVERAGE, COUNT).

Visualizations: Includes state maps, pie charts for terms/purposes, bar charts for trends (embedded in dashboards).

Assumptions: Dates are in numeric format (e.g., 44447 for ~Jan 2012); focused on provided summaries to avoid raw data parsing issues.
