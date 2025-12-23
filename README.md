# Customer Churn & Revenue Risk — Executive Summary

## Business Context
A subscription-based company observed stable topline revenue but suspected customer churn was masking long-term growth risk.  
This analysis evaluates churn through a revenue lens to identify high-impact retention opportunities and guide targeted intervention decisions.


---

## Key Insights
- Customer churn rate is approximately **26.5%**, driven primarily by month-to-month contracts.
- Month-to-month customers account for the majority of estimated monthly revenue at risk (~$110K).
- Revenue risk is moderately concentrated: the top **20%** of customers account for just over **50%** of total revenue at risk.
- To capture ~80% of revenue risk, targeting closer to **40%** of customers is required.

---

## Retention Strategy Results
Simulated retention strategies highlight a clear efficiency tradeoff:

| Strategy | Customers Targeted | Revenue Saved | Cost | ROI |
|--------|-------------------|---------------|------|-----|
| Top 10% Risk | 704 | ~$13.1K | ~$7.0K | **1.86** |
| Top 20% Risk | 1,408 | ~$22.5K | ~$14.1K | 1.60 |
| Top 40% Risk | 2,817 | ~$33.8K | ~$28.2K | 1.20 |

ROI declines steadily as coverage expands.

---

## Recommendation
Retention efforts should focus on customers with the highest expected revenue loss rather than applying incentives broadly.

Targeting the top 10% of at-risk customers provides the strongest return on investment. Expanding to the top 20% increases total revenue saved, but with a clear drop in efficiency. Broader targeting shows diminishing returns and should only be considered if revenue preservation outweighs cost efficiency.

---

## Data & Approach (Brief)
- Dataset: IBM Telco Customer Churn
- Methods: segmentation, logistic regression, revenue-weighted risk ranking
