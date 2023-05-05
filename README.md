Download Link: https://assignmentchef.com/product/solved-cse240-homework-7-8-linked-list-of-containers
<br>
Introduction

The aim of this assignment is to make sure that you understand and are familiar with the concepts covered in the lectures, including linked list, pointer operations, and parameter passing mechanisms. This two-assignment combination allows you to put all together that you have learned in C programming language into a large program. By the end of the assignment, you should have understood and exercised

<ul>

 <li>Pointer and pointer to pointer operations accessing structured data</li>

 <li>Linked list of structures, with complex manipulations of pointer and structure</li>

 <li>Different types of parameter passing mechanisms and return values of different types.</li>

 <li>Solving problems in recursion</li>

</ul>




<strong>Reading</strong>:​ Textbook Chapter 2, Section 2.5.4 on linked list and Section 2.6 on parameter passing and Section 2.10.

<strong>Preparation</strong>:​ Complete the multiple choice questions in the textbook exercise section. The answer keys can be found in the course Web site. These exercises can help you prepare for your weekly quiz and the exam. You are encouraged to read the other exercise questions and make sure you understand these questions in the textbook exercise section, which can help you better understand what materials are expected to understand after the lectures and homework on each chapter.

You are expected to do the majority of the assignment outside the class meetings. Should you need assistance, or have questions about the assignment, please contact the instructor or the TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board. However, <strong>do</strong>​<strong> not share your answers and code</strong> in the course discussion board.​

Homework Description

This is a project consisting of HW 7 and HW 8. The grades will be entered into the gradebook as two homework grades. If you do not submit this project, you will have two zeros in gradebook. The following figure shows an instance of the linked list that you will be building and managing in these two homework. The node of the main linked list is called studentList, which contains two members: student member is a pointer to the student node and a pointer to next studentList node. The student node contains three members: student name, roll number and a pointer to courses list. The node in the course list has course name and a pointer to next course node.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/288.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/288.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>HW 7 Programming Assignment

You are given a partially completed program hw7_8.c. Your should follow the instructions given in the program to complete the functions so that the program executes properly. You will be completing a program that creates a list of students. In HW7, the lowest linked list ‘course’ does not come into picture.  It is a menu driven program where user is given following options:

<ol>

 <li>Add a student’s information (name and roll number). In HW7, the new student needs to be added to the head of the linked list. We do not ask user for courses to add in this function. So simply assign NULL to *courses member of the ‘student’ node when a new student is added to the list in this function. (*courses is used in HW8)</li>

 <li>Display the student list. This function should print student’s name and roll number. It should not print courses of the student. You must write a recursive function to implement this function. You may print the list forward or backward. See expected output for this function below.</li>

 <li>Search a student in the list by name. This function should return the ‘student’ node if that student is found in the list, else return NULL. It is used as helper function in executeAction() to check if the student exists in the list.</li>

 <li>Remove the student from the list. This function removes the student’s name and roll number.</li>

</ol>

(Notice that new student ‘Jim Halpert’ was added to head of linked list. So he appears first while displaying. This is forward list. You may display the list forward or backward.) <strong>removeStudent(15 points) </strong>

(After removing student ‘Michael Scott’, you can use display function to verify. This display function is of HW8. It is used here only to demonstrate that the student is removed)

<strong>         </strong>HW 8 Programming Assignment

HW8 homework is the continuation of HW 7. It focuses on using ‘course’ linked list. In this part, the user should be able to use following menu options:

<ol>

 <li>Add a course to a student’s profile. This function assumes that the student is added in the list and assigns course name using the *courses member of ‘student’ node. You may add the new course to the head or tail of the ‘course’ linked list. (Sample solution adds the course to the tail)</li>

 <li>Display the last added course for a student. ‘Add course’ option can be used multiple times to add multiple courses under a student’s profile. This function should return the most recently added course of the student. See expected output below.</li>

 <li>Display the list of students and their course list. This function should display student’s name, roll number and courses. See expected output below. (Display function in HW 7 did not display courses of the student).</li>

</ol>




The removeStudent() of HW7 removed only the student’s name and roll number while removing the student form the list. In HW8, you need to modify the removeStudent() of HW7 to remove courses of the student as well when removing the student from the list. This is mentioned in the end of C file as HW8 Q4




Expected outputs:

<h2>addCourse</h2>

(The course is added using ‘c’ option. You can use the display function to verify) <strong>lastCourse (15 points) </strong>

(As seen in display function, student ‘Michael Scott’ has two courses. The most recently added course ‘Embedded Systems’ was added to tail of *courses list. So that course appears when ‘l’ option is used)

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>




<strong> </strong>

<strong> </strong>

<strong> </strong>























