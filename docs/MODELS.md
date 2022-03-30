1. [Overview](OVERVIEW.md)
2. [Installation](INSTALLATION.md)
3. [Configuration](CONFIGURATION.md)
4. [Seeds](SEED.md)
5. [Models](MODELS.md)
6. [Sources](SOURCES.md)
7. [Tests](TESTS.md)
8. [Deploy](DEPLOY.md)
---
# Models
To get started, this demo contains several models with different materialisations.

You can find these in `./demo_project/models/`.

The current models are:
- people
  - people_usa
    - This model takes the columns that describe our fictional people from the seed `people_and_accounts`
    - Materialisation: table
- accounts
  - accounts_usa
    - This model takes the columns that describe our fictional bank accounts plus the non-identifiable ID that referrs to the owner of the account, from the seed `people_and_accounts`
    - Materialisation: table

---
Next: [Sources](SOURCES.md)