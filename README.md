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

asdads

### Page 3 - Revenue Conversion

**Business Question: Is revenue converting into profit in line with assumptions, and where is margin pressure coming from?**

<img
  src="https://raw.githubusercontent.com/ezrandc/FP-A-Project/e33ed2ba5df190eb81aeba0d76e2b467b0346e1e/Dashboard/Pages/Page%203%20-%20Converting%20Revenue.png"
  width="900">

This page analyses how revenue translates into gross profit, isolating pricing effects, cost inflation, and mix dynamics.

Analysis:

asdasd

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

