# Java3_LinkedList

This program is designed to determine whether a sequence of Airline flights exists from an origin city to a destination city based on a given flight map represented as a graph. The graph consists of vertices and edges connecting the vertices, where each vertex represents a city and each edge represents a flight route between cities.

Algorithm:

    Create a stack.
    Clear marks on all cities.
    Push the original city onto the stack and mark it as visited.
    While a path to the destination city has not been found:
    a. If there are no flights from the city on top of the stack to unvisited cities, pop the city from the stack.
    b. Otherwise, select an unvisited destination city and push it onto the stack, marking it as visited.

Classes:

    Vertex class: Represents a city with attributes for city name and visited status. Provides methods to set and get city information, as   
    well as marking cities as visited.
    Node class: Represents a node in the graph, containing a city vertex and an ArrayList of adjacent cities (path). Provides methods to 
    manipulate and retrieve path information.
