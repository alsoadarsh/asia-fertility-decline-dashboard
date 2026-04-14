# The Hidden Pressures Behind Asia's Fertility Decline

![Dashboard Preview](images/dashboard_preview.png)

**[View Live Dashboard →](https://public.tableau.com/app/profile/alsoadarsh/viz/AsiaFertilityDeclineDashboard/AsiaFertilityDecline)**

Fertility fell across all 8 countries. Obesity rose across 
all 8 countries. Same decade, opposite directions.

---

## Overview

Tracks demographic transitions across Afghanistan, 
Bangladesh, Bhutan, China, India, Nepal, Pakistan, and 
Sri Lanka from 2000 to 2010 across five indicators: 
fertility rate, obesity, maternal mortality, GDP per 
capita, and HDI.

**Tools:** Tableau Desktop 2025.1, Microsoft Excel, 
Power Query  
**Data:** World Bank · WHO Global Health Observatory · UNDP

---

## Data Preparation

Raw data was downloaded from four source databases in 
three different formats and manually consolidated into 
a single flat table — 88 rows, 8 countries × 11 years, 
9 columns. Wide-format World Bank files were unpivoted 
using Power Query. Calculated metrics like fertility 
decline were built in Tableau using FIXED LOD expressions 
rather than Excel to keep the source data clean.

One data gap worth noting: Bhutan has no official UNDP 
HDI values before 2005. Those cells are blank and Bhutan 
is excluded from HDI-specific charts with a note.

---

## Key Findings

- Nepal and Afghanistan led fertility decline at 
  −1.4 children/woman each over the decade
- China was the only country to reach replacement 
  level (2.1) by 2010 — but its drop was small because 
  it started the decade already at 1.8
- Sri Lanka's MMR is 35 per 100,000 vs Bangladesh at 194 
  and India at 212 — both with higher GDP per capita. 
  Income alone doesn't explain that gap
- Pakistan: fertility still above 3.8 in 2010, obesity 
  nearly doubled (2.9% → 5.7%). Transition stalled, 
  health burden growing simultaneously
- The HDI–fertility relationship is loose. You can't 
  predict a country's fertility trajectory from its 
  HDI alone — Sri Lanka is the clearest counterexample

---

## Dashboard Features

- 7 charts: dual bar, donut, dual-axis line, bar table, 
  waterfall, scatter, dot plot
- 5 dynamic KPI cards
- Preset filter modes: All Countries, On Target, 
  High MMR Burden, Fast Movers, Stalled Transition, 
  Compare Two
- Cross-filtering via country selector
- Highlight/Hide toggle and sort control

---

## Files

| File | Description |
|---|---|
| `data/asia_fertility_dashboard_data.xlsx` | Master dataset, 88 rows × 9 columns |
| `images/dashboard_preview.png` | Dashboard screenshot |

---

## Sources

- World Bank Open Data — fertility rate, GDP per capita, 
  maternal mortality ratio
- WHO Global Health Observatory — adult obesity prevalence
- UNDP Human Development Reports — HDI time series

---

## Author

**Adarsh Shukla**
MS Business Analytics · University of Dayton
[LinkedIn](https://linkedin.com/in/adarshhshukla) · [GitHub](https://github.com/alsoadarsh)
