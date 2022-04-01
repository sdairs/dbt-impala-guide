1. [Overview](OVERVIEW.md)
2. [Installation](INSTALLATION.md)
3. [Configuration](CONFIGURATION.md)
4. [Seeds](SEED.md)
5. [Models](MODELS.md)
6. [Sources](SOURCES.md)
7. [Tests](TESTS.md)
8. [Deploy](DEPLOY.md)
---
> v1.0.4
# Overview
[dbt](https://github.com/dbt-labs/dbt-core) is a rapidly growing project that aims to enable data teams to ship data like software teams ship software.

## In this guide
This guide will walk you through getting started with the `dbt-impala` adapter built by [Cloudera](https://www.cloudera.com/) to use with [Apache Impala](https://impala.apache.org/) and Cloudera Data Platform (CDP).

## Supported features
| Name | Supported |
|------|-----------|
|Materialization: Table|Yes|
|Materialization: View|Yes|
|Materialization: Incremental - Append|Yes|
|Materialization: Incremental - Insert+Overwrite|Yes|
|Materialization: Incremental - Merge|No|
|Materialization: Ephemeral|No|
|Seeds|Yes|
|Tests|Yes|
|Snapshots|Yes|
|Documentation|Yes|
|Authentication: LDAP|Yes|
|Authentication: Kerberos|Yes|

## Supported endpoints
| Name | Supported |
|------|-----------|
|Cloudera Data Warehouse|Yes|
|Cloudera DataHub|Yes|
|Cloudera Private Cloud|Yes|

## Getting ready

### Cloudera Data Warehouse
To use dbt-impala with CDW, you must have an Impala Virtual Warehouse running in CDP Public Cloud.

To do so, follow the steps
1. [Activating an AWS environment](https://docs.cloudera.com/data-warehouse/cloud/aws-environments/topics/dw-activating-environments-4-data-catalogs.html)
2. [Setting up your first Database Catalog](https://docs.cloudera.com/data-warehouse/cloud/getting-started/topics/dw-get-started-data-lake.html)
3. [Creating your first Virtual Warehouse on public cloud environments](https://docs.cloudera.com/data-warehouse/cloud/getting-started/topics/dw-create-virtual-warehouse-end-to-end-flow.html)

### CDP Workload User
To authenticate with CDP, you must provide your Workload username & password.

If you need helping setting that up, follow the steps here:
1. [Setting the workload password](https://docs.cloudera.com/management-console/cloud/user-management/topics/mc-setting-the-ipa-password.html)

---
Next: [Installation](INSTALLATION.md)
