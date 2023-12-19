![Alt text](Assets/4..png)

# Tokenomics Documentation: Fair Pricing and Distribution Model

## Overview

CognideX's Tokenomics is designed to incentivize the fair monetization of data contributions while maintaining a balanced and reasonable marketplace. This document outlines the procedures for setting data prices, aggregating contributions, determining the final sale price, and distributing proceeds among contributors.

## Data Contribution and Preliminary Valuation

Contributors upload their datasets to the platform, setting their desired price tags based on personal valuation. An approved analyst then aggregates these datasets and performs a detailed analysis to suggest a bundled value for the insights derived from the collective data.

(Note: The examples are completely hypothetical. We need to replace all with real Tokenomics.)

## Establishing Price Reasonability

To ensure that the final price suggested by analysts remains within a reasonable range:

1. **Maximum Price Cap:** A cap is implemented based on:
   - Median contributor price.
   - Historical sales data.
   - Total number of contributions.

2. **Weighted Average Pricing:** 
   - A baseline price per unit of data (e.g., per MB) is calculated using a weighted average that considers dataset size and quality score.

## Community Voting for Final Price

A community-driven voting round is initiated to gather consensus on the final value of the aggregated dataset. Stakeholders cast votes that are weighted by their contribution size and quality scores. The final sale price is set by a weighted median of these votes.

## Proceeds Distribution Model

Upon the successful sale of the aggregated dataset, proceeds are allocated as follows:

1. **Contributor Earnings:** Contributors are remunerated based on their proportional share of the total data pool, adjusted by the weighted average price.

2. **Analyst Reward:** The analyst is compensated with a percentage of the total sale, capped to prevent any disproportionate allocation.

3. **Platform Sustainability:** A platform fee is deducted to support operational costs and the continuous improvement of the ecosystem.

## Example Case

With a total of 10,000MB contributed and an initial combined price tag of 1,000,000 Algos, the process unfolds as follows:

1. **Weighted Average Calculation:**
   - The weighted average is computed as 100 Algos/MB, setting the stage for a reasonable price range.

2. **Price Adjustment:**
   - The analyst's suggested price is adjusted to the reasonable range's upper limit if necessary.

3. **Community Consensus:**
   - Voting within the reasonable range leads to a final sale price that reflects the community's consensus.

4. **Final Distribution:**
   - The proceeds are distributed equitably among contributors and the analyst according to the established model.

## Governance and Future Adjustments

The tokenomics model is dynamic and governed by community consensus. Changes to the price cap, the weighted average mechanism, and the distribution formula can be proposed and voted upon by token holders, ensuring that the platform evolves with the needs of its users.

---

## Tokenomics Example with Markdown Formulas

### Data Listing

- **Alice** lists 20MB of Netflix data at `100 Algos`.
- **Bob** lists 3MB of Netflix data at `100,000 Algos` (outlier).
- **Carl** lists 200MB of Netflix data at `1 Algo`.
- **Dimitry** lists 10MB of Netflix data at `10 Algos`.
- (Assuming a total of `1004` contributors, contributing a total of `10,000MB`.)

### Analyst's Aggregated Valuation

- **Eve**, the data analyst, aggregates all data and proposes a valuation of `300,000 Algos` for the entire dataset.

### Reasonable Price Range Establishment

- A maximum price cap is determined at `150 Algos/MB` based on historical data and median pricing.
- The weighted average price per MB is calculated to be `100 Algos/MB`.

### Community Voting

- The community participates in voting on the final price of the dataset within the reasonable range.

### Final Price Determination

- The weighted median price after community voting is established at `90 Algos/MB`.

### Sale and Distribution of Proceeds

- The dataset is sold at the price of `90 Algos/MB`.
- Total Sale Amount: `10,000MB * 90 Algos/MB = 900,000 Algos`.

### Proceeds Distribution

- **Platform Fee**: `10%` of the total sale amount.
- **Net Proceeds for Distribution**: `90%` of the total sale amount.

### Contributors' Earnings Calculation

- Alice's share: `(20MB / 10,000MB) * 810,000 Algos = 1,620 Algos`.
- Carl's share: `(200MB / 10,000MB) * 810,000 Algos = 16,200 Algos`.
- Dimitry's share: `(10MB / 10,000MB) * 810,000 Algos = 810 Algos`.
- (Calculated proportionally for all other contributors.)

### Analyst Reward

- Eve's reward: `5%` of the total sale amount.
- Eve's reward calculation: `900,000 Algos * 5% = 45,000 Algos`.

### Governance and Adjustments

Contributors and token holders can vote on proposals to adjust the tokenomics model.

You can check the governance future proposal in [the following page](6-Governance.md) ⬅️


