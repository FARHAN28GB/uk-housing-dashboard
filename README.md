# UK Housing Market Dashboard 2015–2026

Interactive dashboard of UK house prices from January 2015 to August 2026, built from official data.

**Open the dashboard:** https://farhan28gb.github.io/uk-housing-dashboard/

**Data workbook:** [UK_Housing_Market_Data_2015-2026.xlsx](UK_Housing_Market_Data_2015-2026.xlsx)

## Quick guide

- **Area / Compare with:** pick the UK, a nation or region, and an optional second area to chart against it.
- **From / To:** choose any month and year from Jan 2015 to Aug 2026. Every chart, table and figure updates.
- **Quick periods:** one-click presets such as Last 12 months, Pre-Covid → latest, Jan 2020 → Dec 2024. Reset restores defaults.
- **Property type:** all, detached, semi-detached, terraced, flats.
- **Prices: Cash / Adjusted for inflation:** one toggle restates every price and growth figure on every tab in pounds of your To month (ONS CPIH or CPI), so changes become real changes. Price-band counts and mortgage rates are not adjusted.
- **ⓘ icons:** hover or tap any ⓘ next to a figure or chart title for a plain-English explanation.
- **Hover or tap** charts for exact values. Orange dots under the trend chart are market events.

### Tabs
- **Price trend:** start/end prices, £ and % change, annualised growth, property types, buyer types, purchase-value calculator.
- **Regions and nations:** sortable regional comparison; click a row to select it.
- **Price bands:** share of sales from under £200k to £2m+ by year (England and Wales; shows sales mix, not value growth).
- **Mortgages and rates:** Bank Rate, fixed and variable rates, approvals, repayment comparison.
- **Local areas:** all 387 counties, districts, boroughs and councils; search, sort, click to chart.
- **Inflation detail:** cash vs real price chart, real change by region and property type, real mortgage cost.
- **Sources and method:** data sources and the events timeline.

### Excel workbook
- **Comparison:** change the yellow cells (area, months as YYYY-MM); results update by formula.
- **Real_Terms:** inflation-adjusted prices. Pick area, CPIH or CPI, base month and period for real change, real peak, property types, regions and real mortgage cost.
- **Regions, Annual_Averages, Band_Shares:** summaries built on the raw data tabs. See the Read Me tab.

## Data notes
- Sources: HM Land Registry UK House Price Index (released 21 Oct 2026) and Price Paid Data; Bank of England mortgage rates. News sources used for event context only.
- Prices are cash (nominal) by default. Switch on Adjusted for inflation in the dashboard, or use the workbook's Real_Terms sheet, for real-terms figures.
- Latest months are provisional; sales counts after June 2026 are incomplete.
- Northern Ireland figures are quarterly.
- Blank or "Not published" means the series is not published for that area or month.
- Annualised growth shows only for periods of 12 months or more.
- The purchase calculator is an index estimate, not a valuation.

Contains HM Land Registry data © Crown copyright and database right 2026, licensed under the Open Government Licence v3.0. Contains Bank of England data. Contains ONS data (CPI, CPIH) © Crown copyright, Open Government Licence v3.0.
