# Graphs

- Create a Graph class
  - You need to determine how you will store the underlying data
  - Implement a default constructor that initializes the graph to have no vertices and no edges
    - You also need to specify whether the graph is directed or undirected
  - Implement a method to add a vertex to the graph (addVertex)
    - A vertex will be a single capital letter
  - Implement a method to add an edge to the graph (addEdge)
    - An edge will be two capital letters
  - Implement a method to remove a vertex from the graph (removeVertex)
    - This should also remove any edges that are connected to that vertex
  - Implement a method to remove an edge from the graph (removeEdge)
  - Implement a method takes two vertices as parameters and returns the shortest path from the first vertex to the second (findPath)
    - Return null if there is no path from the first vertex to the second
  - Implement a method that takes two vertices as parameters and returns whether or not the first vertex is adjacent to the second vertex (isAdjacent)
  - Implement a toString method that returns the graph with the vertices and edges printed out
    - Separate the elements with commas and surround each set of elements with square brackets
- Create a program called `GraphTester.java`
  - Create a Graph object
  - Prompt the user for a filename
  - Each line in the file will be a stack operation or the print command
    - For add and remove operations, do not print anything
    - For findPath and isAdjacent operations, print what is returned
    - For print operations, print the graph
  - You must read in the line and perform the specified operation on the Graph object you created

***Example Input:***\
***Example Contents of input1.txt:***\
***Example Output:***
