# Topic: Operations on Functions

| Name       | Input              | Output              |
| ---------- | ------------------ | ------------------- |
| Sum        | $(f + g)(x)$       | $f(x) + g(x)$       |
| Difference | $(f - g)(x)$       | $f(x) - g(x)$       |
| Product    | $(fg)(x)$          | $f(x)g(x)$          |
| Quotient   | $(\frac{f}{g})(x)$ | $\frac{f(x)}{g(x)}$ |
| Composite  | $(f \circ g)(x)$   | $f(g(x))$           |

1. Given $f(x) = x^2 - 3x + 2$ $g(x) = 2x - 4$
- $(f + g)(x)$
> $= f(x) + g(x)$
> 
> $= x^2 - 3x + 2 + 2x - 4$
> 
> $= x^2 - x - 2$
- $(fg)(x)$
> $= f(x) \cdot g(x)$
> 
> $= (x^2 - 3x + 2) \cdot (2x - 4)$
> 
> $= (2x^3 - 6x^2 + 4x) + (-4x^2 + 12x - 8)$
> 
> $= 2x^3 - 10x^2 + 16x - 8$
- $(f / g)(x)$
> $= \frac{f(x)}{g(x)}$
> 
> $= \frac{x^2 - 3x + 2}{2x - 4}$
> 
> $= \frac{x^2 - 3x + 2}{2(x - 2)}$
> 
> $= \frac{(x - 1)(x - 2)}{2(x - 2)}$
> 
> $= \frac{(x - 1)}{2}$
- $f(g(x))$
> $= g(x)^2 - (3 * g(x)) + 2$
> 
> $= (2x - 4)^2 - 3(2x - 4) + 2$
> 
> $= (2x - 4)(2x - 4) - 6x + 12 + 2$
> 
> $= 4x^2 - 16x + 16 - 6x + 14$
> 
> $= 4x^2 - 22x + 30$
> 
> $= 2(2x^2 - 11x + 15)$
> 
> Factors of $30$ ($2 \cdot 15$) that add to $-11$ are $\set{ -5, -6 }$<br>
> $= 2(2x^2 - 5x - 6x + 15)$
> 
> $= 2(x(2x - 5) - 3(2x - 5))$
> 
> $= 2(x - 3)(2x - 5)$

2. Given $f(x) = \frac{4}{x}$, $g(x) = \frac{2x}{x - 2}$
- $(f - g)(x)$
> $= f(x) - g(x)$
> 
> $= \frac{4}{x} - \frac{2x}{x - 2}$
> 
> $= (\frac{4(x - 2)}{x(x - 2)}) - (\frac{x^2}{x(x - 2)})$
> 
> $= \frac{4(x - 2) - 2x^2}{x(x - 2)}$
> 
> $= \frac{4x - 8 - 2x^2}{x(x - 2)}$
> 
> $= \frac{-2(x^2 - 2x + 4)}{x(x - 2)}$

- $(fg)(1)$
> $= f(1)g(1)$
> 
> $= \frac{4}{1} \cdot \frac{2(1)}{1 - 2}$
> 
> $= 4(-2)$
> 
> $= -8$

- `f(g(x))`
> = 4 / g(x)
> = 4 / (\frac{2x}{x - 2})
> = 4(x - 2) / 2x
> = 2(x - 2) / x

- `g(f(x))`
> = 2(f(x)) / (f(x) - 2)
> = 2(4 / x) / ((4 / x) - 2)
> = 8 / x((4 / x) - 2)
> = 8 / (4 - 2x)
> = 8 / 2(2 - x)
> = 4 / (2 - x)

1. Use the graph to find each of the following:

- `(f + g)(-1)`
> = f(-1) + g(-1)
> = -2 + 1
> = -1

- `(fg)(4)`
> = f(4) * g(4)
> = 3 * 1
> = 3

- `(f - g)(-2)`
> = f(-2) - g(-2)
> = -1 + 1
> = 0

- `f(g(6))`
> = f(-1)
> = -2

- For which x-values is `f(x) >= g(x)`?
> `(-Infinity, -2]` `[+3, +8]` (intervals)

- For which x-values is `f(x) < g(x)`?
> `[-2, +3]` `[+8, +Infinity)`