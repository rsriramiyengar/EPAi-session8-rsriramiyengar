# Readme File for Assignment for Session 8 - Functional Parameter
### Created by Sriram Iyengar
## Session 4 - Functional Parameter
- Global and Local Scopes
- Non Local Scopes 
- Closures
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Requirment of Assignment
-

## This Function Done in Present Assignment
1. Write a closure that takes a function and then check whether the function passed has a docstring with more than 50 characters. 50 is stored as a free variable - 200
2. Write a closure that gives you the next Fibonacci number - 100
3. We wrote a closure that counts how many times a function was called. Write a new one that can keep a track of how many times add/mul/div functions were called, and update a global dictionary variable with the counts - 250
4. Modify above such that now we can pass in different dictionary variables to update different dictionaries - 250
No readme or no docstring for each function, or no test cases, 0. Write test cases to check boundary conditions that might cause your code to fail. 

## Description of Functions in Assignment
### function_1_docstring_50_count(fn):
    """
    This Closure function thats takes in function check if its docstring is having 50 character
    if yes then stores it in  free variable doc_string else it stores False Doc String not Long enough
    """

### function_2_fibonacci():
    """
    This Closure function gives the next fibonnaci number
    """

### function_3_counter (fn: "Function Name for Counter"):
    """
    This Function creates a counter for input function and updates the global dictionary times_dict3
    """
### function_4_counter (fn: "Function Name for Counter", dict: "Input dictory name"):
    """
    This Function creates a counter for input function and updates it in given dictionary
    """

### add (a:"Number1", b"Number1")->"Sum of Numbers":
    """
    This Function Returns sum of Two given real numbers (Integer/Floats)
    """

### mul (a:"Number1", b"Number1")->"Multiplication of Numbers":
    """
    This Function Returns Multiplication of Two given real numbers (Integer/Floats)
    """
### div (a:"Number1", b"Number1")->"Division of Numbers":
    """
    This Function Returns division of Two given real numbers (Integer/Floats)
    """
## Functions used in Test File
### test_readme_exists 
- checks if Readme files exists

### test_readme_contents length 
- checks the content length of  Readme file
### test_readme_proper_description 
- checks the content length of  Readme file

### test_readme_file_for_formatting 
- checks the formatting of  Readme file

### test_indentations 
- checks if the Assignment code is properly formated

### test_function_name_had_cap_letter 
- checks if the Assignment code is function has capital letters 
### test_function_1_docstring_50_count():
- Checks if function_1_docstring_50_count works  for all boundary condition
### test_function_2_fibonacci():
- Checks if function_2_fibonacci works
### test_function_3_counter():
- Checks if function_3_counter works  for all boundary condition   
### test_function_4_counter():
- Checks if function_3_counter works  for all boundary condition

For This Assignment we made use of Following imports 
- pytest
- random
- randint
- string
Based on our understanding following concept
- Global scope
- Local scope
- nonlocal scope
- closure
- Used cases for counter creation

***
> ![My Image](https://github.com/rsriramiyengar/EPAi-session8-rsriramiyengar/blob/master/images/Image01.JPG)
***

We are using python >3.8.3

The assignment is  tested by executing 'pytest' , from python shell in same folder
