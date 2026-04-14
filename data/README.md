# Data

`asia_fertility_data.xlsx` is the consolidated 
dataset used to build the dashboard.

## What's in it

88 rows — 8 countries × 11 years (2000–2010)

| Column | Description | Source |
|---|---|---|
| Country | Country name | — |
| Country_Code | ISO 3-letter code | — |
| Year | 2000–2010 | — |
| Fertility_Rate | Births per woman | World Bank |
| Obesity_Rate | % adults with BMI ≥ 30 | WHO |
| MMR | Maternal deaths per 100,000 live births | World Bank |
| GDP_per_Capita | Current USD, not PPP-adjusted | World Bank |
| HDI | 0–1 scale | UNDP |
| Population | Total population | Our World in Data |

## Notes

Raw data was downloaded from four source databases and 
manually consolidated into this flat table. Wide-format 
World Bank files were unpivoted using Power Query before 
merging.

Bhutan has no official HDI values before 2005 — those 
cells are intentionally blank.

GDP figures are current USD. Cross-country comparisons 
should account for purchasing power differences.

## Sources

- [World Bank Open Data](https://data.worldbank.org)
- [WHO Global Health Observatory](https://www.who.int/data/gho)
- [UNDP Human Development Reports](https://hdr.undp.org/data-center)
- [Our World in Data](https://ourworldindata.org)
