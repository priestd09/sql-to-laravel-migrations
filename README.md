# sql-to-laravel-migration

A script to genenerate Laravel migrations from existing MySQL database.

It isn't super comprehensive and is meant to quicken the setting up of Laravel migrations on an existing database.

# Specs

Python2.7

# Set Up

1. install mysql python connector https://dev.mysql.com/downloads/connector/python/
2. fill database connection details in ./config.json

# Run

## config.json

only_include_tables - takes precedence if tables are specified

exclude_tables - tables will be excluded

## terminal

```
python retrieve_and_convert.py
```

# Output

Files will be in output folder

# Contribution

Feel free to report any bugs or contribute!
