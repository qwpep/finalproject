Key Design Decisions
-
- File Storage for Data Persistence: Files allow the program to save data between sessions.
- Record Data Structure: Simplifies storing the description and amount of each record.
- Command-Line Interface: Provides a simple way for users to interact with the program.

Algorithms and Data Structures Used
-
- Record Structure: Stores the description and amount of each entry.
- Vector vector<Record>: Stores all records of a specific type (incomes, expenses, saving goals).
- Search and Update Algorithms: Check for existing records with the same description and update their amounts.
- Deletion Algorithm: Removes records by index.

Functions and Modules
-
**Structure**

    struct Record
    {
      string description;
      double amount;
    };

**Loads records from a file.**


    vector<Record> loadRecords(const string &fileName);


**Saves records to a file.**


    void saveRecords(const string &fileName, const vector<Record> &records);

**Adds a new record or updates an existing one.**


    void addRecord(vector<Record> &records);

**Displays records.**


    void viewRecords(const vector<Record> &records, const string &type);

**Updates a selected record.**


    void updateRecord(vector<Record> &records);

**Allows the user to select the type of record to update.**


    void selectUpdateRecord(vector<Record> &incomes, vector<Record> &expenses, vector<Record> &savingGoals);

**Deletes a selected record.**


    void deleteRecord(vector<Record> &records);

**Allows the user to select the type of record to delete.**

    void selectDeleteRecord(vector<Record> &incomes, vector<Record> &expenses, vector<Record> &savingGoals);

**Calculates the total amount of records.**

    double calculateTotal(const vector<Record> &records);

**Calculates and displays a summary.**

    void calculateSummary(const vector<Record> &incomes, const vector<Record> &expenses, const vector<Record> &savingGoals);


**Main Function main**

**The main loop of the program with the menu.**

    int main();

Example Usage with Instructions
-

### Main Menu

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

### Adding a Record

1. Select option 1, 2, or 3 to add an income, expense, or saving goal.
2. Enter the description and amount.

### Viewing Records
Select option 4, 5, or 6 to view incomes, expenses, or saving goals.

### Updating a Record
1. Select option
2. Choose the type of record.
3. Select the record to update.
4. Enter new description and amount.

### Deleting a Record
1. Select option 8.
2. Choose the type of record.
3. Select the record to delete.

### Calculating and Displaying the Summary

- Select option 9 to calculate and display the total amount of incomes, expenses, and saving goals.

### Saving Data and Exiting

- Select option 10 to save the data to files and exit the program.

Ready Test Files
-
Prepare three text files incomes.txt, expenses.txt, and savingGoals.txt with sample data:

### `incomes.txt`   
    Salary 3000
    Freelance 1200
    Investment 500

### `expenses.txt`
    Rent 1000
    Groceries 300
    Utilities 150

### 'savingGoals.txt'
    Vacation 200
    EmergencyFund 100
    NewCar 150
