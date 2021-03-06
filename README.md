# Optimal Multiple-item Resource Allocation Subject to Network Effects

> Jinho Lee (jinhohl2@illinois.edu)

## Purposes:
- 1. Implement integer programming, linear optimization for convex probrem, and two rounding algorithms
- 2. Apply rounding algorithms to the continuous solution of convex programming and generate plots of objective values of different methods
- 3. Compare performances of two rounding algorithms with the classic integer programming
- 4. Implemment randomized descent method and compare its performance with the integer programming

## File Structures:
- integer_programming.py: Implementation of integer programming
- convex_optimization.py: Implementation of linear optimization of convex problem
- algorithm1.py: Implementation of the Kleinberg and Tados (KT) rounding algorithm
- algorithm2.py: Implementation of the Randomized Algorithm for Nonnegative Convex Externalities
- random_descent.py: Implementation of random descent optimization method
- plot.ipynb: Generate plots using implemented algorithms
- Random_Descent.ipynb: Generate plot of the random descent method
- algorithms_ipynb_descriptions: Detailed implementation of algorithms with step-by-step explanation in notebook format

## Environment Requirement
The code has been tested under Python 3.9.6. The required packages are as follows:

* scipy == 1.4.1
* numpy == 1.19.5
* pandas == 1.3.1
* matplotlib == 3.4.2
* cvxpy == 1.1.17

## Results:
![Alt text](/Plots/algorithm_12.PNG?raw=true "Algorithm 1 vs Algorithm 2")
- Algorithm 1 vs Algorithm 2
- 10 items
- number of agents increases from 10 to 50

![Alt text](/Plots/random_versus_ip.PNG?raw=true "Random Descent Method vs Integer Programming")
- Random Descent Method vs Integer Programming
- 20 items
- 40 agents

![Alt text](/Plots/random_over_iteration.PNG?raw=true "Performance of random descent algorithm over iteration")
- Performance of random descent algorithm over iteration
- 10 items
- number of agents increases from 10 to 50

