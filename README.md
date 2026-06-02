# Olist E-Commerce Logistics Performance & Delivery Efficiency Audit

This repository contains production-ready SQL queries used to audit and evaluate the logistics performance of Olist E-Commerce (2017–2018).

## Analytics Workflow & Documentation
The data extraction, handling, and analysis were fully performed using MySQL. The core objectives focus on identifying critical route failures, analyzing lead time breakdowns, and mapping geographic bottlenecks.

### Key Queries Included in `queries.sql`:
1. **Delivery Delay Evaluation & SLA Compliance Rate:** Analyzes the baseline Service Level Agreement (SLA) success metrics.
2. **Fulfillment Lifecycle & Lead Time Breakdown:** Breaks down the end-to-end supply chain transit duration.
3. **Macro-Corridor Matrix:** State-to-state performance and cross-regional risk mapping.
4. **Micro-Geographic Deep Dive:** Localized city-level bottleneck identification (SP to RJ corridor).
5. **Customer Experience Correlation:** Core evaluation of how delivery delays directly affect customer review scores.

*Note: The calculated outputs of these queries have been fully integrated into the Power BI interactive portfolio dashboard.*
