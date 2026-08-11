# selected indicators from World Bank

Dimension data tables created 2026-08, based upon those previously created in 2020-04 and updated 2026-09, aligned to data as downloaded 2026-08-01

# reference

World Bank website https://datacatalog.worldbank.org/search/dataset/0037712/world-development-indicators 
data extracted on 2026-08-01

## subset extracted:

selected KPIs 1960-2025

# contents

This repository contains supporting tables for a sample dashboard created in 2020-04, data updated 2026-08-01

The choice has been to have a single unified facttable, directly selected as a subset of the export from the World Bank dataset.

This repository contains "dimension tables", i.e. descriptions and additional information to complement the datapoints within the datamart:
1. dimension_country.csv: country identification and metadata
2. dimension_indicator.csv: selected indicators identification and metadata
3- dimension_time: years 1960-2025
3. dimension_indicator_xrefprevious.csv: some indicators have been removed from the source dataset (see next section).

To ease re-use by AIs, the table have been extended with all the metadata available

# indicators discountined in 2021

The following indicators were part of the project [Doing Business project](http://www.doingbusiness.org/), that has been discountined in 2021.

The Press release announcing termination of the project "Doing Business" [is available here](https://www.worldbank.org/en/news/statement/2021/09/16/world-bank-group-to-discontinue-doing-business-report)

The Press release includes a link to the report disclosing data anomalies in 2018 and 2021 within the indicators.

The previous version of this dataset included the following indicators now discontinued

| Indicator Code | Indicator Name and description |
| --- | --- |
| IC.BUS.DISC.XQ | Business extent of disclosure index (0=less disclosure to 10=more disclosure) |
| IC.CRD.INFO.XQ | Depth of credit information index (0=low to 8=high) |
| IC.LGL.CRED.XQ | Strength of legal rights index (0=weak to 12=strong) |
| IC.REG.DURS.FE | Time required to start a business, female (days) |
| IC.REG.DURS.MA | Time required to start a business, male (days) |
| IC.TAX.TOTL.CP.ZS | Total tax and contribution rate (% of profit) |

# license

The content of this repository is released CC-BY-SA-4.0

The [associated Kaggle dataset](https://www.kaggle.com/datasets/robertolofaro/selected-indicators-from-world-bank-20002019) is a fact table

