# oops_lab_experiments

EXP 1 (A)  Understand the basics of C++ library, variables, data type,  input and output  
Write a program to find the area of the rectangle and the perimeter of the triangle. 
EXP 1 (B)  Implement banking management system using switch case user-defined functions and do while 
loop.  
EXP 2   Define a structure Student with fields rollNo, name, age, and marks. Create an array of 10 Student 
structures and initialize it with sample data. Write a C++ program to display the details of all 
students. 
EXP 3 (A) Create a class in C++ electricity to find the bill of a person    
Units  Amount (in Rs)  
 
 
100  1.5 per unit   200  2 per unit  
300  3 per unit  
EXP 3 (B) Create a C++ program to manage a hospital's patient records using dynamic memory allocation. 
The program should allow users to: 
1. Add new patients. 
2. Display all patients. 
3. Search for a patient by name. 
4. Delete a patient. 
Requirements: 
1. Define a Patient class with attributes: name, age, disease, and room number. 
2. Create a Hospital class with methods: 
    - addPatient(): dynamically allocates memory for a new patient. 
    - displayPatients(): displays all patients in the hospital. 
    - searchPatient(): searches for a patient by name. 
    - deletePatient(): deletes a patient from the hospital. 
3. Use dynamic memory allocation (new, delete) to manage memory. 
EXP 4 Design a Transportation class in C++ that uses function overloading to calculate the cost of 
shipping different types of packages. The class should have the following functions: 
 
1. calculateCost(weight) to calculate the cost of shipping a package based on its weight. 
2. calculateCost(length, width, height) to calculate the cost of shipping a package based on its 
dimensions. 
3. calculateCost(packageType, weight) to calculate the cost of shipping a package based on its 
type (e.g., ground, air, express) and weight. 
 
Overload these functions to handle different package types: - Ground packages - Air packages - Express packages 
 
Constraints for the cost calculation concerning the parameters: 
calculateCost(weight) - Weight range: 0.1 kg to 50 kg - Cost calculation: 
    - 0.1 kg to 1 kg: $5 + ($2/kg * weight) 
    - 1 kg to 10 kg: $10 + ($1.5/kg * weight) 
    - 10 kg to 50 kg: $20 + ($1/kg * weight) 
 
calculateCost(length, width, height) - Dimension range: 
    - Length: 10 cm to 200 cm 
    - Width: 10 cm to 100 cm 
    - Height: 10 cm to 50 cm - Cost calculation: 
    - Small package (volume < 0.1 cubic meters): $10 + ($0.5/cubic meter * volume) 
    - Medium package (volume < 0.5 cubic meters): $15 + ($0.25/cubic meter * volume) 
    - Large package (volume >= 0.5 cubic meters): $25 + ($0.1/cubic meter * volume) 
 
calculateCost(packageType, weight) - Package types: Ground, Air, Express - Weight range: 0.1 kg to 50 kg - Cost calculation: 
    - Ground package: 
        - 0.1 kg to 1 kg: $5 + ($2/kg * weight) 
        - 1 kg to 10 kg: $10 + ($1.5/kg * weight) 
        - 10 kg to 50 kg: $20 + ($1/kg * weight) 
    - Air package: 
        - 0.1 kg to 1 kg: $10 + ($3/kg * weight) 
        - 1 kg to 10 kg: $20 + ($2/kg * weight) 
        - 10 kg to 50 kg: $30 + ($1.5/kg * weight) 
    - Express package: 
        - 0.1 kg to 1 kg: $15 + ($4/kg * weight) 
        - 1 kg to 10 kg: $30 + ($3/kg * weight) 
        - 10 kg to 50 kg: $40 + ($2/kg * weight) 
Create a main function to demonstrate the usage of these overloaded functions with 
different inputs. 
EXP 5  
EXP 6  
Create a class student using the following attributes   
Name- string, roll number- integer, marks- float   
Implement the following constructors   - 
A Default constructor that initializes name as string “ ”  roll number to 0 and marks is 0.0.   - - 
A Parameterize constructor that takes 3 arguments string name, integer roll number, float 
marks.  
A Copy constructor that creates the copy of a given student object.  
The main function creates an instance of the student class using three constructors and displays 
info.  
Let's consider scenario involving  two  classes a “ Bank Account “ and a “ Friend function “ class 
that stimulates a real-life banking situation.  - 
The Bank Account class represents a bank account with private member variables like account 
holder, account number, and balance.  - 
In the main function we create two bank accounts and then use the   
Friend:: transfer Funds friend function to transfer funds from one account to another.   
The Friend Function class has a friend function name transferFunds which allow it to access 
and modify the private members of Bank Account objects to transfer funds between th
