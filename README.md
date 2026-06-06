# 🎯 RFM-Based Customer Segmentation & Behavioral Analytics Dashboard

Retail businesses often treat all customers equally, missing revenue concentration patterns and churn signals. This project applies **RFM (Recency, Frequency, Monetary)** analysis to segment customers into actionable behavioral cohorts using **SQL** for metric engineering and **Power BI** for interactive reporting. The objective is to enable data-driven marketing prioritization and customer lifetime value optimization. Technologies used include **SQL Server**, **Power BI Desktop**, **Power Query (M)**, and **DAX**. The final dashboard helps marketing and CRM teams allocate resources toward high-value customers while re-engaging at-risk segments.

---

## 📸 Dashboard Preview

![Dashboard Screenshot](https://github.com/bhavishgupta/customer-segmentation-rfm-analysis/blob/main/rfm_analysis_dashboard.png)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development & segment visualization |
| Power Query (M) | Data transformation, date aggregations & normalization |
| DAX | Revenue by segment, avg order value, frequency measures |
| Data Modeling | Star schema — transactions, customers, date dimension |

---

## 📌 Key KPIs

- **Total Customers Analyzed** — Total unique customers scored across all RFM tiers
- **Total Revenue** — Aggregate monetary value across all customer segments
- **Champions Share (%)** — Percentage of customers classified in the top RFM tier
- **At-Risk Revenue** — Total revenue attributable to customers showing declining engagement
- **Avg Order Value by Segment** — Mean transaction value broken down across all 5 RFM cohorts

---

## 🔍 Key Insights

- The **top 20% of customers** (Champions and Loyal) contribute over **60% of total revenue**, confirming a strong Pareto concentration that warrants a premium loyalty investment.
- **At-Risk customers** have the highest historical spend among disengaged cohorts — a targeted win-back campaign for this segment offers the highest recovery ROI of any retention initiative.
- **Hibernating and Lost customers** represent a recoverable revenue opportunity if approached with time-bound offers; longer inactivity correlates with sharply declining re-engagement probability.
- **New customers** show higher purchase frequency but below-average monetary value — structured upsell and cross-sell journeys in the first 90 days can accelerate progression to the Loyal tier.
- **Monetary score alone** is a weak predictor of future churn risk; combined Recency + Frequency signals are significantly stronger indicators for proactive intervention.
- Customers in the **"Promising" segment** demonstrate recent engagement but low frequency — nurturing campaigns here yield measurable conversion lift to Loyal status.
- The **Champions segment** drives repeat purchases at nearly **3× the frequency** of average-tier customers, making retention of this group the single highest-leverage growth action.

---

## ⚙️ Dashboard Features

- **Interactive slicers** — filter by RFM segment, date range, and customer tier
- **Drill-down analysis** — individual customer-level RFM score exploration
- **Dynamic KPI cards** — revenue, customer count, and avg order value per segment
- **Customer segmentation view** — visual distribution across all 5 RFM cohorts
- **Revenue concentration analysis** — Pareto-style contribution chart by segment
- **Cross-filtering visuals** — all charts update in sync on segment selection

---

## 🔗 Live Dashboard

🔗 [View Power BI Dashboard](https://github.com/bhavishgupta/customer-segmentation-rfm-analysis/blob/main/rfm_analysis_dashboard.png)

---

## ✅ Conclusion

This project solved a critical marketing prioritization problem: understanding which customers deserve the most attention and why. By applying RFM  through a Power BI dashboard, the analysis exposed that a small fraction of customers drive the majority of revenue — while a sizable at-risk cohort represents recoverable attrition. Decision-makers can use this dashboard to direct loyalty investment toward Champions, launch precision win-back campaigns for At-Risk customers, and design onboarding sequences that convert new buyers into long-term, high-value customers.
