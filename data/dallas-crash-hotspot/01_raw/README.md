# Raw Crash Data

The raw files used in this project were downloaded from the Texas Department of Transportation's [CRIS Query tool](https://cris.dot.state.tx.us/public/Query/). They contain crash-level records for the City of Dallas covering 2021–2025, with one CSV file for each year.

To reproduce the dataset, use CRIS Query to filter records by City of Dallas and the applicable calendar year, then export the following fields:

- `Crash ID`
- `City`
- `Contributing Factors`
- `Crash Date`
- `Crash Death Count`
- `Crash Possible Injury Count`
- `Crash Severity`
- `Crash Suspected Serious Injury Count`
- `Crash Time`
- `Crash Total Injury Count`
- `Highway Number`
- `Intersection Related`
- `Latitude`
- `Light Condition`
- `Longitude`
- `Manner of Collision`
- `Roadway Part`
- `Speed Limit`
- `Street Name`
- `Surface Condition`
- `Weather Condition`

Rename the annual exports as follows and place them in this directory:

```text
dallas-city-2021-cris.csv
dallas-city-2022-cris.csv
dallas-city-2023-cris.csv
dallas-city-2024-cris.csv
dallas-city-2025-cris.csv
```
