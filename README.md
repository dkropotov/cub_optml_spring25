# CUB Optimization Methods in Machine Learning, Spring 2025

Optimization methods underlie in solution of many problems in computer science. In machine learning, one needs to solve an optimization problem during fitting of some prediction model on data, and efficiency in solving such optimization problems directly influences practical applicability of the correspondent machine learning approaches. This module aims to provide students with theoretical knowledge and practical skills in understanding both classic and recent continuous optimization methods (including optimization of non-convex functions) and important features in application of such methods for solving machine learning and deep learning problems. The module supposes a detailed discussion of practical aspects in implementation and usage of optimization routines. As the result of the module students will be able to choose and customize optimization method with better fit for their applied problems.

**Instructor**: Dmitry Kropotov

**Teaching assistant**: Maksim Nakhodnov

**Timetable**: the classes are on Wednesdays 14:15 - 17:00 in the classroom EH-4.

**Telegram chat for questions and discussion**: [link](https://t.me/+lg10Rx2criVjMzYy)

**Assignments**: All assignments are given and checked in the corresponding Teams space

## Course assessment

Assessment Component 1: written examination, Duration: 60 min, Weight: 50 %

Assessment Component 2: Practical assessments, Weight: 50 %

Completion: To pass this module, the examination of each module component must be passed with at least 45%.

## Exam

The written exam is planned to be offline on campus. Test exam from the previous year: [formulation](Materials/test_exam.pdf), [reference solution](Materials/test_exam_reference.pdf)

## Lectures

| Date | Number | Topic | Materials |
| :---: | :---: | --- | --- |
| 04.02.25 | 01 | Introduction to the course. Function classes for optimization. Finding Hessians using second differentials. Convergence speed of optimization algorithms. Non-exact one-dimensional optimization.	| NW, sections 3.1, 3.5 |
| 12.02.25 | 02 | Gradient Descent. Convergence speed for different function classes. Examples. Finite-difference methods.	| NW, sections 3.2, 3.3  |
| 19.02.25 | 03 | Newton method. Invariance to linear scaling. Global and local convergence. Matrix decompositions for solving linear systems. Hessian correction schemes.	| NW, sections 3.3, 3.4  |
| 26.02.25 | 04 | Conjugate Gradient method for solving linear systems, its convergence properties. Preconditioning. Non-linear CG.	| NW, sections 5.1, 5.2  |
| 05.03.25 | 05 | Hessian-Free Newton (Newton-cg), its convergence speed. Convex sets. Introduction to Quasi-Newton methods.	| NW, section 7.1; BV, section 2  |



## Literature
1. J. Nocedal, S. Wright. [Numerical Optimization](https://www.math.uci.edu/~qnie/Publications/NumericalOptimization.pdf). Springer, 2006.
1. S. Boyd, L. Vandenberghe. [Convex Optimization](https://stanford.edu/~boyd/cvxbook/). Cambridge University Press, 2004.
