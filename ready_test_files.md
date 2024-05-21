Ready Test Files
-
Test 1 (add 2 income and show them)
-
    ======== MENU ========
    1. Add Income
    2. Add Expense
    3. Add Saving Goals
    4. View Incomes
    5. View Expenses
    6. View Saving Goals
    7. Update Record
    8. Delete Record
    9. Calculate Total
    10. Exit
    =======================

    Enter your choice:

Input:

    1


Output:

    Enter description:
    Enter amount:

Input:

    salary
    5000

Output:

    Record added successfully.

**Also add income** `investment`
**and the amount** `3000`


**Now in order to see them, select 4 in the menu**

Input:

    4

Output

    Incomes:
    1. Description: salary, Amount: $5000
    2. Description: investment, Amount: $3000


Test 2 (add 2 expenses, delete one of them and calculate total)
-
**To add expenses select 2**
Input:

    2

Output:
  
    Enter description:
    Enter amount:

Input:

    house rent
    2000

Output:

    Record added successfully.

**Also add income** `food`
**and the amount** `1000`

**To delete expense select 8**

Input:

    8

Output:
  
    1. Delete Income
    2. Delete Expense
    3. Delete Saving Goals
    0. Go Back
    Enter your choice:

Input:

    2

Output:
  
    records:
    1. Description: house rent, Amount: $2000
    2. Description: food, Amount: $1000
    Enter the record number to delete (or 0 to go back):

Input:

    2

Output:
  
    Record deleted successfully.

**To calculate and see total select 9**
Input:

    9

Output:
  
    Total Incomes: $8000
    Total Expenses: $2000
    Total Saving Goals: $0
    Remaining Amount with Saving Goals: $6000
    Remaining Amount: $6000

Test 3 (add saving goal, update income and calculate total)
-

**To add saving goal select 3**
Input:

    3

Output:
  
    Enter description:
    Enter amount:

Input:

    contract payment
    3000

Output:

    Record added successfully.


**To update income select 7**

Input:

    7

Output:
  
    1. Update Income
    2. Update Expense
    3. Update Saving Goals
    0. Go Back
    Enter your choice:

Input:

    1

Output:
  
    Records:
    1. Description: salary, Amount: $5000
    2. Description: investment, Amount: $3000
    Enter the record number to update (or 0 to go back):

Input:

    2

Output:
  
    Updating record: investment, Amount: $3000
    Enter new description:
    Enter new amount:

Input:

    investment
    2000

Output:
  
    Record updated and duplicates combined successfully.

    ======== MENU ========
    1. Add Income
    2. Add Expense
    3. Add Saving Goals
    4. View Incomes
    5. View Expenses
    6. View Saving Goals
    7. Update Record
    8. Delete Record
    9. Calculate Total
    10. Exit
    =======================

    Enter your choice:

Input:

    9
    
Output:

    Total Incomes: $7000
    Total Expenses: $2000
    Total Saving Goals: $3000
    Remaining Amount with Saving Goals: $2000
    Remaining Amount: $5000
