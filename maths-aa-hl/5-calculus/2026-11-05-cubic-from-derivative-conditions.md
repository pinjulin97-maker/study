# Reconstructing a cubic from f, f', f'' conditions

Source: Math AA 5.2 Derivatives – Basic Rules (C. Nikolaidis), Q25
Date: 2026-11-05

## Problem
Let $f$ be a cubic polynomial function. Given that $f(0) = 2$, $f'(0) = -3$, $f(1) = f'(1)$ and $f''(-1) = 6$, find $f(x)$.

## Working
Let $f(x) = ax^3 + bx^2 + cx + d$.

$$f(0) = d = 2$$
$$f'(x) = 3ax^2 + 2bx + c, \qquad f'(0) = c = -3$$

From $f(1) = f'(1)$:
$$a + b - 3 + 2 = 3a + 2b - 3 \;\Rightarrow\; 2 = 2a + b$$

From $f''(x) = 6ax + 2b$ and $f''(-1) = 6$:
$$-6a + 2b = 6 \;\Rightarrow\; b = 3 + 3a$$

Substitute into $2 = 2a + b$:
$$2 = 2a + (3 + 3a) = 5a + 3 \;\Rightarrow\; a = -\tfrac{1}{5}$$
$$b = 3 + 3\left(-\tfrac{1}{5}\right) = \tfrac{12}{5}$$

## Answer
$$f(x) = -\frac{x^3}{5} + \frac{12x^2}{5} - 3x + 2$$

## Notes
Each condition pins one unknown or gives one equation: $f(0)$ and $f'(0)$ give $d$ and $c$ directly; $f(1)=f'(1)$ and $f''(-1)=6$ give two equations in $a$ and $b$. Solve the $2\times2$ system last.
