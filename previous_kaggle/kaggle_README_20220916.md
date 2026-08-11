### Context

On UN SDGs (focus:EU27) I [posted on 2019-12-30 a dataset containing indicators from Eurostat](https://www.kaggle.com/robertolofaro/sdgeu-datamart-sample), but then on 2020-04-24 (lockdown), decided to expand the dataset by searching within the Worldbank huge collection of indicators those that could be useful in my interim publications focusing on the same themes.

Hence, selected 33 indicators (actually 34, but one is across- the GINI index estimate), and created a dataset containing those indicators, adding a sample notebook focused on EU27 to show the content.

Eventually, both the WorldBank and Eurostat data (routinely updated by their sources) will be integrated within the digital side (that I will share online to allow others to develop their own analyses) of the book that I have been keeping on the back burner since 2015 (see below).

UPDATE 2020-11-26: added to the series of datasets supporting my ongoing publications on sustainable digital transformation also another dataset: [EU 27 Energy sources - consumption 1990-2018 - *energy production, import, export by source - consumption by sector*](https://www.kaggle.com/robertolofaro/eu-27-energy-sources-consumption-19902018)

UPDATE 2022-11-17: extended the series to 2021, with data extracted 2022-09-16

### Content

Shared the "raw" data as downloaded from the World Bank webite, with the following limited preparation steps:

1. extracted the "dimensions", i.e. the Country and Indicator codes and descriptions
2. unified the 34 CSVs (34 indicators, see below) in a single CSV, smaller after leaving just the codes for the "dimensions" and the actual values
3. selected as period of reference 2000-2021, to focus on the XXI century (albeit 2000 data might actually refer to 1999 or earlier information).

**Selection rationale**

The criteria for selection of those 33 indicators was:

1. should be foreseen a routine update by the source (in this case, yearly), if needed
2. are considered non-partisan (i.e. do not represent a specific agenda, and therefor could be more acceptable as components to indicators to both political activists and business advocates)
3. each indicator should be provided by a "domain expert source" and then collated by an acknowledged "super-partes" (again, to improve credibility and perception as non-biased)
4. last but not least: each indicator should be useful, alone or with others, to help set an agenda for action (e.g. used the indicators on access to Internet, workforce inclusion, urbanization, etc)

**Release date and timeframe coverage**

The updated collated dataset was released on 2022-11-17, and contains data from 1999 until 2021

**"Raw" WorldBank indicators list**

The "keycode" (e.g. TX.VAL.TECH.MF.ZS) can be used [on WorldBank search index](https://datacatalog.worldbank.org/search/indicators) to both see the metadata, the timeframe available, preview, and select other export options

In order to enable to check on the metadata if the information might be of interested to you, this is the list of the indicators:
| index | key  | description |
| --- | --- | --- |
| 0 | CM.MKT.LCAP.GD.ZS | Market capitalization of listed domestic companies (% of GDP) |
| 1 | EG.IMP.CONS.ZS | Energy imports, net (% of energy use) |
| 2 | EG.USE.ELEC.KH.PC | Electric power consumption (kWh per capita) |
| 3 | EN.URB.LCTY.UR.ZS | Population in the largest city (% of urban population) |
| 4 | FP.CPI.TOTL.ZG | Inflation, consumer prices (annual %) |
| 5 | FR.INR.LNDP | Interest rate spread (lending rate minus deposit rate, %) |
| 6 | FS.AST.PRVT.GD.ZS | Domestic credit to private sector (% of GDP) |
| 7 | GB.XPD.RSDV.GD.ZS | Research and development expenditure (% of GDP) |
| 8 | GC.NLD.TOTL.GD.ZS | Net lending (+) / net borrowing (-) (% of GDP) |
| 9 | GC.TAX.TOTL.GD.ZS | Tax revenue (% of GDP) |
| 10 | GC.XPN.TOTL.GD.ZS | Expense (% of GDP) |
| 11 | IC.BUS.DISC.XQ | Business extent of disclosure index (0=less disclosure to 10=more disclosure) |
| 12 | IC.CRD.INFO.XQ | Depth of credit information index (0=low to 8=high) |
| 13 | IC.GOV.DURS.ZS | Time spent dealing with the requirements of government regulations (% of senior management time) |
| 14 | IC.LGL.CRED.XQ | Strength of legal rights index (0=weak to 12=strong) |
| 15 | IC.REG.DURS.FE | Time required to start a business, female (days) |
| 16 | IC.REG.DURS.MA | Time required to start a business, male (days) |
| 17 | IC.TAX.TOTL.CP.ZS | Total tax and contribution rate (% of profit) |
| 18 | IT.CEL.SETS.P2 | Mobile cellular subscriptions (per 100 people) |
| 19 | IT.MLT.MAIN.P2 | Fixed telephone subscriptions (per 100 people) |
| 20 | IT.NET.BBND.P2 | Fixed broadband subscriptions (per 100 people) |
| 21 | LP.LPI.OVRL.XQ | Logistics performance index: Overall (1=low to 5=high) |
| 22 | MS.MIL.XPND.GD.ZS | Military expenditure (% of GDP) |
| 23 | NY.GDP.MKTP.KD.ZG | GDP growth (annual %) |
| 24 | SE.PRM.TCAQ.ZS | Trained teachers in primary education (% of total teachers) |
| 25 | SE.XPD.TOTL.GD.ZS | Government expenditure on education, total (% of GDP) |
| 26 | SI.POV.GINI | GINI index (World Bank estimate) |
| 27 | SI.POV.URHC | Urban poverty headcount ratio at national poverty lines (% of urban population) |
| 28 | SL.TLF.CACT.FE.ZS | Labor force participation rate, female (% of female population ages 15+) (modeled ILO estimate) |
| 29 | SL.TLF.CACT.MA.ZS | Labor force participation rate, male (% of male population ages 15+) (modeled ILO estimate) |
| 30 | SL.UEM.TOTL.FE.ZS | Unemployment, female (% of female labor force) (modeled ILO estimate) |
| 31 | SL.UEM.TOTL.MA.ZS | Unemployment, male (% of male labor force) (modeled ILO estimate) |
| 32 | SP.URB.TOTL.IN.ZS | Urban population (% of total population) |
| 33 | TX.VAL.TECH.MF.ZS | High-technology exports (% of manufactured exports) |

for further information on each indicator, please refer to the source (World Bank)

**Potential uses**

*Example*: as part of the [CDP Unlocking Climate Solutions](https://www.kaggle.com/c/cdp-unlocking-climate-solutions) analytics challenge, I [discussed a potential use of these indicators](https://www.kaggle.com/c/cdp-unlocking-climate-solutions/discussion/190884#1063807) to cover both business and social impact issues, as it is part of something that I started writing on in 2015 ([a book-in-progress that actually is more an ongoing research released via articles on business and social change on my website](http://robertolofaro.com/index.php?section=expo2015diaries))

In that specific case (I haven't yet decided if I will have time to send in a proposal for the KPIs and associated methodology by early December 2020- I already had to skip the visualization part due early November 2020, that would have blended business and social impacts, as usual), my proposal was to use the above mentioned indicators contained within the "fact table" as follows:

*(the list of numbers is the indicator as per the list above, but it is just a sample- compounding and aggregation through a specific analysis model could actually use more or make irrelevant others)*

How do you help cities adapt to a rapidly changing climate amidst a global pandemic, but do it in a way that is socially equitable? *3,4,5,6,8,15,16,18,24,25,26,27,28,29,30,31,32*

What are the projects that can be invested in that will help pull cities out of a recession, mitigate climate issues, but not perpetuate racial/social inequities? *same as above, but focusing on "delta" (i.e. change impact, trend, acceleration/deceleration of change)*

What are the practical and actionable points where city and corporate ambition join, i.e. where do cities have problems that corporations affected by those problems could solve, and vice versa? *1,2,7,11,13,14,21,23,33*

How can we measure the intersection between environmental risks and social equity, as a contributor to resiliency? *integrate the above with the data from the "reference" dataset within the context*

### Acknowledgements

Thanks to the World Bank for publishing the extensive Open Data

### Inspiration

Connecting different data points to identify potential correlations, as part of my knowledge update/learning process (and to complement my other publication activities).

As [part of a long-term publishing project (started in 2015 at Expo2015 in Milan)](http://robertolofaro.com/index.php?section=expo2015diaries), routinely share data that collect along my writing journey- generally via articles on [my website on business and social change](https://robertolofaro.com).

