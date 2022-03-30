1. [Overview](OVERVIEW.md)
2. [Installation](INSTALLATION.md)
3. [Configuration](CONFIGURATION.md)
4. [Seeds](SEED.md)
5. [Models](MODELS.md)
6. [Sources](SOURCES.md)
7. [Tests](TESTS.md)
8. [Deploy](DEPLOY.md)
---
# Configuration

## dbt profile
Add an Impala target to your dbt profile.

### Cloudera Data Warehouse profile example
Below is a sample profile to connect with an Impala virtual warehouse in CDP.

For the `host` you should obtain the hostname for your virtual warehouse as per [steps 6 & 7 from this page](https://docs.cloudera.com/data-warehouse/cloud/querying-data/topics/dw-connect-to-hive-virt-warehouse-with-tableau.html). 

For example `my-vw-impala.my-cdp-env.a123-1a2b.cloudera.site`

```
demo_project:
  outputs:
    dev:
     type: impala
     host: <impala endpoint>
     port: 443
     dbname: demo
     schema: demo
     user: user1
     password: Password123!
     auth_type: ldap
     http_path='cliservice'
  target: dev
```

### Cloudera DataHub profile example
> TODO

### Cloudera Private Cloud profile exaple
> TODO

## Test configuration

Run `dbt debug` to test your connection to CDW.

---
Next: [Seeds](SEED.md)