# Triple product rule

Source: Math AA 5.2 Derivatives – Basic Rules (C. Nikolaidis), Q11
Date: 2026-11-05

## Problem
For a product of three functions, it holds:

$$(f \cdot g \cdot h)' = f' \cdot g \cdot h + f \cdot g' \cdot h + f \cdot g \cdot h'$$

Use this rule to find the derivative of $f(x) = x^5 e^x \ln x$.

## Working
$$f = x^5, \quad f' = 5x^4$$
$$g = e^x, \quad g' = e^x$$
$$h = \ln x, \quad h' = \tfrac{1}{x}$$

$$(f \cdot g \cdot h)' = 5x^4 e^x \ln x + x^5 e^x \ln x + x^5 e^x \cdot \tfrac{1}{x}$$

## Answer
$$f'(x) = 5x^4 e^x \ln x + x^5 e^x \ln x + x^4 e^x$$

## Notes
Apply the rule term by term: differentiate one factor at a time, keep the other two as they are. The last term simplifies because $x^5 \cdot \tfrac{1}{x} = x^4$.
