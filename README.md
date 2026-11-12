# Paygrade salary data

Open salary and pay datasets from [Paygrade](https://www.paygradecareers.com/), a free site that shows what jobs really pay
in 12 countries using official statistics. Every figure comes from a named official source (BLS, ONS, Statistics Canada /
Job Bank, MOM, ABS and others) or from Paygrade's documented model, and each row says which.

Licence: [CC BY 4.0](LICENSE). Use it for anything, including commercial work and journalism, as long as you credit
**Paygrade (paygradecareers.com)** with a link.

The live, always up to date versions of these files are on the site: https://www.paygradecareers.com/data/
(this repository is a snapshot, refreshed from time to time).

## Files

### Salary pages (`data/`)
| File | What it holds |
| --- | --- |
| `paygrade-salary-data.csv` | Every salary page on paygradecareers.com: career, country, the entry, median and senior figures shown, whether they are official or modelled, and the source, source URL and release date |
| `us-pay-by-state.csv` | US median pay for each career in each state, from the BLS Occupational Employment and Wage Statistics (OEWS), with employment and hourly pay |
| `us-pay-by-metro.csv` | US pay for each career in each metro area (BLS OEWS): median, 10th and 90th percentiles, employment |
| `canada-pay-by-province.csv` | Canadian median hourly pay for each career by province (Job Bank wages), with the yearly figure at 2,080 hours |

### Studies (`data/studies/`)
Each file is the data behind a study page on the site, with its method and limits:
| File | Study |
| --- | --- |
| `pay-transparency-index.csv` | [Pay transparency index](https://www.paygradecareers.com/studies/pay-transparency-index/): share of US job ads with a pay range, by state and posting law |
| `ai-pay-premium.csv` | [Do AI jobs pay more?](https://www.paygradecareers.com/studies/ai-pay-premium/): pay in US job ads with AI in the title against the same employer's other roles |
| `entry-level-jobs.csv` | [Junior vs senior](https://www.paygradecareers.com/studies/entry-level-jobs/): how many US job ads are entry level, by function and sector |
| `take-home-by-country-2026.csv` | [How much of your salary you keep](https://www.paygradecareers.com/studies/take-home-pay-by-country/): take-home pay on the same salary in 12 countries, 2026 rates |
| `uk-graduate-pay-by-degree.csv` | [UK degree pay five years on](https://www.paygradecareers.com/studies/uk-graduate-pay-by-degree/): DfE LEO earnings by subject |
| `uk-pay-rises-2026.csv` | [Which UK jobs got the biggest pay rises](https://www.paygradecareers.com/studies/uk-pay-rises-by-job/): ONS ASHE 2026 by occupation |

Column meanings, sources and methods are explained on each page and at https://www.paygradecareers.com/methodology/.

## How to cite
Paygrade (2026). *Paygrade salary data*. https://www.paygradecareers.com/data/ (CC BY 4.0).

Please also credit the original statistics office named in each row's `source` column.

## Contact
hello@paygradecareers.com
