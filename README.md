# CANTILEVER BEAM WITH SHEAR ALONG BOTTOM EDGE

**COURSE: ADVANCED SOLID MECHANICS (ES 621)**
**DEPARTMENT OF MECHANICAL ENGINEERING, M. TECH (2024-2026)**
**INDIAN INSTITUTE OF TECHNOLOGY GANDHINAGAR**
*NOVEMBER, 2024*

---

## Submitted by: Group 4
* RIAZ ALI MAMUD (24250055)
* APRATIM PANDEY (24250019)
* MAYANK AWASTHI (24250054)
* SOHAN KUMAR PRADHAN (24250091)
* SIVAM BEHERA (24250090)

---

## 1. PROBLEM STATEMENT
To analyze the stress distribution in a cantilever beam subjected to a uniform shear load along its bottom edge using a suitable **Airy’s stress function $\Psi$**.

---

## 2. METHODOLOGY & ASSUMPTIONS

### Assumptions
* The material of the beam is linearly elastic and follows Hooke’s law.
* The problem assumes a **plane stress condition**.
* Displacements are assumed to be small.
* Boundary conditions are idealized, with the beam perfectly fixed at $x = 0$.
* The material is assumed to be isotropic with a constant Young’s Modulus and Poisson’s ratio.

### Biharmonic Equation
The Airy's stress function $\Psi$ must satisfy the biharmonic equation (in the absence of body forces) for the compatibility of strains:

$$
\nabla^4 \Psi = \frac{\partial^4 \Psi}{\partial x^4} + 2 \frac{\partial^4 \Psi}{\partial x^2 \partial y^2} + \frac{\partial^4 \Psi}{\partial y^4} = 0
$$

### Stresses
The stress components are derived from the Airy's stress function as follows:
* $T_{xx} = \frac{\partial^2 \Psi}{\partial y^2}$
* $T_{yy} = \frac{\partial^2 \Psi}{\partial x^2}$
* $T_{xy} = -\frac{\partial^2 \Psi}{\partial x \partial y}$

The analysis involves finding a suitable $\Psi$, applying the boundary conditions to solve for unknown constants, and then calculating the final stress, strain, and displacement fields.

---

## 3. PLOTS FOR STRESS FIELD
Following contours were plotted for $c = 10$ and $L = 0.5$:

* **Fig 1: Stress contour of $T_{yy}$** (Found to be zero everywhere)
* **Fig 2: Stress contour of $T_{xx}$**
* **Fig 3: Stress contour of $T_{xy}$**

*(Note: To add your images, upload them to the repository and then add lines like `![Stress contour of Txx](figure_2.png)`)*

---

## Course Project Brief
> Each group must pick a problem relevant to the subject. For instance, you could pick a plane stress or a plane strain problem from any textbook (e.g. chapter 8 of Martin Sadd). You may also pick any other kind of problem that may or may not have been discussed in the class. Don’t pick a problem that is too trivial, or too difficult. It should be at a level where you can fully describe the problem, and its solution, in your presentation that will be limited to 7 minutes.
