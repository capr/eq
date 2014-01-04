---
project:     eq
title:       eq2
tagline:     2nd degree equation solver
category:    Math
---

v1.0 | Lua 5.1, Lua 5.2, LuaJIT 2

## `local solve_equation2 = require'eq2'`

## `solve_equation2(a, b, c[, epsilon]) -> [s1[, s2]]`

Solve the [2nd degree equation][1] *ax^2^ + bx + c* and return all the real solutions.

Epsilon controls the precision at which the solver converges on close enough solutions.

----
See also: [eq3](eq3.html)

[1]: http://en.wikipedia.org/wiki/Quadratic_equation
