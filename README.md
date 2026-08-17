# Customer_Analysis
DataCamp project: Will This Customer Purchase Your Product?

[README.md](https://github.com/user-attachments/files/31134441/README.md)

# Will This Customer Purchase Your Product?

Customer and conversion analysis of ~12,000 online shopping sessions: who buys, what browsing behaviour looks like, and the probability of reaching a sales target.

## Questions
- How do purchase (conversion) rates differ between new and returning customers in the November–December peak season?
- Which parts of on-site browsing time move together?
- If the returning-customer conversion rate improved by 15%, how likely is a target of 100 sales in 500 sessions?

## Data
Adapted from the Online Shoppers Purchasing Intention dataset, UCI Machine Learning Repository (DOI: 10.24432/C5F88Q), as provided with the DataCamp project.

## Method
Cleaned missing records, filtered to the Nov–Dec season, computed conversion rates per customer type, examined correlations between browsing-duration variables, and modelled the sales target with a binomial distribution (scipy).

## Key findings
- New customers convert at a noticeably higher rate (~27%) than returning customers (~20%) in the peak season.
- Time on administrative pages correlates most strongly with time on product pages (r ≈ 0.39).
- With a 15% uplift in the returning-customer rate (to ~22.5%), the probability of at least 100 sales in 500 sessions is ~90%.

## Tools
Python · pandas · NumPy · scipy · matplotlib

## Origin
Based on a DataCamp guided project ("Will This Customer Purchase Your Product?"). Code tidied, results derived programmatically rather than hardcoded, and a visualization added.
