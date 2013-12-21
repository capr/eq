---
project: eq
title:   eq3
tagline: 3rd degree equation solver
---

v1.0 | Lua 5.1, Lua 5.2, LuaJIT 2

## `local solve_equation3 = require'eq3'`

## `solve_equation3(a, b, c, d[, epsilon]) -> [s1[, s2[, s3]]]`

Solve the [3rd degree equation][1] *ax^3^ + bx^2^ + cx + d* and return all the real solutions.

Epsilon controls the precision at which the solver converges on close enough solutions.

----
See also: [eq2](eq2.html)

[1]: http://en.wikipedia.org/wiki/Cubic_function
