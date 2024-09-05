# Travelling Salesman Problem (TSP) Project - Ant Colony Optimization (ACO) Metaheuristic

This project was developed as part of the Algorithm Analysis course during the 2019-02 semester of the Systems Engineering program. The primary objective of the project is to implement a solution to the Travelling Salesman Problem (TSP) using the Ant Colony Optimization (ACO) Metaheuristic.

Project Description
The Travelling Salesman Problem is a combinatorial optimization problem that seeks to find the shortest path that allows a traveler to visit a series of cities exactly once and return to the starting city. Since the problem is NP-hard, metaheuristic techniques like Ant Colony Optimization are used to find approximate solutions within a reasonable time.

## Ant Colony Optimization (ACO) Metaheuristic)

![ver](https://www.google.com/urlsa=i&url=https%3A%2F%2Felpais.com%2Fretina%2F2019%2F01%2F25%2Ftendencias%2F1548429275_846133.html&psig=AOvVaw11RpWRTackEPkELPF6U5iJ&ust=1725591547101000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqGAoTCPD76srnqogDFQAAAAAdAAAAABCRAQ)

The ACO algorithm simulates the behavior of ants in nature, where ants find the shortest path between their colony and a food source using pheromones. In this project, this behavior is simulated to solve the TSP, where each ant constructs a partial solution and pheromones are deposited on the most promising routes, guiding future ants toward optimal solutions.

# Project Features
#### Input Data: The user enters the number of cities (vertices) and the distances between them (edges) to generate the adjacency matrix of the graph.

ACO Simulation: The number of ants, alpha and beta parameters influencing the importance of pheromones and visibility, and the pheromone evaporation rate are configured.

Results: The distance matrix is printed, and the shortest approximate path found by the algorithm is calculated.

# Running the Project
To run the project, simply clone the repository and compile the Java files in a compatible development environment (such as NetBeans or Eclipse). Make sure that the input data is consistent and that valid values for the distances between cities are provided.


# Clone the repository
git clone https://github.com/lightday15/TravellingSalesmanProblem_ACO.git

# Compile and run the project
javac TravellingSalesmanProblem_ACO.java
java TravellingSalesmanProblem_ACO
# Requirements
Java JDK 8 or higher
Development environment (NetBeans, Eclipse, IntelliJ IDEA)
# Author
This project was developed by Lightday Carrillo as part of the Algorithm Analysis course.
