# Customer Churn & Revenue Risk — Executive Summary

## Business Context
A subscription-based company observed stable topline revenue but increasing customer turnover.  
This analysis evaluates customer churn through a revenue lens to identify high-impact retention opportunities and inform targeted intervention strategies.

---

## Key Insights
- **15% of customers account for ~50% of projected revenue loss**, driven by high-value, mid-tenure segments.
- Month-to-month contracts show the highest churn rate, but **longer-tenure customers contribute more to absolute revenue risk**.
- Contract type, tenure, and payment method are the strongest predictors of churn.
- Blanket retention campaigns are inefficient; targeted intervention significantly improves ROI.

---

## Revenue at Risk
- Estimated monthly revenue at risk from churn: **$X**
- Top decile of at-risk customers represents **Y% of total churned revenue**
- Retaining just the top-risk segment could reduce revenue loss by **Z%**

---

## Recommended Actions
1. Prioritize retention incentives for high-revenue, mid-tenure customers approaching contract renewal.
2. De-emphasize retention spend on low-value, short-tenure churners.
3. Introduce early-warning churn monitoring using contract and usage signals.

---

## Business Impact Scenario
| Strategy | Customers Targeted | Estimated Cost | Revenue Saved | ROI |
|--------|-------------------|---------------|--------------|-----|
| Target Top 10% Risk | ... | ... | ... | ... |
| Contract-Based Targeting | ... | ... | ... | ... |
| No Intervention | - | 0 | 0 | - |

---

## Data & Approach (Brief)
- Dataset: IBM Telco Customer Churn
- Methods: segmentation, logistic regression, revenue-weighted risk ranking
- Focused on interpretability and decision support rather than model complexity

---

## What I Would Do Next
- Incorporate customer lifetime value instead of monthly revenue
- Test targeted retention offers through controlled experiments
- Add behavioral usage data for earlier churn detection
