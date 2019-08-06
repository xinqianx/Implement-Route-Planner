# Implement-Route-Planner
Project of nano degree from Udacity - Intro to self-driving cars


## About this Project
In this project, you will build a route-planning algorithm like the one used in Google Maps to calculate the shortest path between two points on a map.


**_Project Instructions_**

The Jupyter Notebook which contains all the instructions for the project. `project_notebook.ipynb`. 

**_The Algorithm_**

A-star search is an algorithm for pathplaning and graph reversal. A-start starts from a specific node of a graph and find a path to a goal node with smallest cost. The cost estimation f(n) are consist of two parts: (1) the cost of moving from start to the current node g(n); (2) a heuristic that estimate the cost of the cheapest path from node n to the goal h(n). A-start ends when it reaches the goal or there is no paths eligible to be extended at frontiers.
