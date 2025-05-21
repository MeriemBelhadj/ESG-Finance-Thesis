# Methodology

## Objective
To evaluate the impact of ESG performance on the financial performance of fossil fuel companies, particularly before and after the 2015 Paris Agreement, using a Difference-in-Differences (DiD) approach.

## Econometric Approach
The analysis is based on four linear regression models estimated using panel data from fossil fuel companies, comparing the periods before and after the 2015 Paris Agreement. A Difference-in-Differences (DiD) specification is used in some models to isolate the effect of the policy shift.

## Difference-in-Differences (DiD) Method
The DiD method is used to estimate the causal effect of a policy intervention by comparing the changes in outcomes over time between a treatment group (Paris Agreement–aligned firms) and a control group (non-aligned firms). In this thesis, DiD isolates the impact of the 2015 Paris Agreement on financial performance and ESG scores by interacting the post-2015 time period with a dummy variable indicating whether a firm is aligned with the agreement.

## Model Specifications
Model 1: ESG Score Determinants
## esg_score = α + β1 * ca + β2 * res_net_ai + β3 * res_ope + ε
This model explores how revenue, net income, and operating income relate to the ESG score of a firm.

Model 2: Revenue as a Function of ESG and Financial Indicators
## ca = α + β1 * esg_score + β2 * res_net_ai + β3 * res_ope + β4 * DiD + ε
This model tests whether ESG scores influence revenue, while controlling for profitability and the post-Paris Agreement period (DiD).

Model 3: Net Income Drivers
## res_net_ai = α + β1 * ca + β2 * res_ope + β3 * DiD + ε
This model assesses how revenue, operating income, and policy shift affect net income.

Model 4: Operating Income Determinants
 ## res_ope = α + β1 * res_net_ai + β2 * ca + β3 * DiD + ε
This model evaluates the relationship between residual operating income and the firm’s revenue, net income, and post-policy effect.

## Variable	Descriptions

esg_score: Environmental, Social, and Governance performance score of the firm (Refinitiv).

ca: Total revenue (chiffre d'affaires): a measure of firm size and performance.

res_net_ai: Residual net income after tax: net income adjusted for firm fixed effects.

res_ope: Residual operating income: operating income adjusted for firm fixed effects.

DiD: Difference-in-Differences variable:: equals 1 for Paris Agreement–aligned firms after 2015, 0 otherwise.
