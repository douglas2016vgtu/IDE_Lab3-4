# IDE_Lab3-4
This repository contains the code for the Integrated Development Environments course laboratory works 3 and 4 also known as second practical work.

Instructions:
Code uses a seperate class to handle student information and methods.

1) The program generates a student file, the size is determined in the for loop "i < [some number i.e. 10000]." Comment-off the following code if you wish to test run time of program using functions that call for student list file:
"//stud_list_generator();""

2) Next is a menu that accepts number integer inputs with options from 1 to 4.
-First option allows you to add new students their homework grades and an exam grade. Program should will ask if you wish to continue adding students and/or more homework marks for them, user can decide with yes or no answer to continue.
-Second option takes existing file (must be generated first so do not comment off stud_list_generator(); for first compile.)
and allows you to sort the student data alphabetically either by name or surname while also spliting student info into "studentai_islaike" or "studentai_neislaike" files based on their average final grade.
-Third option adds students from the file to a linked list container.
-Fourth option is the same as third option but the container is a queue.
These last 2 options are intended for comparing program run times with original list container. Thus they do not include sorting options and are more like testing options really.

3) If you have chosen the second option then you will have to select from 1 to 2 by whether to sort data by student name or surname.

Notes:
1) Options 3 and 4 are intended for comparing program run times with original list container. Thus they do not include sorting options and are more like testing options really.

2) Program does not print out full student table in the console as with larger student sizes this option takes many many minutes, it is more efficient to view the student list from the generated student files.

3) Only "studentai_islaike.txt" and "studentai_neislaike.txt" files can be sorted, main file "studentu_sarasas.txt" is not sorted.
