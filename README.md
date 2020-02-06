<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#Learning-outcomes" data-toc-modified-id="Learning-outcomes-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Learning outcomes</a></span></li><li><span><a href="#Description-of-content" data-toc-modified-id="Description-of-content-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>Description of content</a></span></li><li><span><a href="#Reading-list" data-toc-modified-id="Reading-list-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>Reading list</a></span></li><li><span><a href="#Lecture-plan" data-toc-modified-id="Lecture-plan-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>Lecture plan</a></span></li></ul></div>


# Numerical Methods

A course on numerical methods covering:

* Introductory numerical analysis (interpolation, quadrature, etc)
* Numerical linear algebra (solving linear systems, methods for solving nonlinear systems)
* Numerical solution of ODEs (including time-stepping methods suitable for unsteady PDEs)
* Numerical solution of PDEs (approaches to discretise the spatial dimensions: the finite difference, volume and element methods)

<!-- #region -->
## Learning outcomes

On successful completion of this module, students will be able to:

1. Describe and implement numerical methods to solve typical (algebraic/ differential, linear/non-linear) equations, including ordinary differential equations (ODEs), partial differential equations (PDEs) and linear/non-linear systems.
2. Contrast the fundamental properties of different numerical algorithms: complexity, stability, accuracy, consistency, convergence, and boundedness.
3. Critique the key numerical approaches for the solution of problems from continuum mechanics.
4. Apply knowledge of spatial and temporal discretisation methods and their properties.

## Description of content

This module will operate at the interface of the Modelling Dynamical Processes module (ACSE-2) introducing key physics and mathematical underpinning, i.e. the continuous world, and the Modern Programming Methods module (ACSE-1) for how to interact with computers.  It will also provide knowledge of key algorithms that will be used in Applying Computational Science (ACSE-4).

This module will introduce the key concepts and algorithms required to represent the continuous world on discrete computers.  Introductory fundamental concepts that are common across all numerical methods will be introduced:  stability, accuracy, consistency, convergence, boundedness, conservation, etc.

Algorithms from numerical linear algebra and for the numerical solution of ODEs (implicit and explicit) and PDEs will be introduced. These will be motivated by the physical problems introduced in the Continuum Mechanics module, and looking ahead to future modules (and their associated coursework) as well as the major projects (module ACSE-9).

## Reading list

* Practical Numerical Methods with Python, Lorena Barba, Ian Hawke and Bernard Knaepen \[A MOOC with IPython Notebooks available at: [https://github.com/numerical-mooc/numerical-mooc/wiki](https://github.com/numerical-mooc/numerical-mooc/wiki)\] 
* Numerical Methods in Engineering with Python 3, 3rd Edition, Jaan Kiusalaas
* Fundamentals of Engineering Numerical Analysis, 2nd Edition, Parviz Moin
* A First Course in the Numerical Analysis of Differential Equations, 2nd Edition, Arieh Iserles
* Numerical Linear Algebra, Lloyd N. Trefethen, David Bau III 
* Finite Difference Methods for Ordinary and Partial Differential Equations: Steady-State and Time-dependent Problems, Randall LeVeque
* Finite Volume Methods for Hyperbolic Problems, Randall LeVeque
* Finite Elements and Fast Iterative Solvers: with Applications in Incompressible Fluid Dynamics, 2nd Edition,  Howard Elman, David Silvester and Andy Wathen
* Computational Methods for Fluid Dynamics, 3rd Edition, Joel Ferziger and Milovan Peric

## Lecture plan


1. Mon 18 Nov. Interpolation and curve-fitting

2. Tue 19 Nov. Numerical integration (or quadrature)

3. Thu 21 Nov. Numerical linear solvers (e.g. Gaussian elimination)

4. Fri 22 Nov. Nonlinear solvers (e.g. Newton's method)

5. Mon 25 Nov. ODEs 1 (simple time-stepping schemes; stability

6. Tue 26 Nov. ODEs 2 (more advanced time-steppers - Runge-Kutta and linear multistep methods)

7. Thu 28 Nov. Numerical differentiation and BVPs (finite differences; shooting method)

8. Fri 29 Nov. PDEs 1 (1D problems; advection and diffusion; stability)

9. Mon 02 Dec. PDEs 2 (2D problems; incompressible computational fluid dynamics (CFD))

10. Tue 03 Dec. FVM (finite volume methods; hyperbolic PDEs and compressible CFD)

11. Thu 05 Dec. FEM 1 (finite element methods; weak forms, assembly and implementation)

12. Fri 06 Dec. FEM 2 (finite element methods; 2D problems and computational fluid dynamics)
<!-- #endregion -->

```python

```
