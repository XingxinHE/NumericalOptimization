# Numerical Optimization
People optimize.  This is a repo for my notes and exercise of Book Numerical Optimization by J. Nocedal, S.J. Wright



# Chapter 1 Introduction

Elements of optimization:package:

> `objective`: sth. need to be first defined with quantitative measure.
>
> `variable / unknown`: the characteristics of the system, which can optimize the objective
>
> `constraint` : the constraint of variables
>
> `modeling` : the process identifying objectives, variables, and constraints for a given problem
>
> `algorithm` : no universal one, but should find the tailored one related to the objective
>
> `optimality condition` : mathematical expression checking whether it is a good solution
>
> `sensitivity analysis` :	possible solution to improve



## 1.1 Mathematical Formulation

:star:(mathematical speaking) Optimization is the minimization / maximization of a function subject to constraints on its variables.

- $x$ - variable, unknown, parameters
- $f$ - objective function(scalar function) of $x$ 
- $c_i$ - constraint function(scalar function) of $x$ where must be satisfied


$$
min_{}\space f(x)\space\space\text{subject to}\space\space
        \begin{cases}
                c_i(x)=0, & i\in\epsilon\,,  \\
                c_i(x)\geq0, & i\in I\,.
        \end{cases}
$$
