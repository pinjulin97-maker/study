# Derivative of tan x, gradients in geometric sequence

Source: Math AA 5.2 Derivatives – Basic Rules (C. Nikolaidis), Q18
Date: 2026-11-05

## Problem
Let $f(x) = \tan x$.

(a) Show that $f'(x) = \dfrac{1}{\cos^2 x}$.

(b) Show that the gradients of the curve of $f(x)$ at $x = 0$, $x = \dfrac{\pi}{4}$ and $x = \dfrac{\pi}{3}$ are in geometric sequence.

## Working
**(a)** Write $\tan x = \dfrac{\sin x}{\cos x}$ and use the quotient rule:

$$f'(x) = \frac{\cos x \cdot \cos x + \sin x \cdot \sin x}{\cos^2 x} = \frac{\sin^2 x + \cos^2 x}{\cos^2 x} = \frac{1}{\cos^2 x}$$

**(b)** Evaluate the gradient at each point:

$$\frac{1}{\cos^2 0} = 1$$
$$\frac{1}{\cos^2 \frac{\pi}{4}} = \frac{1}{\left(\frac{\sqrt{2}}{2}\right)^2} = \frac{1}{\tfrac{1}{2}} = 2$$
$$\frac{1}{\cos^2 \frac{\pi}{3}} = \frac{1}{\left(\frac{1}{2}\right)^2} = \frac{1}{\tfrac{1}{4}} = 4$$

## Answer
The gradients are $1,\ 2,\ 4$ — a geometric sequence with common ratio $2$.

## Notes
$\sin^2 x + \cos^2 x = 1$ collapses the numerator in part (a). For part (b), "geometric sequence" just means each term is a constant multiple of the previous one: $1 \to 2 \to 4$ multiplies by $2$ each step.
