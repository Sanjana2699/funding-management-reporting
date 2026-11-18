# Stakeholder Brief: Annual Startup Funding Reporting

## Who
Head of Research at a company data platform that tracks startups and funding.

## Problem
The research team has no clear yearly view of how many companies received
their first funding, how much funding those companies raised in total, and
which sectors and countries are growing. Reports are built manually, and
figures are hard to compare from one year to the next.

## What they need
1. A yearly dashboard showing companies funded, total funding and
   sector and country growth.
2. A one-page report for leadership summarising what changed and what it
   means.

## Success looks like
- The Head of Research can answer "what changed this year compared with
  last year?" in under 5 minutes.
- Numbers match the underlying data and every definition is written down.

## Out of scope
- Forecasting
- Individual company profiles
- Investor analysis (the dataset has no investor information)
- Live data refresh

## Data source
Crunchbase startup investments dataset (Kaggle, file: investments_VC.csv).
- One row per company, about 49,000 companies after removing blank rows.
- Covers companies with first funding up to the end of 2014.

## Known limitations
- "Funding by year" means the total funding of companies whose first
  funding happened in that year. It does not mean money raised in that year.
- About 17% of companies have no funding amount recorded.
- Some dates and fields are missing or inconsistent; cleaning decisions
  are documented in the data dictionary.
