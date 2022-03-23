# Stacks

- Create a Stack class that will hold Integers
  - You need to determine how you will store the underlying data
  - Implement the constructor
  - Implement the push method
  - Implement the pop method
  - Implement the peek method
  - Implement the size method
  - Implement the isEmpty method
    - Do not use an isEmpty method for an underlying data structure
  - Implement a toString method that returns the stack with the top of the stack as the first element
    - Separate the elements with commas and surround all the elements with square brackets
- Create a program called `StackTester.java`
  - Create a Stack object that will hold Integers
  - Prompt the user for a filename
  - Each line in the file will be a stack operation or the print command
    - For push and pop operations, do not print anything
    - For peek, size, and isEmpty operations, print what is returned
    - For print operations, print the stack
  - You must read in the line and perform the specified operation on the Stack object you created

***Example Input:***\
input1.txt\
***Example Contents of input1.txt:***\
push 7\
push 12\
print\
push 19\
push 37\
print\
pop\
print\
peek\
size\
isEmpty\
push 72\
print\
pop\
pop\
pop\
print\
peek\
size\
isEmpty\
pop\
print\
peek\
size\
isEmpty\
***Example Output:***\
[12, 7]\
[37, 19, 12, 7]\
[19, 12, 7]\
19\
3\
false\
[72, 19, 12, 7]\
[7]\
7\
1\
false\
[]\
null\
0\
true
- - - - - - - - - - - -

## Extra Credit

- Implement the peek, size, and isEmpty methods using only the push and pop methods
  - Don't use any methods from the underlying data structure
