A payroll management system project in C++ is a console application with the use of Object Oriented Programming with graphics. This project has multiple classes and sub-classes. Users can perform basic actions like creating, editing, and deleting an employee's record. Besides these, this C++ payroll management project allows users to print the salary slip for a particular employee.
Employee’s grades are categorized as A, B, C, D and E.

The project uses the concept of the following C++ topics:
Pointers
Loops
Functions
If Else
Switch
Classes
File handling
C++ Graphics
Function overriding and overloading

The Project has three main classes and many functions in the menu
* LINES: LINE_HOR, LINE_VER, BOX, CLEARUP, CLEARDOWN
* MENUS: MAIN_MENU, EDIT_MENU, INTRODUCTION
* EMPLOYEE: NEW_EMPLOYEE, MODIFICATION, DELETION, DISPLAY, LIST, SALARY_SLIP, ADD_RECORD, MODIFY_RECORD, DELETE_RECORD, LASTCODE, CODEFOUND, RECORDNO, FOUND_CODE, DISPLAY_RECORD, VALID_DATE

How the Project Works:
* Addition of a New Employee:  
This feature is under the public functions of class employees. The information handled in this feature is employee code number, name, address, phone number, joining date (day, month and year), designation, grade and loan.
* Modify or Editing an Employee Record:
Users can edit the employee's code number, joining date (day, month and year), name, address, phone number, designation, grade, house allowance and loan given to the employee. 
* Deleting an Employee Record: 
An employee's record can be deleted using the employee's code. A deletion confirmation message displays whether the user really wants to delete the record from the file.
* Printing an Employee Salary Slip:
This function lists all the months of the year and asks for a date, employee name, designation, and grade from the user. To print the salary slip, the user needs to provide information such as the number of days worked in the month by the employee and the number of overtime worked. The slip enlists the employee's basic salary, allowance, deductions and net salary.
* Displaying Employee Record:
By entering the employee's code number, users can access all the provided information related to a particular employee via this function. The employee record information displayed is the one provided while adding a new employee record.
* Displaying List of Employees:
This feature displays the record of all employees added to a file. The records are displayed in a tabular pattern, including information such as the code name of the employee, phone number, date of joining, designation, grade and salary.
