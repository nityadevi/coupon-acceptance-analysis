# Practical Application 1 — Coupon Acceptance Analysis

This repository contains an exploratory analysis of the **In-Vehicle Coupon Recommendation** dataset (UCI).  
The goal is to understand what characteristics are associated with **coupon acceptance**.

## Contents
- `Practical_Application_1_Unique.ipynb` — analysis notebook
- `data/coupons.csv` — dataset (provided in starter)
- `images/` — starter images (and any plots you choose to export)

## Summary of Findings
- The dataset has a few columns with missing values; `car` is almost entirely missing and is dropped.
- Overall coupon acceptance rate is computed as a baseline.
- **Bar coupons**: acceptance is much higher for people who already go to bars more than once per month, and highest for segments that reflect an adult social context (e.g., no kid passengers, not widowed).
- **Coffee House coupons**: acceptance increases with higher coffee-house visit frequency and varies by time of day.

## Recommendations
- Target Bar coupons primarily to frequent bar-goers and relevant contexts.
- Avoid spending Bar coupons on non-bar-goers and shift effort to higher-performing coupon types.
- For Coffee House coupons, emphasize timing (morning/afternoon) and frequent visitors.

## How to run
Open the notebook and run all cells from top to bottom:

```bash
pip install pandas numpy matplotlib seaborn
```

