# Package index

## Mock DB methods

- [`with_mock_db()`](https://docs.ropensci.org/dittodb/reference/mockdb.md)
  [`start_mock_db()`](https://docs.ropensci.org/dittodb/reference/mockdb.md)
  [`stop_mock_db()`](https://docs.ropensci.org/dittodb/reference/mockdb.md)
  : Run DBI queries against a mocked database
- [`with_mock_path()`](https://docs.ropensci.org/dittodb/reference/with_mock_path.md)
  : Run the DBI queries in an alternate mock directory

## Capturing fixtures

- [`start_db_capturing()`](https://docs.ropensci.org/dittodb/reference/capture_requests.md)
  [`stop_db_capturing()`](https://docs.ropensci.org/dittodb/reference/capture_requests.md)
  [`capture_db_requests()`](https://docs.ropensci.org/dittodb/reference/capture_requests.md)
  : Capture and record database transactions and save them as mocks

## Utilities

- [`expect_sql()`](https://docs.ropensci.org/dittodb/reference/expect_sql.md)
  **\[experimental\]** : Detect if a specific SQL statement is sent

- [`db_mock_paths()`](https://docs.ropensci.org/dittodb/reference/mockPaths.md)
  [`.db_mock_paths()`](https://docs.ropensci.org/dittodb/reference/mockPaths.md)
  : Set an alternate directory for mock API fixtures

- [`redact_columns()`](https://docs.ropensci.org/dittodb/reference/redact_columns.md)
  : Redact columns from a dataframe with the default redactors

- [`set_dittodb_debug_level()`](https://docs.ropensci.org/dittodb/reference/set_dittodb_debug_level.md)
  :

  Set `dittodb`'s debug level

- [`use_dittodb()`](https://docs.ropensci.org/dittodb/reference/use_dittodb.md)
  :

  Use `dittodb` in your tests

## DBI methods

- [`dbDisconnect(`*`<DBIMockConnection>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbMockConnect()`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbExistsTable(`*`<DBIMockConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbExistsTable(`*`<DBIMockConnection>`*`,`*`<Id>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbListTables(`*`<DBIMockConnection>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbListFields(`*`<DBIMockConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbListFields(`*`<DBIMockConnection>`*`,`*`<Id>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbListFields(`*`<DBIMockConnection>`*`,`*`<ANY>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbSendQuery(`*`<DBIMockConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbSendQuery(`*`<DBIMockConnection>`*`,`*`<SQL>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbSendStatement(`*`<DBIMockConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbFetch(`*`<DBIMockResult>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`fetch(`*`<DBIMockResult>`*`,`*`<ANY>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`fetch(`*`<DBIMockResult>`*`,`*`<missing>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbClearResult(`*`<DBIMockResult>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbHasCompleted(`*`<DBIMockResult>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbGetQuery(`*`<DBIMockRPostgreSQLConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbGetRowsAffected(`*`<DBIMockResult>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbGetInfo(`*`<DBIMockConnection>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbWriteTable(`*`<DBIMockConnection>`*`,`*`<character>`*`,`*`<data.frame>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbRemoveTable(`*`<DBIMockConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbColumnInfo(`*`<DBIMockResult>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbGetInfo(`*`<DBIMockResult>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbQuoteIdentifier(`*`<DBIMockRPostgresConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbQuoteIdentifier(`*`<DBIMockRPostgresConnection>`*`,`*`<SQL>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbQuoteString(`*`<DBIMockRPostgresConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbQuoteString(`*`<DBIMockRPostgresConnection>`*`,`*`<SQL>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbQuoteString(`*`<DBIMockMariaDBConnection>`*`,`*`<character>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbQuoteString(`*`<DBIMockMariaDBConnection>`*`,`*`<SQL>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbBegin(`*`<DBIMockConnection>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbCommit(`*`<DBIMockConnection>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  [`dbRollback(`*`<DBIMockConnection>`*`)`](https://docs.ropensci.org/dittodb/reference/mock-db-methods.md)
  : Methods for interacting with DB mocks instead of an actual database

## Test DB creation

- [`nycflights_sqlite()`](https://docs.ropensci.org/dittodb/reference/nycflights_sqlite.md)
  : An SQLite connection to a subset of nycflights13
- [`nycflights13_create_sql()`](https://docs.ropensci.org/dittodb/reference/nycflights13_create_sql.md)
  : Create a standardised database for testing
- [`nycflights13_create_sqlite()`](https://docs.ropensci.org/dittodb/reference/nycflights13_create_sqlite.md)
  : Create an in-memory SQLite database for testing
