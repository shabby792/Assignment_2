The dataset contains 97 rows and 6 columns.

The columns include:

- date
- item
- city
- price
- unit
- data_label

Problems Identified

The dataset requires inspection for the following issues:

1. Missing price values.
2. Duplicate records.
3. Inconsistent item naming.
4. Prices containing commas.
5. Unusually high price observations.

 Planned Cleaning Decisions

| Problem | Planned Decision |
|---|---|
| Missing prices | Keep missing and investigate |
| Duplicate records | Remove exact duplicates |
| Inconsistent names | Standardize item names |
| Comma-formatted prices | Convert into numeric values |
| Unusually high prices | Flag for verification |

 Initial Approach

I planned to use Python and Pandas to inspect the dataset, identify data quality problems, and compare the data before and after cleaning.

The original dataset would remain unchanged.

Snapshot code

9e42542
 
