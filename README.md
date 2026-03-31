# DS3000

DS3000 Group Project

Create the data folder structured below:

```
data/
    raw/
    processed/
```

This must be set up on your own machine as data is sensitive and cannot be pushed to github, hence the gitignore for data files.

Files to put into `raw/`:

```
DemoStats_(DST)_2025_2025_GEO.csv
HouseholdSpend_(HHS)_2025_GEO_P1.csv
HouseholdSpend_(HHS)_2025_GEO_P2.csv
```

After running `data_prep.ipynb`, `tableau.pkl` will be created in `processed/`.

## Useful Info

y = HBR (If the households in a specific neighborhood (a PRCDDA) have an average disposable income of $100,000, and they spend $30,000 of that on rent or mortgages, their Housing Burden Ratio would be 0.30 (or 30%).)

GEO column:

| Geography                                        | Geo Abr. |
| ------------------------------------------------ | -------- |
| National                                         | CAN      |
| Provinces / Territories                          | PR       |
| Census Divisions                                 | PRCD     |
| Census Subdivisions                              | PRCDCSD  |
| Census Metropolitan / Census Agglomeration Areas | CMACA    |
| Census Tracts                                    | CMACT    |
| Aggregate Dissemination Area                     | PRCDADA  |
| Dissemination Areas                              | PRCDDA   |
| Federal Electoral Districts                      | PRFED13  |
| Forward Sortation Areas (TomTom Q4 2022)         | FSAQ422  |
| FSALDU - Residential only                        | FSALDU   |

CODE column is basically the specific location within GEO like
