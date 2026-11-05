# The Infrastructure Dividend: Geography, Equity, and the Partisan Myth
### An Empirical Analysis of the $1.2 Trillion Infrastructure Investment and Jobs Act (IIJA)

**Live Report:** [View the Interactive Data Story](./index.html)

## Overview
This project investigates the geographic and political distribution of federal funding under the Infrastructure Investment and Jobs Act (IIJA) through March 2023. By merging official federal agency allocations with 2020 Decennial Census population data and 2020 presidential election results across all 50 states and Washington, D.C., this study evaluates whether outlays reflect executive partisan bias or statutory formula mechanics.

## Key Findings
- **Macro Scale vs. Population Parity:** Gross dollar totals correlate strongly with raw state population (r = 0.97), with California ($18.4B), Texas ($14.2B), and New York ($10.1B) receiving the largest gross shares.
- **The Per-Capita Inversion:** Normalizing by population flips the distribution completely. Small rural states capture outsized funding per resident—led by Alaska ($5,045/person), Wyoming ($3,987), and Montana ($3,044)—compared to the national average baseline of $578.
- **Refutation of Partisan Favoritism:** States carried by Donald Trump in 2020 captured an average of $627 per resident versus $542 for Biden-carried states (a 16% advantage for Republican states). Contested battleground states received the lowest average cohort funding at $476 per capita.
- **Root Driver:** Allocation disparity is governed by statutory formula designs (equal state minimums, land area weights, and highway lane mileage), not political steering (r = -0.61 between population and per-capita spending).

## Repository Structure
```
├── index.html     # Self-contained visual report with interactive maps & charts
└── README.md      # Project overview, methodology, and key takeaways
```

## Data Sources & Scope
- **IIJA Allocations:** Official state-by-state funding records through March 2023.
- **Demographics:** 2020 U.S. Decennial Census state population counts.
- **Electoral Results:** 2020 U.S. Presidential Election certified voting margins.
- **Coverage Boundaries:** Focuses on formula allocations across the 50 states and Washington, D.C. Excludes discretionary competitive agency grants, U.S. territories, and tribal communities from partisan comparative models due to Electoral College status.
