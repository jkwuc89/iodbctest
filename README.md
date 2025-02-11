# iodbctest for macOS
## Introduction
This is the sample ODBC application from https://www.iodbc.org that allows one to quickly
and easily test ODBC drivers configured inside `$HOME/Library/ODBC/odbcinst.ini` and
`$HOME/Library/ODBC/odbc.ini`.

## Build instructions
1. Open the project in Xcode.
1. From the scheme dropdown, select either iodbctest-unicode for the Unicode build or iodbctest-ansi for the ANSI build.
1. Press ⌘+R to build and run iodbctest using the selected scheme.
1. Press ? to see a list of configured DSNs.
1. Enter `DSN=<dsn>` to connect to a configured DSN, replacing `<dsn>` with a DSN from the list shown in the previous step.
