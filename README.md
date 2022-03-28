# Graphs

- Create a Graph class
  - You need to determine how you will store the underlying data
  - Implement a default constructor that initializes the graph to have no vertices and no edges
    - The graph will be directed
  - Implement a method to add a vertex to the graph (addVertex)
    - A vertex will be a single capital letter
  - Implement a method to add an edge to the graph (addEdge)
    - An edge will be two capital letters
  - Implement a method to remove a vertex from the graph (removeVertex)
    - This should also remove any edges that are connected to that vertex
  - Implement a method to remove an edge from the graph (removeEdge)
  - Implement a method that takes two vertices as parameters and returns whether or not the first vertex is adjacent to the second vertex (isAdjacent)
  - Implement a toString method that returns the graph with the vertices and edges printed out
    - Separate the elements with commas and surround each set of elements with square brackets
    - Put the vertices in alphabetical order
    - Put the edges in alphabetical order
    - Ex. V: [A, B], E: [AB]
- Create a program called `GraphTester.java`
  - Create a Graph object
  - Prompt the user for a filename
    - This file will contain only add commands to create the graph
  - Prompt the user for another filename
    - This file will contain any commands for the graph 
  - Each line in the file will be a graph operation or the print command
    - For add and remove operations, do not print anything
    - For isAdjacent operations, print what is returned
    - For print operations, print the graph
  - You must read in the line and perform the specified operation on the Graph object you created

***Example Input:***\
graph1.txt\
commands1.txt\
***Example Contents of graph1.txt:***\
add vertex H\
add vertex G\
add vertex F\
add vertex E\
add vertex A\
add vertex B\
add vertex C\
add vertex D\
add edge AB\
add edge CD\
add edge EF\
add edge GH\
add edge AG\
add edge CE\
add edge HD\
add edge AD\
***Example Contents of commands1.txt:***\
print\
remove edge AD\
print\
is adjacent HD\
is adjacent EF\
is adjacent FE\
add edge FE\
print\
is adjacent FE\
***Example Output:***\
V: [A, B, C, D, E, F, G, H], E: [AB, AD, AG, CD, CE, EF, GH, HD]\
V: [A, B, C, D, E, F, G, H], E: [AB, AG, CD, CE, EF, GH, HD]\
true\
true\
false\
V: [A, B, C, D, E, F, G, H], E: [AB, AG, CD, CE, EF, FE, GH, HD]\
true

- - - - - - - - - - - - 

### Extra credit

- Implement a method in the Graph class takes two vertices as parameters and returns the shortest path from the first vertex to the second (findPath)
  - Separate the vertices with dashes
  - Return null if there is no path from the first vertex to the second
- In GraphTester, for the findPath operation, print what is returned 
