# EDA Findings Summary

- 1. **Profitability by category.** Highest aggregate margin: Technology (17.4%); lowest: Furniture (2.5%). Across the categories, total sales were $2,297,201 and profit $286,397. Recommendation: prioritize margin alongside revenue in category plans, and validate category-level cost/discount drivers. Limitation: aggregate margin can hide SKU mix.

- 2. **Discount and return.** Discount vs line-item profit-margin Spearman rho=-0.645 (p=0, approximate 95% CI -0.656 to -0.634). Recommendation: review markdown guardrails and contribution margin by SKU before broad discounting. Limitation: observational correlation; pricing, product mix, and order context confound.

- 3. **Sub-category extremes.** Lowest-profit sub-category: Tables ($-17,725); highest: Copiers ($55,618). Recommendation: conduct SKU-level cost, return, and promotion review for the loss leader; protect availability for strong contributors. Limitation: no unit cost or return data.

- 4. **Regional mix.** Highest total profit region: West ($108,418); lowest: Central ($39,706). Kruskal-Wallis region test p=3.93e-49, effect ε²=0.023. Recommendation: compare regional assortment, discounting and fulfillment; avoid assuming regional differences are causal.

- 5. **Loss-making lines.** 1,871 of 9,994 lines (18.7%) have negative profit; their combined profit is $-156,131. Recommendation: build exception monitoring around repeated loss-making combinations of product, discount, and region. Limitation: line-level profitability omits overhead and returns.

**Caution:** sample fictional retail transactions; observational, line-level analysis; no causal conclusions. Statistical tests are exploratory and not multiplicity-adjusted.
