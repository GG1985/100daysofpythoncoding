Day 6 - Functions and Code Reusability
Functions are reusable blocks of code that make programs easier to read, debug, and maintain. Learn how to define, call, and use functions effectively.

Simple Function
Define and call a simple function greet_user which takes name as a parameter. The function should print 'Hello, name' to the console.

Default and Keyword Arguments
Update the greet_user function by adding a default value 'Guest' for the name parameter. When the function is called without an argument it should print 'Hello, Guest' to the console.

Function with Return Values
Write a function that calculates and returns the area of a rectangle. The function should take length and breadth as the arguments.

Variable Scope
To understand the difference between local and global variables, follow these steps:
1. Define a global variable and print its value.
2. Write a function and assign a new value to the same varible inside the function and then print it.
3. Print the variable again outside the function again to observe that its value didn't change.
4. Write another function that access the global variable using the global keyword and then update its value.
5. Print the variable again outside the function. Verify that it's value now got updated.

You'll notice that in step 3, whatever changes made inside the function in step 2 are not reflected but in step 5 when you use the global keyword the variable value gets updated. This shows how the global keyword is used to modify global variables from within a function.