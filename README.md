# New York State Homeownership Rate Analysis

## Overview

An exploratory time-series analysis of annual homeownership rates in New York State from 1984 through 2018. The project examines the long-term pattern and compares the observed peak with rates during the 2006–2012 period surrounding the 2008 housing crisis.

## Research questions

- How did New York State's homeownership rate change between 1984 and 2018?
- Which year or years recorded the highest rate in this dataset?
- How did rates during 2006–2012 compare with the observed peak?

## Data

- **Source:** `census/homeownership-rate-time-series-collection`, downloaded with KaggleHub
- **File analyzed:** `NYHOWN.csv`
- **Coverage:** Annual observations, 1984–2018
- **Observations:** 35

## Methods

1. Load and inspect the dataset with pandas.
2. Standardize column names and check for missing values and duplicate records.
3. Convert date fields to datetime values and organize observations chronologically.
4. Calculate descriptive statistics and examine annual changes.
5. Use Matplotlib to visualize the series and compare the peak with values in the selected 2006–2012 period.

## Findings from the notebook

The highest observed rate is **55.9%**, recorded in 2005 and 2007. Within the selected 2006–2012 comparison window, the lowest observed rate is **53.6%**, recorded in 2011 and 2012. The difference between those values is 2.3 percentage points.

This is a descriptive comparison. It does not establish that the financial crisis caused the observed changes.

## Tools

- Python
- pandas
- Matplotlib
- Jupyter Notebook
- KaggleHub

## Limitations and reproducibility

This project analyzes one state-level series and a relatively small number of annual observations. The comparison is exploratory, not a causal analysis. The notebook uses a locally downloaded dataset; the file path should resolve to the KaggleHub download directory when the notebook is run on another machine.

