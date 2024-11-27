# Inferential-Statistics-Case-Study

Business Context
A leading pharmaceutical company has tested five batches of a vaccine, with 300,000 doses already administered. The sixth batch, consisting of 60,000 doses, requires quality assurance testing to determine its effectiveness and curing time.

Previous data indicates that each dose is twice as likely to be satisfactory as unsatisfactory. This analysis focuses on inferring the quality of the sixth batch, rather than conducting a clinical trial.

Objective
To analyze random samples from the sixth batch to infer its quality and curing time by performing probability calculations and descriptive statistical analysis.

Tasks
Task 1: Analyze 10 Randomly Selected Doses
Determine the probability distribution of unsatisfactory doses.

Given: Each dose is twice as likely to be satisfactory as unsatisfactory.
Use the Binomial Distribution.
Probability Calculations:

Exactly 3 out of 10 doses are unsatisfactory:
𝑃
(
𝑋
=
3
)
P(X=3)
At most 3 out of 10 doses are unsatisfactory:
𝑃
(
𝑋
≤
3
)
P(X≤3)
More than 8 out of 10 doses are satisfactory:
𝑃
(
𝑋
>
8
)
P(X>8) for satisfactory doses.
Task 2: Analyze 20 Doses Requested by NYC Administration
Probability Calculations:
At least 11 out of 20 doses are unsatisfactory:
𝑃
(
𝑋
≥
11
)
P(X≥11)
At most 5 out of 20 doses are unsatisfactory:
𝑃
(
𝑋
≤
5
)
P(X≤5)
At least 13 out of 20 doses are satisfactory:
𝑃
(
𝑋
≥
13
)
P(X≥13) for satisfactory doses.
Task 3: Analyze the Time of Effect for 50 Doses
Use the time of effect data to calculate probabilities:

Probability that the time of effect is less than 11.5 hours:
𝑃
(
𝑇
<
11.5
)
P(T<11.5)
Probability that the time of effect is more than 10 hours:
𝑃
(
𝑇
>
10
)
P(T>10)
Calculate the 90th Percentile of the Time of Effect:

Identify the value below which 90% of the data lies.
Dataset Description: doses.csv
The dataset includes the following features:

Drug Serial Number: Unique serial number for each dose.
