

# Grade calculator for a final statement decision


This is a project called grade calculator for a final grade statement made by Python.

It can help a user to enter and record all the grade in courses and to know the final grade statement which will be 'pass' or 'fail'.


The project includes five classes of python codes to enter input data of course name, student name, student surname, student number and the grade that is received from the course.


For initialization, the user needs to enter 5 inputs of classes.

It includes some methods that help the user to manipulate the course:
    1) class course_grade:
    This asks user to enter the name of course, and accepts only alphabetic characters as input.
    2) class student_name:
    This asks user to enter the name of student, and accepts only alphabetic characters as input.
    3) class student_surname:
    This asks user to enter the surname of student, and accepts only alphabetic characters as input.
    4)class student_id:
    This asks user to enter the id number of student, and accepts only numeric characters as input.
    5)class course_grade:
    This asks user to enter the grade for identified course, and accepts only ineteger as input.


After definition of class inputs;
-Program starts in a while loop by running classes to record data into the 'Grade System' table which is created in a sqlite databse. Thanks to while loop, the program ask user to end the program or to continue entering multiple student's data at the beginning.
-Only grade input from 'Grade' column in table is read from sql database to use them as inputs of final grade process.
-The final grade process is running with if-elif-else conditions to define numeric grades equievant in alphabetic grade system and states a final letter grade and 'Pass' or 'Fail' statement.
 This process only accepts numeric values between 0 and 100.
-For the last part, the program creates a dictionary with result data to write them into an excel document.



The program is free, so enjoy it as you wish!
  
