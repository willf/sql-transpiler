# SQL Transpiler

Convert from one SQL dialect to another, using the sqlglot library.

```bash
❯ script/transpile --help
usage: transpile [-h] [-f FROM_DIALECT] [--pretty] to_dialect

positional arguments:
  to_dialect            target dialect. Must be one of: bigquery, clickhouse, databricks, drill, duckdb, hive,
                        mysql, oracle, postgres, presto, redshift, snowflake, spark, sqlite, starrocks,
                        tableau, trino, tsql

options:
  -h, --help            show this help message and exit
  -f FROM_DIALECT, --from_dialect FROM_DIALECT
                        target dialect. Defaults to 'guess'
  --pretty              pretty print
```

---

## Installation

1. You must have [uv](https://docs.astral.sh/uv/) installed, and a version of Python 3.9 or higher.
2. You should clone this repository.
3. Run `uv sync` to install the dependencies.

## Usage

1. Run `uv run script/transpile` to see the usage information, or
2. Run `uv shell` to enter the virtual environment and then run `script/transpile`.

## Contributing

We welcome contributions. Please see our [contributing guidelines](contributing.md) for more information.

## Code of Conduct

We expect project participants to adhere to our [Code of Conduct](code-of-conduct.md).
