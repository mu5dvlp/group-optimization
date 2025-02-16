# About
This project solves optimization of grouping with weights.

## Hamiltonian
The hamiltonian is below:

$$
H = P_g \\sum_{v\\in V} \\left( \\sum_{g\\in G} x_{v,g}-1 \\right)^2  +  P_n \\sum_{g\\in G} \\left( \\sum_{v\\in V} x_{v,g}-n \\right)^2  -  \\sum_{g\\in G}\\sum_{(i,j)\\in V} x_{i,g}x_{j,g}w_{i,j}
$$

### Constraint of group count:

$P_g \\sum_{v\\in V} \\left( \\sum_{g\\in G} x_{v,g}-1 \\right)^2$

### Constraint of number of people:

$P_n \\sum_{g\\in G} \\left( \\sum_{v\\in V} x_{v,g}-n \\right)^2$

### Objective function

$-  \\sum_{g\\in G}\\sum_{(i,j)\\in V} x_{i,g}x_{j,g}w_{i,j}$

# Setup
You can import essential modules with:

`pip install -r requirements.txt`
