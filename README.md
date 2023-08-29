# Linear-Optimization

This code demonstrates linear optimization concepts, shows how to model and solve linear programming problems using the CVXOPT library, and explores sensitivity analysis and duality in linear programming.

1. **Linear Optimization Example**:
   - Defines a linear optimization problem with constraints and an objective function.
   - Creates a visual representation of the constraints using matplotlib.

2. **Iso-Lines**:
   - Continues the visualization, adding iso-profit lines to the graph.

3. **Solving the Linear Program**:
   - Solves the linear program using the CVXOPT library.
   - Displays the optimal solution, primal objective value, and the objective value calculated using the optimal solution.

4. **Sensitivity Analysis**:
   - Adjusts the objective function in the linear program and solves it again to observe the change in the solution.
   - Updates the graph to show the new iso-profit line.

5. **Lego Furniture Production Problem**:
   - Presents a problem related to Lego furniture production.
   - Creates a graph to visualize the feasible region based on resource constraints.

6. **Model in Compact Form**:
   - Writes the Lego furniture production problem in compact form as a linear program.

7. **Solution**:
   - Solves the compact form linear program using the CVXOPT library.
   - Displays the optimal solution, primal objective value, and the objective value calculated using the optimal solution.

8. **Duality and Shadow Price**:
   - Introduces the concept of duality and shadow prices in linear programming.
   - Solves the dual problem for the Lego furniture production problem and displays results.
