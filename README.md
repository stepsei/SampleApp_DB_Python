Example Application using python and sqlite3

Criteria:

1. Add 100 random integers, ranging from 0 to 100, to a new database
called newnum.db

2. Prompt the user whether they would like to perform an
aggregation (AVG, MAX, MIN, or SUM) or exist the program altogether

Algorithm:

First script(sql-insert.py)

- Import Libraries
- Establish a connection and create the newnum.db database
- Open the cursor
- Create table

Second script(sql-search.py)
- Import the sqlite3 library
- Connect to the database
- Establish a cursor
- Using an infinite loop, continue to ask the user to enter
the number of an operation that they'd like to perform.
- If they enter a number associated with a SQL Function,
run that function, However, if they enter number not associated with a function,
ask them to enter another number.
- If they enter the number 5, break the loop and exit the program.

