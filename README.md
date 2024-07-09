# Hypothesis Prioritization and A/B Testing

## Project Description

This project aims to identify and prioritize various hypotheses that could potentially boost the revenue of a large e-commerce store. Following the hypothesis prioritization, an A/B test will be conducted to evaluate the effectiveness of the top hypotheses. The analysis of the A/B test results will provide actionable insights for strategic decision-making to enhance the store's revenue performance.

Objectives
<code> Prioritize Hypotheses: </code>

> - Apply the ICE (Impact, Confidence, Effort) framework to rank hypotheses.
> - Apply the RICE (Reach, Impact, Confidence, Effort) framework to rank hypotheses.
> - Compare the prioritizations from both frameworks and explain any differences.

<code> Conduct and Analyze A/B Test: </code>

> - Analyze cumulative revenue by test group.
> - Analyze cumulative average order size by test group.
> - Compare relative differences in cumulative average order size between test groups.
> - Calculate and plot daily conversion rates for both groups.
> - Identify and analyze outliers in the number of orders per user and order prices.
> - Determine statistical significance of differences in conversion rates and average order sizes between groups, both with raw and filtered data.
> - Make a final decision based on test results.

## Data Dictionary

The <code>hypothesis_us.csv</code> table will be used for the first part of the project.

- <code>hypothesis</code>: brief descriptions of the hypotheses
- <code>reach</code>: user reach, on a scale of 1 to 10
- <code>impact</code>: impact on users, on a scale of 1 to 10
- <code>confidence</code>: confidence in hypothesis, on a scale of 1 to 10
- <code>effort</code>: the resources required to test a hypothesis, on a scale of 1 to 10 (the higher the <code>effort</code> value , the more resource-intensive the test)

The <code>orders_us.csv</code> table will be used for the second part of the project.

- <code>transactionId</code>: order identifier
- <code>visitorId</code>: identifier of the user who placed the order
- <code>date</code>: date of the order
- <code>revenue</code>: revenue made from the order
- <code>group</code>: the A/B test group that the user belongs to

The <code>visits_us.csv</code> table will be used for the second part of the project.

- <code>date</code>: date of visit
- <code>group</code>: A/B test group
- <code>visits</code>: the number of visits on the date specified in the A/B test group specified
