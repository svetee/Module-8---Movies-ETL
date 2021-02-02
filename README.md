# Module 8 Challenge Movies-ETL

## Objectives

- Create an automated ETL pipeline.

- Extract data from multiple sources.

- Data cleaning and trabsformation -  using Pandas and regular expressions.

- Load new data into PostgreSQL.

### Summary

Creating function in three arguments:

- Wikipedia data
- Kaggle metadata
- MovieLens rating data (from Kaggle)

Code used to perform all the transformation steps.

Assumptions for automated ETL pipeline:

1. Data will stay in the same formats:

    - Wikipedia data in JSON format.

    - Kaggle metadata and rating data in CSV formats.

2. No columns need to be removed.
3. Valsid list of 'alternate titles'
4. No *new* 'alternate titles' added to the data.
5. Data types will be correct when loaded into SQL.
