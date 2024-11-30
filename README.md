# genetic-tsp
This program tries to find near optimal solutions to the Travelling Salesman Problem. This famous problem is NP-hard, so finding the most optimal solution takes factorial order time. Attempting to use heuristics to guide the choice of solution will likely lead to local minimas in the search space. 
Thus the idea is to use probabilistic algorithms for moving through the search space. The program will have the ability to jump out of local minima and hopefully we get to the global minima or atleast something very near to it. 
Genetic Algorithm is one such powerful algorithm, which uses natural selection inspired criteria to pick the next random solutions. 
We use it to solve the problem for a randomly generated dataset of 25 cities. Solving this optimally on a home pc requires time of the order of the age of universe, but reasonably optimal solutions can be obtained in a few hours. We explore various choice of parameters to understand how to improve this search.
