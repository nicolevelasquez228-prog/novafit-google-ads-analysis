# NovaFit Google Ads Campaign Performance Analysis

## Overview

This project analyses 30-day Google Search advertising performance for NovaFit using Python and Pandas. The analysis evaluates performance across three campaign types: Brand, Category and Competitor.

The objective is to identify differences in campaign efficiency and provide data-driven recommendations for improving search advertising performance.

## Business Question

How does performance differ across NovaFit's Brand, Category and Competitor search campaigns, and where should campaign performance be optimised?

## Dataset

The dataset contains Google Search performance data across NovaFit's campaigns, including:

- Campaign type
- Campaign
- Ad group
- Keyword
- Match type
- Impressions
- Clicks
- Cost
- Conversions
- Quality Score

## Tools

- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## Methodology

The analysis involved:

1. Inspecting the dataset structure and variables
2. Checking for missing values
3. Checking for duplicate observations
4. Cleaning and converting variables into appropriate data types
5. Calculating key performance metrics
6. Comparing performance across campaign types
7. Identifying key findings and strategic recommendations

The following performance metrics were calculated:

- **CTR (Click-Through Rate):** Clicks divided by impressions
- **CPC (Cost Per Click):** Cost divided by clicks
- **CPA (Cost Per Acquisition):** Cost divided by conversions
- **Conversion Rate:** Conversions divided by clicks

## Campaign Performance Analysis

### Brand

Brand was the strongest-performing campaign overall. It generated 396 conversions from 36,530 impressions and 3,858 clicks, while spending 3,700,915 COP.

It achieved the highest CTR (10.56%), lowest CPC (959.28 COP), lowest CPA (9,345.74 COP) and highest conversion rate (10.26%).

These results indicate that Brand searches generated highly engaged traffic and were the most efficient source of conversions in the dataset.

### Category

Category generated the greatest volume of traffic, with 144,730.59 impressions and 7,646 clicks. It also accounted for the largest amount of spend at 14,374,023 COP and generated 257 conversions.

However, its efficiency was considerably lower than Brand. Category achieved a 5.28% CTR, 1,879.94 COP CPC, 55,930.05 COP CPA and 3.36% conversion rate.

This suggests that Category provides valuable acquisition potential but requires optimisation to improve conversion efficiency.

### Competitor

Competitor was the weakest-performing campaign. It generated 27,475 impressions and 314 clicks while spending 992,595 COP, but produced zero conversions.

It had the lowest CTR at 1.14% and the highest CPC at 3,161.13 COP. CPA was not meaningful because the campaign generated no conversions.

## Key Findings

- **Brand was the most efficient campaign**, achieving the highest CTR (10.56%), highest conversion rate (10.26%) and lowest CPA (9,345.74 COP).
- **Category generated the greatest volume**, with 144,730.59 impressions, 7,646 clicks and 257 conversions, but had a substantially higher CPA of 55,930.05 COP.
- **Competitor generated no conversions** despite spending 992,595 COP, with the lowest CTR (1.14%) and highest CPC (3,161.13 COP).
- Brand currently provides the strongest campaign efficiency, while Category represents an opportunity for optimisation and Competitor requires careful budget consideration.

## Recommendations

### 1. Protect Brand performance

Continue to support Brand because it generates strong conversion volume at a substantially lower CPA.

### 2. Optimise Category performance

Review keyword, ad and landing-page performance to identify opportunities to improve conversion efficiency.

### 3. Review Competitor spend

Carefully evaluate continued investment in Competitor given its zero conversions and relatively high CPC.

### 4. Monitor campaign efficiency

Use CPA, conversion rate, CTR and CPC together when evaluating future campaign performance rather than relying on conversion volume alone.

## Repository Contents

- `novafit-google-ads-analysis.ipynb` — Google Colab notebook containing the data cleaning, analysis and findings.

## Conclusion

The analysis demonstrates that Brand currently provides the strongest search campaign efficiency, while Category offers significant traffic and conversion volume but requires optimisation. Competitor performance is currently weak and should be carefully reviewed before additional budget is allocated.
