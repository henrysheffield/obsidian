---
created: 2026-05-09
updated: 2026-05-09 15:19
tags:
  - review
  - flashcards
  - maths/polynomials
sr-due: 2026-10-10
sr-interval: 117
sr-ease: 310
---
## 1. Cubic Equations

### Strategy 1: Discriminant

Works for all cubic equations of the form $ax^3+bx^2+cx+d=0$

![[Number of solutions to Cubics and Quartics-1778304106037.webp]]

But even easier, in Mathematica, you can calculate using:

```
Discriminant[a*x^3 + b*x^2 + c*x + d, x]
```

### Strategy 2: Calculus

1. Find local minimum and maximum

| **Condition**             | **Visual Interpretation**                          | **Number of Real Roots**           |
| ------------------------- | -------------------------------------------------- | ---------------------------------- |
| $f(x_1) \cdot f(x_2) > 0$ | Both extrema are on the same side of the $x$-axis. | **1 Real Root**                    |
| $f(x_1) \cdot f(x_2) = 0$ | One of the extrema sits exactly on the $x$-axis.   | **2 Real Roots** (one is repeated) |
| $f(x_1) \cdot f(x_2) < 0$ | The extrema are on opposite sides of the $x$-axis. | **3 Real Roots**                   |
Number of solutions to a cubic if $f(x_{1)}\times f(x_{2}) > 0$ where $x_1$ and $x_2$ are stationary points? :: 1 Real root
<!--SR:!2026-07-07,17,323-->
Number of solutions to a cubic if $f(x_{1)}\times f(x_{2}) < 0$ where $x_1$ and $x_2$ are stationary points? :: 3 Real roots
<!--SR:!2026-07-08,18,323-->
Number of solutions to a cubic if $f(x_{1)}\times f(x_{2}) = 0$ where $x_1$ and $x_2$ are stationary points? :: 2 Real roots (though one is repeated e.g. $(x+1)^{2}(x+3)$)
<!--SR:!2026-07-07,17,323-->
### Example:

Find range of k so that $f(x)=2x^3-9x^2+12x-k$ has 3 real solutions? :: ![[Number of solutions to Cubics-1778965567272.webp]]
<!--SR:!2026-07-15,32,310-->