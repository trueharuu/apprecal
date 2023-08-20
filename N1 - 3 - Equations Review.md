# Topic: Equation Review

## Solve the following equations for x.

1. `(3x - 2) - (1 / 4)(x - 5) = 10`
> ```rs
> // Turn multiplication with fraction into division
> (3x - 2) - ((x - 5) / 4) = 10
> // Give (3x - 2) a denominator of 4 by multiplying both sides
> (4(3x - 2) / 4) - ((x - 5) / 4) = 10
> // Join fractions
> (4(3x - 2) - (x - 5)) / 4 = 10
> // Factor out -1 from `-(x - 5)`
> (4(3x - 2) + -x + 5) / 4 = 10
> // Distribute constant term `4`
> (12x - 8 + -x + 5) / 4 = 10
> // Join terms
> (11x - 3) / 4 = 10
> // Multiply both sides by 4
> 11x - 3 = 40
> // Add 3 to both sides
> 11x = 43
> // Divide both sides by 11
> x = 43 / 11
> ```

2. `5x² + 3x - 2 = 0`
> ```rs
> // 5 * -2 = -10, factors of -10 that add up to 3 are { 5, -2 }
> = 5x² + 5x - 2x - 2 = 0
> // Rearrange
> = 5x - 2 + 5x² - 2x = 0
> // Factor by grouping
> = (5x - 2) + (5x² - 2x) = 0
> = (5x - 2) + x(5x - 2) = 0
> = (x + 1)(5x - 2) = 0
> // Split factors
> = x = { -1, 2 / 5 }
> ```

3. `3x² - 48 = 0`
> ```rs
> // Factor out `3`
> = 3(x² - 16) = 0
> // Difference of squares: a² - b² = (a + b)(a - b)
> = 3(x + 4)(x - 4) = 0
> // Divide both sides by `3`, removing it
> = (x + 4)(x - 4) = 0 // 0 / 3 = 0
> // Split factors
> = x = { 4, -4 }
> ```

4. `x² + 4x + 2 = 0`
> ```rs
> // Add 2 to both sides
> = x² + 4x + 4 = 2
> // Factors of 4 that add to 4 are { 2, 2 }
> = (x + 2)(x + 2) = 2
> = (x + 2)² = 2
> = x + 2 = ±sqrt(2)
> = x = ±sqrt(2) - 2
> ```

5. `9x² - 20 = 0`
> ```rs
> // Add 20
> = 9x² = 20
> = x² = 20 / 9
> = x = ±sqrt(20 / 9)
> = x = ±(sqrt(20) / sqrt(9))
> = x = ±(sqrt(20) / 3)
> = x = ±(2 * sqrt(5) / 3)
> ```

6. `2x³ - x² - 18x + 9 = 0`
> ```rs
> // Factor by grouping
> = (2x³ - x²) + (-18x + 9) = 0
> = x²(2x - 1) - 9(2x - 1) = 0
> = (x² - 9)(2x - 1) = 0
> // Difference of squares: a² - b² = (a + b)(a - b)
> = (x + 3)(x - 3)(2x - 1) = 0
> // Split factors
> = x = { ±3, +1 / 2 }
> ```

7. `x^4 = 2x² - 1`
> ```rs
> x^4 - 2x² + 1 = 0
> // y = x²
> = y² - 2y + 1 = 0
> // Factors of 1 that add up to -2 are { -1, -1 }
> (y - 1)(y - 1) = 0
> (y - 1)² = 0
> (x² - 1)² = 0
> // Difference of squares: a² - b² = (a + b)(a - b)
> (x + 1)² * (x - 1)² = 0
> (x + 1)(x + 1)(x - 1)(x - 1) = 0
> // Split factors
> = x = { +1, -1 }
> ```

## Solve for the specified variable

8. `A = (1/2)(bh)` for `h`
> ```rs
> A = (1/2)(bh)
> 2A = bh
> 2A/b = h
> ```

9. `ax + by = ab` for `b`
> ```rs
> = ax + by - ba = 0
> = ax + b(y - a) = 0
> b(y - a) = -ax
> b = -ax / (y - a)
> ```

