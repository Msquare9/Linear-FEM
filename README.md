### Linear-FEM
A deep dive into bars and truss analysis
### Linear FEM Assignment

A deep dive into bars and truss analysis using the Finite Element Method (FEM), implemented in MATLAB.

---

#### Exercise 1 – Spring System
Analysed a 3-spring system with boundary conditions u₁, u₄ and load P. 
Computed the global stiffness matrix, nodal displacements, reaction forces, and force in spring 2.

---

#### Exercise 2 – Linear Elastic Bar
Solved an elastic bar problem  both analytically and numerically using FEM.
The FEM solution showed perfect agreement with the analytical result since the displacement field is linear.

---

#### Exercise 3 – 2D Truss Analysis

##### Problem Setup
A 10×10 2D truss grid with horizontal, vertical, and diagonal members.

![Problem Statement](images/Problem%20Statement.png)

##### 3.1 – Concentrated Load (10 kN at top-right node)
![Displaced Nodes](images/Displaced%20nodes.png)

##### 3.2 – Eigenvalue Analysis
![Eigenpairs Values](images/Eigenpairs%20Values.png)
![Eigenpairs Visualization](images/Eigenpairs%20Visualization.png)

##### 3.3 – Material Properties

![Truss Elongation](images/Truss%20Elongation%20force.png)
![Truss Shear](images/Truss%20shear%20force.png)


---

#### Tools Used
- MATLAB
- Finite Element Method (FEM)
