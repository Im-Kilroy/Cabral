# ⛵⚓ CABRAL Project
## Resume

This project idea came to me while I was working for a small business whose main activity involved transportation. They wanted to determine the best routes for their operations, considering factors such as **fuel consumption, travel time, and, most importantly, overall cost**.

I researched several algorithms and came across the **Traveling Salesman Problem (TSP)**, a well-known combinatorial optimization problem in which the goal is to find the shortest possible route that visits a set of locations exactly once and returns to the starting point.

There are several approaches to solving the TSP. For this project, I chose **Simulated Annealing (SA)**, a probabilistic optimization technique inspired by the physical process of annealing in metallurgy. The algorithm explores different possible solutions and can occasionally accept worse solutions in order to escape local optimal, gradually becoming more selective as the optimization progresses.

The name <b>CABRAL</b> is derived from **Pedro Álvares Cabral**, the Portuguese explorer who commanded the fleet that reached the coast of Brazil in **1500**, making him one of the most important figures associated with the beginning of Portuguese exploration and colonization in Brazil.


<br>
<br>

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1Jl1Qc08TFaeoqZFceq6ypMS9XiwwcwAY" width="400">
  <br>
  <sub>Armada de Cabral</sub>
</p>


## Features 

In this software, you can select **multiple locations** and calculate a route that visits all of them, following the general idea of the TSP. The program also allows specific parameters to be configured in order to influence the optimization process.

In addition to Simulated Annealing, I implemented the **A\* (A-star) algorithm** to find the best route between two points. A\* is a heuristic pathfinding and graph-search algorithm that can be viewed as an extension of Dijkstra's algorithm: when the heuristic is set to zero, A\* behaves like Dijkstra's algorithm. By using an appropriate heuristic, A\* can search for a low-cost path more efficiently.
