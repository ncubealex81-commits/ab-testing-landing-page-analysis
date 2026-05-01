# A/B Testing: Landing Page Redesign Analysis

**View the full analysis:** [Open in NBViewer](https://nbviewer.org/github/ncubealex81/ab-testing-landing-page-analysis/blob/main/ab_testing_project.ipynb)

**Python 3.8+ | Pandas | SciPy | StatsModels | Matplotlib**


## The Problem

An e-commerce company redesigned their landing page but doesn't know if it actually improves sales. Launching an ineffective page wastes money. Failing to launch a better page leaves revenue on the table.

**The question:** Does the new landing page increase purchase conversions?


## The Answer

**Yes. The new page increases conversions by 51%.**

The control group (old page) had 146,926 users and converted at 11.87%. The treatment group (new page) had 147,552 users and converted at 17.95%. That is a lift of 6.08 percentage points, which represents a 51% relative improvement.

The p-value is less than 0.0001, meaning this result is statistically significant and not due to random chance. The 95% confidence interval ranges from 5.82% to 6.33% — entirely above zero — confirming the new page is definitely better.

**Recommendation:** Launch the new page immediately.

## Business Impact

For every 100 visitors, the new page generates 6 more purchases. For a site with 100,000 monthly visitors, that means 6,000 additional purchases per month. At 1 million monthly visitors, that jumps to 60,000 extra purchases.



## What I Did

I loaded and cleaned 294,478 user session records, calculated conversion rates for both groups, ran a two-proportion z-test to determine statistical significance, calculated 95% confidence intervals, and performed segment analysis by device type.

The new page outperformed the old page across every device type — mobile, desktop, and tablet — with no segment performing worse.


## How to Run This Code

Clone the repository:
