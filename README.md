Financial Records Management System
--

This Financial Records Management System is a C++ program designed to help users manage their financial records such as incomes, expenses, and saving goals. The program allows users to add, view, update, and delete records, as well as calculate the total amount and display a summary of their financial data.

How to Use
-
1)Compilation: Compile the code using a C++ compiler. For example:

      g++ -o finance_manager main.cpp

2)Execution: Run the compiled executable. For example:

      ./finance_manager

3)Menu Options: Follow the on-screen menu to perform various actions such as adding, viewing, updating, and deleting records.
4)Saving Data: The program automatically saves records to separate text files (incomes.txt, expenses.txt, savingGoals.txt) when exiting.

Features
-
1) Add Records: Users can add new records for incomes, expenses, and saving goals.
2) View Records: Users can view existing records for incomes, expenses, and saving goals.
3) Update Records: Users can update existing records, including changing descriptions and amounts.
4) Delete Records: Users can delete unwanted records from the system.
5) Calculate Total: The program can calculate the total amount for incomes, expenses, and saving goals.
6) Display Summary: Users can view a summary of their financial data, including total incomes, total expenses, total saving goals, and remaining amounts.
   
File Structure
-
- main.cpp: Contains the main program logic.
- incomes.txt: Text file to store income records.
- expenses.txt: Text file to store expense records.
- savingGoals.txt: Text file to store saving goal records.
  
Dependencies
-
- C++ Compiler (e.g., g++)
- Standard C++ Libraries (iostream, fstream, vector, string, limits)
- Operating System with Command Line Interface

Future Improvements
-
- Add authentication and user-specific data storage.
- Implement data validation for input fields.
- Enhance user interface with a graphical interface.
- Support for additional financial operations such as budgeting and forecasting.

Contributors
-
[Tynybekov Nurtai] - Initial development
