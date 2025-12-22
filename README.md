# FP&A Project
## Project Overview

This project simulates an FP&A reporting and planning environment for a mid-sized B2B operating company. The objective is to explain performance drivers, prioritise material variances, and translate historical performance into forward-looking planning assumptions, rather than performing detailed forensic attribution.

The [dashboard](https://github.com/ezrandc/FP-A-Project/tree/3b27955b08b349c0c7fba7032c1774be6ca40db9/Dashboard/Pages) is structured to mirror how FP&A supports management discussions: starting from high-level performance, isolating execution versus macro effects, assessing margin and cost structure, and informing forecast logic.

## Dataset & Scope

The [dataset](https://github.com/ezrandc/FP-A-Project/tree/be7e3ec2af2f1b63f4f253a264a4c485d6743ffe/Dataset) is artificially generated to resemble a realistic FP&A model for a B2B business selling furniture, office supplies, and corporate technology.
It includes monthly actuals and budgets for revenue, gross profit, operating expenses, and supporting dimensions (product category, time).

The focus is on directional analysis and prioritisation, not operational root-cause diagnosis.

## Key Assumptions & Limitations

- Industry demand is represented as an indexed benchmark for comparative analysis rather than a specific external source.
- Variance analysis is performed at an aggregate level to demonstrate analytical judgment and decision framing.
- Structural vs temporary classifications are judgement-based, intended to guide management focus rather than provide definitive attribution.
- Forecast scenarios are directional, designed to illustrate methodology rather than point-estimate precision.

## Dashboard Walkthrough

### Page 1 - Executive Summary

**Business Question: How is the business performing versus plan, and where should management focus next?**

<img
  src="https://raw.githubusercontent.com/ezrandc/FP-A-Project/e33ed2ba5df190eb81aeba0d76e2b467b0346e1e/Dashboard/Pages/Page%201%20-%20Executive%20Summary.png"
  width="900">

This page provides a consolidated LTM view of performance across revenue, gross profit, and EBITDA, supported by variance decomposition to isolate key drivers.

Analysis:

- *LTM revenue of $13.0M is +3.7% vs budget and +3.5% YoY, indicating modest outperformance.*
  - A modest favourable variance suggests that revenue assumptions were broadly well calibrated, rather than indicating a material demand surprise or planning error.
- *Variance magnitude remains small, suggesting forecast accuracy rather than a planning miss.*
  - The objective of FP&A is not to maximise favourable outcomes, but to reduce unexplained deviation over time.
- *Revenue outperformance is price-led (+2.8%), with limited volume contribution (+0.9%).*
  - Price contributing the majority of upside suggests execution discipline rather than cyclical or macro-driven demand uplift. Limited volume sensitivity implies that pricing actions held without materially impacting demand. In practice, this would prompt further monitoring of price sustainability and elasticity rather than aggressive volume re-forecasting
- *With revenue and gross profit tracking plan, EBITDA pressure is driven by cost structure and operational execution.*
  - This reframes management focus away from revenue growth and toward cost control, operating leverage, and structural efficiency - areas where incremental improvement would flow most directly to profitability.

### Page 2 - Performance Against Market

**Business Questions: Is growth driven by internal execution or external market conditions?**

<img
  src="https://raw.githubusercontent.com/ezrandc/FP-A-Project/e33ed2ba5df190eb81aeba0d76e2b467b0346e1e/Dashboard/Pages/Page%202%20-%20Performance%20vs%20Market.png"
  width="900">

This page benchmarks company revenue against indexed industry demand to distinguish execution-led performance from macro effects, and analyses quarterly growth patterns.

Analysis:

- *Company revenue growth outpaced flat industry demand, indicating execution-led performance rather than macro tailwinds.*
  - This increases confidence in the sustainability of performance, as it is less dependent on favourable macro conditions.
- *Outperformance reflects market share gains and pricing discipline, not cyclical uplift.*
  - When company growth exceeds industry demand, the implied drivers are share capture, pricing execution, or mix optimisation. In a live FP&A setting, this would warrant closer monitoring of competitive positioning and pricing effectiveness rather than reliance on market growth assumptions.
- *Quarterly YoY trends show consistent seasonality, with Q2 and Q4 structurally outperforming while Q1 remains weaker.*
  - The recurrence of this pattern across periods suggests seasonality is embedded in the business model rather than driven by one-off events. As a result, quarter-on-quarter comparisons are more informative than full-year averages when assessing performance.
- *Growth timing appears predictable rather than one-off and should be explicitly reflected in forecasts.*
  - Predictable seasonality reduces forecast uncertainty and argues against smoothing growth assumptions across the year. Instead, forecasts should preserve intra-year volatility to avoid overstating performance in structurally weaker periods.
- *Execution-led outperformance suggests scope for selective price increases without material volume risk.*
  - Sustained growth in excess of market demand implies that pricing actions have not significantly constrained volume to date. While this does not justify aggressive repricing, it supports cautious, targeted pricing initiatives subject to elasticity monitoring.

### Page 3 - Revenue Conversion

**Business Question: Is revenue converting into profit in line with assumptions, and where is margin pressure coming from?**

<img
  src="https://raw.githubusercontent.com/ezrandc/FP-A-Project/e33ed2ba5df190eb81aeba0d76e2b467b0346e1e/Dashboard/Pages/Page%203%20-%20Converting%20Revenue.png"
  width="900">

This page analyses how revenue translates into gross profit, isolating pricing effects, cost inflation, and mix dynamics.

Analysis:

- *Gross margin has remained broadly stable and close to plan, indicating that pricing assumptions were directionally correct.*
  - Margin stability suggests that pricing actions were sufficient to offset cost pressures, at least in aggregate. This reduces the likelihood that margin performance is being distorted by mix shifts or short-term volatility, and supports confidence in the underlying pricing framework.
- *Gross profit outperformance (+5.7% vs budget) is driven mainly by price uplift, partially offset by cost inflation, rather than mix changes.*
  - A price-led variance with limited mix impact implies that upside was achieved through execution rather than favourable product or customer mix. This distinction matters because price-driven gains are generally more controllable than mix-driven effects, but also require validation of sustainability.
- *Indexed COGS has increased faster than inflation benchmarks, suggesting that cost pressure is not purely macro-driven and may reflect internal or supplier-specific dynamics.*
  - Cost growth exceeding inflation indicates that margin pressure is unlikely to resolve without intervention. In a live environment, this would prompt further analysis at the supplier or category level to distinguish renegotiation opportunities from structural cost increases.
- *With margins protected through pricing and limited volume sensitivity observed, incremental cost savings would flow directly to profitability.*
  - The ability to absorb cost inflation without material volume loss suggests potential pricing inelasticity, indicating meaningful operating leverage on the cost base. If costs were reduced, a disproportionate share of the savings would translate into incremental profit. This hypothesis however, would require further validation through elasticity and customer-level analysis.

### Page 4 - Profitability

**Business Question: Where does actual profitability diverge most from plan, and is it controllable?**

<img
  src="https://raw.githubusercontent.com/ezrandc/FP-A-Project/e33ed2ba5df190eb81aeba0d76e2b467b0346e1e/Dashboard/Pages/Page%204%20-%20Profitability.png"
  width="900">

This page bridges gross profit to EBITDA, highlighting operating expense behaviour and cost sensitivity.

Analysis:

asdasd

### Page 5 - Revenue Analysis & Forecast

**Business Question: What does historical performance imply about forecast reliability, and how should assumptions evolve?**

<img
  src="https://raw.githubusercontent.com/ezrandc/FP-A-Project/e33ed2ba5df190eb81aeba0d76e2b467b0346e1e/Dashboard/Pages/Page%205%20-%20Revenue%20Analysis%20%26%20Forecast.png"
  width="900">

This page analyses historical growth patterns and translates them into scenario-based forecast assumptions.

Analysis:

sdfdsf

