# Chapter-4-
 exercises of chapter 4 of the book "practical C programmin
 
 ### Exercise 4-1: Write a program to print your name, social security number, and date of birth.

```c
#include <stdio.h> 
 int main()  
  {
     printf("Name   : Alfonso Gumesindo Jimenez Valdes\n"); 
     printf("date of birth    : October 13, 2002\n"); 
     printf("SSN : 25170227349\n"); 
     return(0); 
  }
  ```
 ### Exercise 4-2: Write a program to print a block E using asterisks (*), where the Ehas a height of seven characters and a width of five characters.
 
 ```c
 #include <stdio.h> 
 int main() 
 {
	printf("*****\n");
	printf("*\n");
	printf("*\n");
	printf("*****\n");
	printf("*\n");
	printf("*\n");
	printf("*****\n");

	return(0);
}
 ```
### Exercise 4-3: Write a program to compute the area and perimeter of a rectangle with a width of three inches and a height of five inches. What changes must be made to the program so that it works for a rectangle with a width of 6.8 inches and a length of 2.3 inches?
