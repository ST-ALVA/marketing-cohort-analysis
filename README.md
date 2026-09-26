# Marketing Cohort & Performance Analysis
**Customer Value, Acquisition Efficiency & ROI Optimization**

---

## Executive Summary

This project evaluates the performance and efficiency of marketing acquisition channels for Showz using a full-funnel, revenue-driven approach. The analysis integrates user behavior, cohort retention, conversion dynamics, customer lifetime value (LTV), customer acquisition cost (CAC), and return on marketing investment (ROMI).

Results show that purchase decisions are highly front-loaded, with most users converting shortly after their first interaction, while long-term retention remains limited. Customer value is strongly concentrated: a small segment of users accounts for a disproportionate share of total revenue, highlighting the importance of acquisition quality over volume.

Marketing performance varies significantly by channel, and overall the budget did not pay for itself: **$329K in spend generated ~$252K in revenue (total ROMI ≈ −23%)**. Only sources 1 and 2 deliver a clear positive return: source 1 (ROMI +46%) combines low CAC with high LTV, while source 2 brings the most valuable customers (LTV $13.48) at a higher acquisition cost (ROMI +11%). Sources 5 and 9 roughly break even (+3%). Sources 3, 4, and 10 lose money, and source 3 alone absorbs 43% of the budget at a ROMI of −63%.

Based on these findings, the recommended strategy is to concentrate investment on sources 1 and 2, test break-even sources carefully before scaling them, and cut or restructure spend on money-losing channels, starting with source 3.

---

## 📌 Project Context

- **Company:** Showz (event ticketing platform)
- **Timeframe:** June 2017 – May 2018
- **Data Sources:**
  - Website visit logs
  - Purchase and revenue records
  - Marketing spend by acquisition channel
- **Primary Goal:**  
  Optimize marketing investment by understanding user behavior, customer value, and channel-level profitability.

---

## 🔍 Analytical Scope

This analysis was structured around four key business questions:

1. **How users behave and convert**
   - Session dynamics
   - Time-to-conversion
   - Retention by cohorts

2. **How revenue is generated**
   - Purchase frequency
   - Average order value (AOV)
   - Revenue concentration

3. **How customer value evolves**
   - Customer Lifetime Value (LTV)
   - LTV distribution and segmentation
   - LTV by acquisition channel and device

4. **How efficient marketing investments are**
   - Customer Acquisition Cost (CAC)
   - Return on Marketing Investment (ROMI)
   - Channel-level performance comparison

---

## 📊 Key Findings

### User Behavior & Conversion
- The majority of users convert **within the first few days** after their initial visit.
- Conversion probability drops sharply after the first weeks, limiting the impact of long-term retargeting.
- Retention stabilizes at low levels, indicating a **small but consistent core of repeat users**.

### Revenue & Customer Value
- Most users generate **low lifetime revenue**, while a small group of high-value users drives a large share of total income.
- Desktop users account for the majority of orders (≈81%), with higher average order value ($5.16 vs $4.36) and higher LTV ($7.23 vs $5.72) than touch users.
- Purchase frequency remains low overall, with most users completing a single transaction.

### Marketing Performance
| Source | Spend | CAC | LTV | ROMI |
|---|---|---|---|---|
| 1 | $20.8K | $7.01 | $10.22 | **+46%** |
| 2 | $42.8K | $12.17 | $13.48 | **+11%** |
| 5 | $51.8K | $7.56 | $7.79 | +3% |
| 9 | $5.5K | $5.09 | $5.26 | +3% |
| 4 | $61.1K | $6.05 | $5.50 | −9% |
| 10 | $5.8K | $4.45 | $3.56 | −20% |
| 3 | $141.3K | $13.82 | $5.18 | **−63%** |

- **Source 1** is the most efficient channel: low CAC, high LTV, and the highest ROMI.
- **Source 2** brings the highest-value customers; its CAC is high, but LTV still covers it.
- **Sources 5 and 9** roughly break even. Source 9 is cheap to acquire but converts more slowly and has a low average order value.
- **Sources 4 and 10** have low CAC, but their customers are worth even less, so they lose money.
- **Source 3** receives 43% of the total budget and has the highest CAC and one of the lowest LTVs, making it the largest source of losses.

---

## 🧠 Final Recommendations

Based on a combined evaluation of **CAC, LTV, ROMI, and conversion behavior**:

- **Prioritize investment in Sources 1 and 2**, the only channels with a clear positive return.
- **Maintain and optimize Source 5**, which breaks even at significant volume; small gains in conversion or order value would make it profitable.
- **Test Source 9 with a small, controlled budget increase** before scaling: acquisition is cheap, but it converts slowly and order values are low.
- **Cut or restructure spend on Sources 3, 4, and 10**, starting with source 3, which drives most of the overall loss. Validate the cut with a controlled reduction (e.g., one region or period first) to confirm revenue doesn't drop proportionally.

This approach shifts marketing strategy away from volume-driven acquisition toward **sustainable, value-based growth**.

---

#### 🛠 Tools & Technologies

- **Python:** pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Analysis:** Cohort analysis, funnel analysis, CAC / LTV / ROMI modeling
- **Environment:** Jupyter Notebook

---

#### 🎯 Why This Project Matters

This case study demonstrates how **data-driven marketing decisions** can be made even under imperfect conditions. Rather than optimizing vanity metrics, the analysis focuses on **profitability, efficiency, and long-term value**, providing a realistic framework for executive-level decision-making.