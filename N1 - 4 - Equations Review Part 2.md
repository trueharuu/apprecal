# Topic: Equation Review Part 2

## Solve the following equations for x. State any values not in the domain of x.

1. `(6 / x) + (8 / (x + 5)) = 3`
> ```rs
> // Get a common denominator by multiplying both parts
> = (6(x + 5) / x(x + 5)) + (8x / x(x + 5)) = 3
> // Combine like terms
> = (6(x + 5) + 8x) / (x(x + 5)) = 3
> // Move `(x + 5)`
> = 6(x + 5) + 8x = 3x(x + 5)
> // Multiply terms
> = 6x + 30 + 8x = 3x² + 15x
> = 14x + 30 = 3x² + 15x
> = -3x² - 15x + 14x + 30 = 0
> = -3x² - x + 30 = 0
> // Factor out `-1`
> = -(3x² + x - 30) = 0
> // Products of `-90` that add to `1` are { -9, 10 }
> = -(10(x - 3) + 3x(x - 3)) = 0
> = (3x + 10)(x - 3) = 0
> // Split factors
> = x = { -10 / 3, +3 }
> = x ≠ { +0, -5 }
> ```

2. `((x + 2) / (x - 3)) = (30 / (x² - 9)) + (1 / (x + 3))`
> ```rs
> // Difference of squares: a² - b² = (a + b)(a - b)
> = ((x + 2) / (x - 3)) = (30 / (x + 3)(x - 3)) + (1 / (x + 3))
> // Multiply by `(x + 3)(x - 3)`
> = ((x + 2)(x + 3)(x - 3) / (x - 3)) = (30(x + 3)(x - 3) / (x + 3)(x - 3)) + (1(x + 3)(x - 3) / (x + 3))
> = (x + 2)(x + 3) = x + 27
> = x² + 5x + 6 = x + 27
> = x² + 4x - 21 = 0
> // Products of `-21` that add to `4` are { 7, -3 }
> = (x + 7)(x - 3) = 0
> // Split factors
> = x = -7 // +3 is removed as a root
> = x ≠ { +3, -3 }
> ```

## Solve the following equations for x.

3. `sqrt(x + 3) = 5`
> ```rs
> = x + 3 = +25
> = x = +22
> ```

4. `sqrt(4 - x) = 2 - x`
> ```rs
> = 4 - x = (2 - x)²
> = 4 - x = (2 - x)(2 - x)
> = 4 - x = 4 - 2x - 2x + x²
> = 4 - x = x² - 4x + 4 
> = x² - 5x = 0
> = x(x - 5) = 0
> // +5 is removed as a root as sqrt(4 - 5) = i, not in R
> = x = 0
> ```

5. `cbrt(3x - 1) + 4 = 0`
> ```rs
> = cbrt(3x - 1) = -4
> = 3x - 1 = -64
> = 3x = -63
> = x = -21
> ```

6. `|2x + 3| = 5`
> ```rs
> // Split into 2 equations
> = 2x + 3 = 5
>  -> 2x = 2
>  -> x = 1
> 
> = -2x - 3 = 5
>  -> -2x = 8
>  -> x = -4
>
> = x = { 1, -4 }
> ```

## Solve for the specified variable.

7. `1 / R = (1 / R₁) + (1 / R₂)`
> ```rs
> = 1 / R = (R₂ / R₁R₂) + (R₁ / R₁R₂)
> = 1 / R = ((R₁ + R₂) / R₁R₂)
> // Assuming R₁ ≠ 0 and R₂ ≠ 0
> = R = (R₁R₂ / (R₁ + R₂))
> ```
