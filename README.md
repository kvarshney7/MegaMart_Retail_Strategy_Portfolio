# MegaMart Strategic Retail Analysis
### *Optimizing Profitability & Customer Retention through Data Science*

## Executive Summary
This project analyzes 2 years of retail transaction data (5,000+ records) from **MegaMart** to identify revenue drivers, assess profit margins, and segment customers. 

By integrating **Python (for statistical EDA)** and **Power BI (for interactive reporting)**, this analysis uncovers a critical reliance on high-volume/low-margin Electronics and identifies a significant churn risk in the customer base. The project culminates in a **Strategic Business Report** proposing a 3-pillar strategy to improve profitability by an estimated **15-20%**.

---

## Project Deliverables
| File | Description |
| :--- | :--- |
| **[MegaMart_Retail_Strategy_Analysis.pdf](/main/MegaMart_Retail_Strategy_Analysis.pdf)** | Full Data Analysis & RFM Segmentation (Readable Format). |
| **[STRATEGIC BUSINESS REPORT.pdf](/main/STRATEGIC%20BUSINESS%20REPORT.pdf)** | Executive Memo summarizing findings & recommendations. |
| **[MegaMart_Dashboard.pbix](/main/sales%20dashboard%20kaggle.pbix)** | Interactive Power BI file. |
| **[Source Code (.ipynb)](/main/MegaMart%20Strategic%20Business%20Analysis.ipynb.json)** | Python code for data cleaning, EDA, and statistical tests. |

---

## Tools & Technologies
* **Python:** Pandas, NumPy (Data Cleaning & Feature Engineering)
* **Visualization:** Seaborn, Matplotlib (Statistical Analysis)
* **Business Intelligence:** Power BI (Interactive Dashboard, DAX Measures)
* **Techniques:** RFM Segmentation, Cohort Analysis, Profit Margin Testing

---

## Key Insights & Findings

### 1. Financial Trends (Seasonality)
* **Observation:** Revenue peaks significantly in **Q4 (Nov-Dec)** due to holiday demand but suffers a 35% slump in Q1.
* **Business Impact:** Current inventory stocking is reactive. Operational efficiency decreases during Q1 slumps.

### 2. Product Strategy (Volume vs. Risk)
* **The Issue:** **Electronics** drive the most revenue but have the most volatile profit margins (often negative due to discounting).
* **The Solution:** **Fashion** categories show lower volume but highly consistent, positive margins. 
* **Action:** Shift marketing spend from Electronics to Fashion to stabilize company-wide profit.

### 3. Customer Intelligence (RFM Segmentation)
Using Recency, Frequency, and Monetary (RFM) analysis, we segmented the customer base:
* **Champions (15%):** High-value VIPs.
* **At Risk (30%):** Customers who haven't purchased in >180 days.
* **Action:** Immediate "Win-Back" campaign targeting the 'At Risk' segment is required to prevent permanent churn.

---

## Visualizations

### 1. Python Analysis (Statistical Deep-Dive)
*Identifying the Profitability Risk in Electronics:*
![Profit Analysis](/images/MonhtlyRevenueVsProfitTrajectory.png)

### 2. Power BI Dashboard (Operational View)
*Interactive view of Sales, Profit, and Regional Performance:*
![Dashboard Screenshot](/images/Dashboard%20pdf_page-0001.jpg)

---

## Strategic Recommendations

Based on the analysis, the following actions are recommended (detailed in the **[Strategic Report](reports/STRATEGIC_BUSINESS_REPORT.pdf)**):

1.  **Merchandising Mix:** Cap discounts on Electronics at **10%** and increase Fashion inventory in the North Region to test demand elasticity.
2.  **Retention Strategy:** Launch a "We Miss You" automated email flow offering a one-time 15% coupon specifically to the **"At Risk"** RFM segment.
3.  **Operational Efficiency:** Implement JIT (Just-In-Time) inventory stocking for Q4 to reduce holding costs during the Q1 slump.

---

## How to Run
1.  **Jupyter Notebook:**
    * Clone the repo.
    * Install requirements: `pip install pandas seaborn matplotlib openpyxl`
    * Run `notebooks/MegaMart_Retail_Strategy_Analysis.ipynb`
2.  **Power BI:**
    * Download the `.pbix` file from the `dashboard/` folder.
    * Open in Power BI Desktop to interact with slicers and filters.

---
**Author:** [Your Name]  
**Connect:** [Your LinkedIn Profile Link]
