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

### Page 1 — Executive Summary

**Business Question: How is the business performing versus plan, and where should management focus next?**



This page provides a consolidated LTM view of performance across revenue, gross profit, and EBITDA, supported by variance decomposition to isolate key drivers.

Key Takeaways (LTM):

- LTM revenue of $13.0M outperformed budget (+3.7%) and prior year (+3.5%), indicating modest upside rather than a planning miss.
- Revenue variance is primarily price-led, with limited volume contribution, pointing to execution discipline rather than demand surprise.
- With revenue and gross profit largely tracking plan, EBITDA pressure is driven by cost structure and operational execution, not top-line underperformance.
