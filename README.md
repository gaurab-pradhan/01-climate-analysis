# Climate Analysis — World Bank Data

Exploratory data analysis of global climate indicators using Python and pandas.

## Objective

Analyse CO2 emissions, temperature trends, and development indicators across countries
and regions from 1990 to 2011. Identify patterns by region and income group.

## Tools

Python · pandas · matplotlib · seaborn · Jupyter

## Data

Source: World Bank Climate Change Data  
Download: https://www.kaggle.com/datasets/theworldbank/world-bank-climate-change-data

Download the following files and place in `data/raw/`:

- `climate_indicators.xls` — CO2, GDP, population, land area indicators (1990–2011)
- `climate_historical.xls` — Monthly temperature and precipitation by country (1961–1999)

> Data is not committed to this repo due to file size.

## Key Questions

- How have CO2 emissions changed globally from 1990 to 2011?
- Which regions and income groups are the highest emitters?
- Is there a relationship between GDP and CO2 emissions?
- How do temperature patterns vary across countries?

## Project Structure

```
data/raw/          ← raw files, never committed
notebooks/         ← EDA notebooks
src/               ← Python modules
outputs/           ← charts and exports
```
