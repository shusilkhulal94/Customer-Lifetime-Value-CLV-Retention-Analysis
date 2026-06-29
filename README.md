# Customer-Lifetime-Value-CLV-Retention-Analysis
# Project Overview 
Business often struggles to identify the most valuable customers and understand whether customer remain engaging over time.
This project uses RFM Segmentation, Customer Lifetime value (CLV), and Cohort Analysis to identify high-value customers, analysis customer behavior pattens, and measure customer retention performance. This insight can help business improve customer retention, personalize marketing efforts, and prioritize high value customers to maximize long term revenue.

# Objectives
-	Identify high value customer segments using RFM analysis.
-	Calculate customer lifetime value (CLV) to measure customer profitability.
-	Analyze customer purchasing behavior through recency, frequency, and monetary spending    patterns.
-	Measure customer retention using cohort analysis.
-	Identify opportunity to improve customer retention and customer loyalty.
- Provide data-driven recommendations to increase customer lifetime values and retention.


# Dataset
- Online Retail II
- 407,664 transactions
- 4,312 unique customers
-	Date Range: 2009-2010

# Tools
- Python
- Pandas
- Tableau


# Data Preperation
- Removing records with missing Customer IDs.
- Converted InvoiceDate to datetime format.
- Created Revenue Column (Quantity * Unit Price).
- Created snapshot data for RFM analysis.
- Prepared cohort tables for retention analysis.


# Key Findings
-	Champions generated the highest revenue at $5.79M, making them the business’s most valuable customer segment.
-	Lost Customers formed the largest customer segment with 1,346 customers, indicating a significant opportunity.
-	Potential Loyalists accounted for 1,193 customers, representing a strong opportunity for future customer growth through trageted retention.
-	VIP customers contributed the highest customer lifetime value at approximately $6.91M.
-	Average customer retention was 20.5% in month 2 and increased slightly to 22.4% in month 3.
-	overall cohort retention rate was 34.6% indicating opportunities to improve long term customer retention.
-	Most customer cohorts experienced declining retention over time, emphasizing the need for strong retention strategies.


# Business Recommedations
-	Prioritize re- engagement campaigns for lost customers.
-	Strengthen loyalty programs for champions and VIP customers to protect the highest revenue generating customers.
-	Develop personalized campaigns for potential loyalists to encourage repeat purchases and convert them into long term loyal customers.
-	Improve customer onboarding and post purchase communication during the first few months, as month 2 retention drops to 20.5% indicating early customer churn.
-	Allocate marketing resources based on customer value by prioritizing high CLV customers while investing in targeted win-back campaigns for lost customers.
-	Analysis cohort retention trends regularly to measure the effectiveness of retention strategies and identify opportunities for continuous improvement.

# Tableau Dashboard
https://public.tableau.com/views/Final_Customer_segmentation/CustomerSegmentationLifeTimeValue?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
https://public.tableau.com/views/Final_Customer_retentation/CustomerRetentationCohortAnalysisDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
