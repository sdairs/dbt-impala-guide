1. [Overview](OVERVIEW.md)
2. [Installation](INSTALLATION.md)
3. [Configuration](CONFIGURATION.md)
4. [Seeds](SEED.md)
5. [Models](MODELS.md)
6. [Sources](SOURCES.md)
7. [Tests](TESTS.md)
8. [Deploy](DEPLOY.md)
---
# Installation

## Python
### Version
dbt-impala requires Python >3.8

### Virtual Environment (optional)
It is highly recommended to use a Python virtual environment (venv) to use dbt and dbt-impala. This isolates your Python environment from the system Python environment.

See the official docs on using [python3 venv](https://docs.python.org/3/library/venv.html).

### Installing dbt Core

[dbt Core installation documentation](https://docs.getdbt.com/dbt-cli/install/overview)

`pip install dbt-core`

### Installing Impyla

[Impyla](https://github.com/cloudera/impyla) is a python library for interacting with Apache Impala (and Hive) maintained by Cloudera.

`pip install impyla`

### Installing dbt-impyla

`pip install dbt-impala`

---
Next: [Configuration](CONFIGURATION.md)
