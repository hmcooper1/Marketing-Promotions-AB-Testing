# Marketing-Promotions-AB-Testing
## Overview
This project aims to identify the most effective marketing campaign for promoting a new product in a fast-food chain. Campaign effectiveness is measured by total sales. In randomly selected markets, each location utilized a different promotional strategy to sell the new menu item, and sales data were collected over the first four weeks. This approach mirrors an A/B testing framework, comparing multiple promotional strategies to determine the most successful one.
## Goal
Develop a strategic plan to select the most effective promotions tailored to specific locations, maximizing sales success of the new menu item.
## Data Source
The data for this project can be accessed [here](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test/data).
## Statistical Methods
- Assumption checks:
  - Shapiro-Wilk test, Levene's test
- Parametric methods:
  -  ANOVA, t-test
- Non-parametric methods:
  - Kruskal-Wallis test, Mann-Whitney U Test
- Post-hoc analysis:
  - Dunn's test
## Summary of Results
This analysis showed that promotions 1 and 3 generated significantly higher sales than promotion 2. Further investigation into promotions 1 and 3 by market size revealed that promotion 1 significantly outperformed promotion 3 in medium-sized markets. However, there were no significant differences between promotions 1 and 3 in small and large markets.
## Recommendations
- Discontinue the use of promotion 2 across all markets
- Prioritize promotion 1 in medium-sized markets
- For small and large markets, choose between promotions 1 and 3 based on cost efficiency, as their performance was statistically comparable

