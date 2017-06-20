# PenroseDB

A SQLite3 database for programs written for Penrose, a system that automatically visualizes mathematics.

## Usage

```bash
$ python3 penroseDB.py insert < continuousmap.sub # Creates an entry in penrose.db
```

Programs are passed in via standard input

- valid commands: `create`, `insert`, `view`
    - `create`: create a new table called `programs` in the database. Do this when you have a new database to work with
    - `insert`: take lines from `stdin` and stop reading on `eof`
    - `view`  : view the total number of lines in the DB

- optional arguments: -h, --help 

