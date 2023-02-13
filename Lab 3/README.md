Create a java program, that stores the details of a student (Name, Register Number, Email, Class, Department). You can use a two-dimensional array to store the details.

HINT: String arr[] = {{"Alwin",1847207,"alwin@christ.in","MCA","Computer Science"},{"Balagangadhar",2011204,"bala@christ.in","MDS","Data Science"}}

You need to have functions to:

Collect the details of the student
Display the details of the student
Search the details of the student
With the help of a menu-driven main function, you need to access these functions inside your class and perform the operations.

Whenever you are entering the details of a student, you need to enter the value into a static global string array, that stores the names that the user has entered. Searching this array will help you to find if the details of the student are already entered into the program.

You will have a function to perform this search operation, which can be used to implement two functionality in the code
To check if the name is already entered
While searching for a name, you can identify the index of the two-dimensional array to print the details directly.
In the end, you will have
Four functions inside your lab program class including your main class
One static String array storing the names (note the program can store up to 1024 students)
One two-dimensional string array storing the details of up to 1024 students
A menu-driven main method implementing the functions and functionality
Plan your program with a flow chart before starting with coding.
Since you are using functions, plan what should be the returning values and how to implement them.

![flow chart of the programme](https://user-images.githubusercontent.com/118046310/218381234-fc713164-304b-405f-b30a-d19862878219.jpg)


**********OUTPUT***************
 ********* WELCOME IN TO THE PROGRAMME *********
********** MAKE YOUR CHOICE            ********* 
      Press 1 to collect the details.
      Press 2 to display the details.
      Press 3 to search a student.
      Press 4 for exit.1
*********Enter your choice: **********1
How many students you want to enter: 3

....... Enter Details of student 1 ...
Enter Name: Yuvraj Giri
Enter Register No.: 22122060
Enter Email: Yuvraj@gmail.com
Enter Class: mscds
Enter Department: data science

....... Enter Details of student 2 ...
Enter Name: Dashrath
Enter Register No.: 22122039
Enter Email: Dashrath@gmail.com
Enter Class: mscds
Enter Department: data sciene

....... Enter Details of student 3 ...
Enter Name: jayesh
Enter Register No.: 22122017
Enter Email: Jayesh@gmail.com
Enter Class: ,scds
Enter Department: Data science

 ********* WELCOME IN TO THE PROGRAMME *********
********** MAKE YOUR CHOICE            *********
      Press 1 to collect the details.
      Press 2 to display the details.
      Press 3 to search a student.
      Press 4 for exit.1
*********Enter your choice: **********2


 ...The Students details is given below...

*************** Student 1 Details ***************
         Name: Yuvraj Giri
         Register No.: 22122060
         Email: Yuvraj@gmail.com
         Class: mscds
         Department: data science

*************** Student 2 Details ***************
         Name: Dashrath
         Register No.: 22122039
         Email: Dashrath@gmail.com
         Class: mscds
         Department: data sciene

*************** Student 3 Details ***************
         Name: jayesh
         Register No.: 22122017
         Email: Jayesh@gmail.com
         Class: ,scds
         Department: Data science

 ********* WELCOME IN TO THE PROGRAMME *********
********** MAKE YOUR CHOICE            *********
      Press 1 to collect the details.
      Press 2 to display the details.
      Press 3 to search a student.
      Press 4 for exit.1

*********Enter your choice: **********3
Search Name: Yuvraj Giri

*************** Student Yuvraj Giri Details ***************
         Name: Yuvraj Giri
         Register No.: 22122060
         Email: Yuvraj@gmail.com
         Class: mscds
         Department: data science

 ********* WELCOME IN TO THE PROGRAMME *********
********** MAKE YOUR CHOICE            *********
      Press 1 to collect the details.
      Press 2 to display the details.
      Press 3 to search a student.
      Press 4 for exit.1
*********Enter your choice: **********4
PS C:\Users\Yuvraj\Downloads\javalabs\22122060-MDS273L-JAVA\Lab 3>
