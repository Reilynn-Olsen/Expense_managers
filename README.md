# Expense_managers
A ruby commandline application that tracks expenses via a postgreSQL server.

Run the program with just ./expense for a help menu.

Commands.

add AMOUNT MEMO [DATE]- Records a new expense the amount of the expense and memo are required. Date is not, if no date is given it will record the time of data entry as the date.
clear - Clears all expenses.
list - Lists all expenses in the database.
delete NUMBER - Removes an expenses with an id NUMBER.
search QUERY - Searches for expenses by memo.
