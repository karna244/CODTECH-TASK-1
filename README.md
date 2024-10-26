# CODTECH-TASK-1
NAME = KARAN.S
COMPANY = CODTECH IT SOLUTIONS
ID = :CT08DS8780
DURATION = SEPTEMBER - OCTOBER 2024
MENTOR = SARAVANI GOUNI
TASK 1 
Certainly! Below is an explanation of a C program that converts temperatures between Celsius, Fahrenheit, and Kelvin. The program will enable users to input a temperature in one scale and convert it to the other two scales.
Program Overview
The program performs the following steps:

User Input: It prompts the user to enter a temperature value and specify the scale (C for Celsius, F for Fahrenheit, K for Kelvin).
Conversion Logic: Based on the input scale, it applies the appropriate conversion formulas to calculate the equivalent temperatures in the other two scales.
Output: Finally, it displays the converted temperatures to the user.
Temperature Conversion Formulas
The following formulas are used for temperature conversion:

How It Works
Input Handling:

The program first prompts the user to enter a temperature value and its scale using scanf().
It reads the scale character while ensuring that it correctly captures input (the space before %c in scanf helps ignore whitespace).
Conversion Logic:

The convert_temperature function takes the temperature and scale as arguments.
A switch statement determines the scale and performs the appropriate conversions based on the input:
For Celsius: Converts to Fahrenheit and Kelvin.
For Fahrenheit: Converts to Celsius and Kelvin.
For Kelvin: Converts to Celsius and Fahrenheit.
Each conversion is calculated using the defined formulas.
Output:

The results are displayed using printf(), formatted to two decimal places for clarity.
Additional Features to Consider
Input Validation: You can enhance the program by checking if the entered temperature is a valid number and if the scale is one of the allowed characters (C, F, K).
Loop for Continuous Input: Implement a loop to allow the user to perform multiple conversions without restarting the program.
Error Handling: Add error messages for invalid inputs, making the program more user-friendly.
Conclusion
This C program provides a straightforward way to convert temperatures among Celsius, Fahrenheit, and Kelvin. It's useful for anyone needing to quickly perform temperature conversions, such as students or professionals in scientific fields.



TASK 2 
Creating a student management system in C involves designing a program that can handle student registrations, maintain records, and calculate grades. This system will allow users to add, edit, and delete student information efficiently. Below, I’ll outline the components and provide a basic implementation of such a system.

Program Overview
The student management system will consist of several functionalities:

Data Structure: Define a structure to hold student information (e.g., name, ID, grades).
Add Student: Functionality to register a new student.
Edit Student: Update details for an existing student.
Delete Student: Remove a student record from the system.
View Students: Display all student records.
Calculate Grades: Compute and display grades based on recorded marks.
Data Structure
You can define a structure to hold student information, including attributes like ID, name, and grades.
Explanation of the Code
Data Structure: The Student structure holds student ID, name, grades, and average.
Functions:
add_student(): Prompts for student details and calculates the average grade.
edit_student(): Allows the user to find a student by ID and update their details.
delete_student(): Finds and removes a student based on ID.
view_students(): Displays all student records, including their average grades.
Main Loop: A menu-driven interface allows users to choose actions until they decide to exit.
Additional Features to Consider
Input Validation: Ensure user inputs are valid (e.g., numeric grades, valid IDs).
File Storage: Implement functionality to save and load student records from a file for persistent storage.
Error Handling: Improve error handling for invalid operations (e.g., editing a non-existent student).
Dynamic Memory: Use dynamic memory allocation (e.g., with malloc) for handling an arbitrary number of students.
Conclusion
This C program provides a basic framework for a student management system, allowing for the addition, editing, deletion, and viewing of student records. It can be expanded with additional features and improvements based on specific requirements.





