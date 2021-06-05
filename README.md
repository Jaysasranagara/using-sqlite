# using sqlite to input data and show on sqliteonline

use for small scale development project which does not need high processing power, and a limit
data of 281 TB, in contrary to postgreSQL which does not have a data storage limit, much more keen
for use in big data application.

The config.json of sqlite is also much more simpler, only containing 

  "development": {
    "dialect": "sqlite",
    "storage": "./sqlite-dev.db"

in contrast to using normal sql, which contain

  "development": {
    "username": "postgres",
    "password": "moonvest",
    "database": "harvest_moon",
    "host": "127.0.0.1",
    "dialect": "postgres"
  },
  
  in essence, usage of sqlite is perfect for low demanding application, as it size and lightweight transferred to speed
  and ease of usability.
