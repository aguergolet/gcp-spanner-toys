# SQL Query Analyzer for Google Cloud Spanner

This utility helps you analyze SQL queries executed in a Google Cloud Spanner database, extracting information about the tables and columns involved. It also generates a report of potentially unused indices, considering the columns used in the WHERE clauses of the queries.

## Features

1. Extracts table names and columns used in SELECT statements and WHERE clauses.
2. Generates a report of indices that might not be utilized, as they don't contain columns used in the WHERE clause.

## Dependencies

- Python 3
- `sqlparse`
- `google-cloud-spanner`

To install the required dependencies, run:

```bash
pip3 install -r requirements.txt
