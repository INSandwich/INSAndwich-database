# INSAndwich database
Here we'll save all the sql files for our INSAndwich project.

This will include the table creation files, as well as some database dummy filling files.

The technology we use is sqlite3.

Links:
  - [sqlite3](https://www.sqlite.org/)

Todo List:
  - Add an sql script to insert dummy data in the database

Considered things to do (to discuss): 
  - Add UNIQUE constraint to the names of roles and categories

## How to use
  - Install sqlite3 (see link above)
  - run the following commands:

```
$ cd dumps
$ sqlite3 insandwich.db < insandwich.sql
$ sqlite3 insandwich.db
```

If you want to clean up the folder (which you should do before any push to the repo):
```
$ ./dumps/clean.sh
```
