\# 🧮 C Variables Program



\*\*Author:\*\* Ahmed Farooq  

\*\*Language:\*\* C  



\## 📘 Description

This is a simple C program that:

1\. Declares an integer variable.

2\. Takes user input for marks.

3\. Displays the entered marks.



\## 💻 Code Example



```c

\#include <stdio.h>

\#include <conio.h>



void main()

{

&nbsp;   int marks = 0;

&nbsp;   clrscr();



&nbsp;   printf("Enter your marks: ");

&nbsp;   scanf("%d", \&marks);



&nbsp;   printf("Your marks is %d", marks);



&nbsp;   getch();

}



