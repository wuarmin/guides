---
title: Project
order: 10
---

## Project

We can generate a new project via `hanami new`, followed by the name that we want to use.

```shell
$ hanami new bookshelf
```

## Database

The default database engine is SQLite.

We can use the `--database` argument to let Hanami to generate code for a specific database.

It supports:

  * `postgres`
  * `postgresql`
  * `sqlite` (default)
  * `sqlite3`
  * `mysql`
  * `mysql2`

## Testing Framework

The default testing framework is RSpec.

We can use the `--test` argument to specify a different framework, from the list below:

  * `rspec` (default)
  * `minitest`

## Template Engine

The default template engine is ERB.

We can use the `--template` argument to specify a different template engine, from the list below:

  * `erb` (default)
  * `haml`
  * `slim`
