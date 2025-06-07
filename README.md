# 1. 🧾 Loan Performance Dashboard

This Power BI dashboard provides a comprehensive view of loan distribution, repayment behavior, and risk exposure across different customer segments. It is designed to help financial institutions—particularly microfinance banks and digital lenders—monitor performance, detect repayment trends, and identify risky borrower profiles.

---

## 🚩 Problem Statement
Loan institutions often deal with thousands of loan applications but lack real-time visibility into critical metrics like approval rates, default likelihood, and the impact of demographic factors on outcomes. Without a visual and dynamic dashboard, decision-making is slow, fragmented, and often biased.

---

## ✅ What This Dashboard Solves
- **Loan Performance Tracking** – Get an instant overview of how approved loans are performing across time, location, and applicant type.

- **Default Rate Visibility** – Identify patterns in loan defaults by gender, education level, marital status, and credit history.

- **Approval Bottlenecks** – Spot where and why loan approvals drop — whether it’s due to poor credit, property area, or other applicant variables.

- **Customer Segmentation** – Visual filters help understand who gets loans and who doesn’t, enabling data-driven policy improvement.






## 📊 Dashboard Overview

The dashboard is organized into key sections:

### 1. **Loan Summary KPIs**
- **Total Loan Amount**: Aggregated disbursed loan volume.
- **Total Customers**: Count of unique borrowers.
- **Default Rate**: % of loans past due beyond a threshold (e.g., 30 days).
- **Repayment Rate**: % of repaid vs disbursed amount.
- **Average Loan Size**: Useful for portfolio segmentation.

### 2. **Repayment Behavior by Customer Segments**
- Compare repayment rates across:
  - **Employment Type**: Salaried vs Self-Employed
  - **Age Group**
  - **Loan Purpose**
  - **Customer Tenure**

This helps highlight which segments are more likely to default.

### 3. **Time-based Trends**
- **Monthly Loan Disbursement**
- **Repayment Volume Over Time**
- **Default Trendline**

These time series visualizations show how loan performance evolves over time and help detect seasonal risks.

### 4. **Geographic Risk Map (if applicable)**
- View loan status across different locations or branches.
- Spot regional clusters of default or underperformance.

### 5. **Loan Product Comparison**
- Evaluate how different loan products or schemes perform.
- Identify which ones carry higher risk or lower profitability.

---

## ✅ Problem Solved

This dashboard solves a key operational and strategic problem for loan issuers:

> **How do we track loan performance, reduce defaults, and optimize who we lend to?**

It empowers decision-makers to:
- Identify high-risk segments for proactive action.
- Detect operational inefficiencies (e.g., late repayments, unusual patterns).
- Make data-backed decisions when designing new loan products or adjusting eligibility criteria.

---

## 💡 Key Insights from the Dashboard

From the demo data used, the following insights were drawn:
- **Credit History is the strongest determinant** of loan approval. Applicants with a positive credit history had over 80% approval.
- **Self-employed customers** had a significantly lower repayment rate compared to salaried ones.
- **Younger customers (<25)** showed a higher default rate.
- Loans taken for **"Business Expansion"** had better repayment consistency.
- **Repayment delays spiked in Q3**, indicating possible economic or operational disruptions during that quarter.
- **Graduate education level showed** a slightly higher approval and lower default trend compared to non-graduates.
- **Loan amount and term had a nonlinear impact** — mid-sized loans had better performance than extremely small or large ones.


These insights would guide risk modeling, customer targeting, and collection strategies.

![Screenshot 2025-06-07 115728](https://github.com/user-attachments/assets/cf2d3f68-002d-4a99-a346-523158cacf0a)

---

## 📁 File Included
[loan report dashboard.pbix](https://github.com/Jcboy101/Power-BI-Projects/edit/main/loan%20report%20dashboard.pbix): The Power BI file (open with Power BI Desktop)


---

## 📥 How to Use

1. Clone/download the repository
2. Open the `.pbix` file in Power BI Desktop
3. Replace the data source with your own loan dataset
4. Adjust filters, visuals, or DAX logic as needed

---

---



# 2. 📦 Supply Chain Analysis Dashboard – Power BI Project

This Power BI dashboard provides a comprehensive analysis of supply chain performance using key metrics across procurement, inventory, logistics, and supplier performance. Designed for strategic decision-making, the report supports supply chain managers in identifying inefficiencies, optimizing inventory levels, and improving vendor relationships.

## 🧩 Problem Statement

Managing a supply chain involves balancing cost, speed, and reliability. Organizations often struggle to track real-time supplier performance, inventory turnover, and order cycle efficiency. This dashboard aims to provide a centralized, interactive view of critical metrics to support evidence-based supply chain decisions.

## 📊 Dashboard Features

- **KPIs Overview**:
  - Total Purchase Orders
  - Average Delivery Time
  - On-Time Delivery %
  - Inventory Turnover Ratio
  - Cost Per Unit

- **Procurement Trends**:
  - Monthly purchase order volume
  - Year-over-year supplier cost analysis

- **Inventory Analysis**:
  - Inventory aging distribution
  - Overstock and understock alerts

- **Supplier Performance**:
  - On-time delivery rate by vendor
  - Defect rate and return frequency

- **Logistics and Lead Time**:
  - Average lead times per product category
  - Regional delivery performance

## 🔍 Key Insights

- 🔻 **Low On-Time Delivery Rates** from specific vendors highlight the need for renegotiation or new supplier sourcing.
- ⏱️ **Long Lead Times** on high-priority SKUs contribute to frequent out-of-stock situations.
- 📈 **High Inventory Holding Costs** are driven by excess stock of low-demand items.
- 🚚 **Delivery Time Variance** increases with shipments from certain regions, indicating potential logistic bottlenecks.

  ![Screenshot 2025-06-06 081158](https://github.com/user-attachments/assets/a3ce245e-43b8-4dce-bdd8-5145d70145b8)


## ✅ Business Impact

- Improved vendor accountability through performance tracking
- Reduced inventory holding costs by identifying slow-moving items
- Minimized stockouts with proactive lead time monitoring
- Better procurement planning based on historical trend analysis

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **DAX** for measures and KPI calculations
- **Power Query** for data shaping
- **Excel/CSV** as data source (can be extended to SQL or ERP systems)

## 📂 File Structure

- `Supply Chain Analysis Dashboard.pbix`: Power BI project file
- `README.md`: Documentation (you’re reading it)

## 🔄 Extensibility Ideas

- Integrate real-time data feeds (e.g., ERP system APIs)
- Add predictive analytics for lead time forecasting
- Create supplier scorecards with benchmarks and alerts

---

## 📫 Contact

For suggestions, collaborations, or data services, feel free to connect.

