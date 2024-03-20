# 🚀 Linear-Programming-Optimisation-with-Gurobi-in-Python
## 📝 Description
* The code demonstrates how to formulate and solve linear programming problems using the Gurobi optimization library in Python.
  
* It optimizes for maximizing profits based on given constraints and decision variables, first with a basic model and then with an extended model considering additional profit-related variables.

## 📝 Importing and Setup:-

* The code starts by installing the Gurobi Python package and importing necessary modules.
* It can be downloaded from https://pypi.org/project/gurobipy/#files 🔗

## 📝 First Linear Program:

### Decision variables: 
* Three variables (X1, X2, X3) representing quantities of certain items.
### Objective function:
* Maximize the expression 10*X1 + 4*X2.
### Constraints: 
* Three linear constraints (c1, c2, c3) are defined.
### Optimization:
*The model is solved to maximize the objective function.
### Output: 
* Objective function value and optimal values of decision variables are printed.-

## 📝 Second Linear Program:

*Additional decision variables (P1, P2, P3) are introduced representing profits under different scenarios.
### Objective function: 
* Maximize the sum of profits (0.33*(P1 + P2 + P3)).
### Constraints: 
* New constraints (c4 to c9) are added to relate profits to the quantities from the first problem and impose minimum profit requirements.
### Optimization: 
* The extended model is solved.
### Output: 
* Objective function value and optimal values of all decision variables are printed.

## 📖 Please go through [Linear-Portfolio-Optimization-HLD.pdf](https://github.com/Gauravonthemixx/Linear-Programming-Optimisation-with-Gurobi-in-Python/files/14659538/Linear-Portfolio-Optimization-HLD.pdf) for more info
