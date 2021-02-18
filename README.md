## Overview

A simple pure python backtracking based constraint satisfaction solver.

The code borrows from: 
> 2018 David Kopec, Classic Computer Science Problems in Python: Chapter 3
>
> A large number of problems that computational tools are used to solve can be broadly categorized as constraint-satisfaction problems (CSPs). CSPs are composed of variables with possible values that fall into ranges known as domains. Constraints between the variables must be satisfied in order for constraint-satisfaction problems to be solved. Those three core concepts—variables, domains, and constraints—are simple to understand, and their generality underlies the wide applicability of constraint-satisfaction problem solving.

### Constraint satisfaction problems
In artificial intelligence and operations research, 
[constraint satisfaction](https://en.wikipedia.org/wiki/Constraint_satisfaction)
is the process of finding a solution to a set of constraints that impose conditions that the variables must satisfy. A solution is therefore a set of values for the variables that satisfies all constraints—that is, a point in the feasible region.

The techniques used in constraint satisfaction depend on the kind of constraints being considered. Often used are constraints on a finite domain, to the point that constraint satisfaction problems are typically identified with problems based on constraints on a finite domain. Such problems are usually solved via search, in particular a form of [backtracking](https://en.wikipedia.org/wiki/Backtracking) 
or local search. 
[Constraint propagation](https://en.wikipedia.org/wiki/Local_consistency) 
are other methods used on such problems; most of them are incomplete in general, that is, they may solve the problem or prove it unsatisfiable, but not always. Constraint propagation methods are also used in conjunction with search to make a given problem simpler to solve. Other considered kinds of constraints are on real or rational numbers; solving problems on these constraints is done via variable elimination or the 
[simplex algorithm](https://en.wikipedia.org/wiki/Simplex_algorithm) (see also [Google OR Tools](https://developers.google.com/optimization/introduction/overview)).

**Constraint satisfaction problems (CSPs)** are mathematical questions defined as a set of objects whose state must satisfy a number of constraints or limitations. CSPs represent the entities in a problem as a homogeneous collection of finite constraints over variables, which is solved by constraint satisfaction methods. CSPs are the subject of intense research in both artificial intelligence and [operations research](https://en.wikipedia.org/wiki/Operations_research), since the regularity in their formulation provides a common basis to analyze and solve problems of many seemingly unrelated families.
