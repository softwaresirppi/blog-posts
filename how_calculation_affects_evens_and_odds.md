**Numbers** could either be odd or even. Arithmetic operations we do like addition, subtraction, multiplication and division would have an effect on the number being even or odd. That's what we are going to study.<br> 
 
Even numbers are the numbers which are multiples of 2. Odd numbers are the numbers which are NOT multiples of 2. Odd numbers leave a remainder when its divided by 2.<br> 
 
Consider arbitrary integral constants a and b,<br> 
Even numbers have a form of 2a<br> 
Odd numbers have a form of 2a + 1<br> 
 
# Addition<br> 
 
## even + even<br> 
 
 = 2a + 2b<br> 
 = 2(a + b)<br> 
 = even<br> 
 
## even + odd<br> 
 
 = 2a + 2b + 1<br> 
 = 2(a + b) + 1<br> 
 = odd<br> 
 
## odd + odd<br> 
 
 = 2a + 1 + 2b + 1<br> 
 = 2 + 2a + 2b<br> 
 = 2(a + b + 1)<br> 
 = even<br> 
 
# Subtraction<br> 
 
We could leverage the fact that negative of an even is still even. The same goes for odd numbers. So Addition rules naturally apply for<br> 
Subtraction rules.<br> 
 
# Multiplication<br> 
 
## even * even<br> 
 
 = 2a * 2b<br> 
 = 4ab<br> 
 = 2(2ab)<br> 
 = even<br> 
 
## even * odd<br> 
 
 = 2a * (2b + 1)<br> 
 = 4ab + 2a = 2(2ab + a)<br> 
 = even<br> 
 
## odd * odd<br> 
 
 = (2a + 1) * (2b + 1)<br> 
 = 4ab + 2a + 2b + 1<br> 
 = 2(2ab + a + b) + 1<br> 
 = odd<br> 
 
# Division<br> 
 
Divisions become scary irrational fast. They cant be classified as even or odds. I'm skipping it because Its not the territory I'm are going to step in.<br> 
 
# Exponents<br> 
 
Exponents are just multiplications over and over again. So we could use the findings from above. **But it only works for positive non-zero n.**<br> 
 
## even ^ n<br> 
 
 = even * even * even * ... n times<br> 
 = even<br> 
 
## odd ^ n<br> 
 
 = odd * odd * odd * ... n times<br> 
 = odd<br> 
 
# Factorial<br> 
Factorial of a number is simply the product of the series from that number to 1. Hence it also contains 2 in the product chain. It makes it even! **But it only works when n is greater than 1.**<br> 
 
## n!<br> 
 = n * (n - 1) * (n - 2) * ... * 2 * 1<br> 
 = 2 (n * (n - 1) * (n - 2) * ... * 3 * 1)<br> 
 = its even<br> 

# Conclusion

| +    | even | odd  |
|------|------|------|
| even | even | odd  |
| odd  | odd  | even |

| -    | even | odd  |
|------|------|------|
| even | even | odd  |
| odd  | odd  | even |

| *    | even | odd  |
|------|------|------|
| even | even | even |
| odd  | even | odd  |

For non zero positive powers,

| ^    | even | odd  |
|------|------|------|
| even | even | even |
| odd  | odd  | odd  |

Factorials,

| n                  | n!   |
|--------------------|------|
| greater than 1     | even |
| not greater than 1 | odd  |
