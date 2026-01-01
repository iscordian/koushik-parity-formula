# Koushik’s Parity Formula


## Overview


While exploring number patterns, I studied a sequence that behaves differently at odd and even positions.
Instead of writing two separate rules, I derived a single algebraic expression that captures both behaviors.


I refer to this result as **Koushik’s Parity Formula**, based on my independent discovery of the method.


---


## The Sequence


1, 4, 3, 10, 5, 16, 7, 22, 9, ...


---


## Observation


- For odd values of `n`, the term equals `n`.
- For even values of `n`, the term follows the rule `3*n - 2`.


---


## One-Line Formula


The sequence can be written using a single formula based on parity:


  *a(n) = ((1 + (-1)^(n+1)) / 2) * n + ((1 + (-1)^n) / 2) * (3*n - 2)*
  
  ![Parity-Formula](https://github.com/user-attachments/assets/e02454e5-1865-4c3b-a1b6-812205e19d18)


This expression automatically switches behavior depending on whether `n` is odd or even.

---

## Verification

- For `n = 5` (odd):  
  `a(5) = 5`

- For `n = 6` (even):  
  `a(6) = 3*6 - 2 = 16`

- For `n = 8` (even):  
  `a(8) = 22`

The formula correctly reproduces the sequence.

---

## Why This Is Useful

This formula shows how odd–even (parity) behavior can be encoded into algebra using powers of `-1`.
It provides a compact way to represent sequences that follow alternating rules.

---

## Naming

This method is referred to as:

**Koushik’s Parity Formula (Independent Discovery)**

---

## Author Note

I am an 8th-grade student exploring mathematics through pattern discovery and formula construction.
This work is shared for educational and exploratory purposes.

