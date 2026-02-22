# Perfect and Prime Number Pattern Finder

## Overview

This Python program analyzes numbers from **1 to 999** and determines whether each number is **perfect** or **prime**.  

After classifying each number, the program searches for a special pattern:

> Cases where a perfect number is immediately followed by a prime number.

The program stores information about each number and prints pairs that match this pattern.

### Example Output
6 7
28 29


---

## What the Program Does

- Loops through numbers from 1 to 999
- Finds all factors of each number
- Calculates the sum of proper divisors
- Determines whether each number is:
  - Perfect
  - Prime
- Stores results in a structured list
- Searches for and prints perfect–prime consecutive pairs

---

## Concepts I Used and Learned

As a high school student beginning to code in Python, this project helped me practice and understand several important programming concepts:

### 1. Loops
- `while` loops
- `for` loops
- Iterating through ranges

### 2. Conditionals
- `if`
- `elif`
- Boolean flags (`True` / `False`)

### 3. Lists
- Creating lists
- Appending values
- Nested lists (storing multiple pieces of information per number)
- Indexing lists

### 4. Modulus Operator (`%`)
Used to:
- Determine factors
- Check divisibility
- Identify prime numbers

### 5. Mathematical Concepts
- Factors
- Proper divisors
- Prime numbers
- Perfect numbers

### 6. Basic Algorithm Design
- Breaking a problem into logical steps
- Storing computed data
- Searching for patterns after processing data

---

## Definitions

**Prime Number:**  
A number with exactly two factors — 1 and itself.

**Perfect Number:**  
A number whose proper divisors add up to the number itself.

Example:
- 6 → 1 + 2 + 3 = 6 (Perfect)
- 7 → Prime

---

## Possible Improvements

Future improvements to this project could include:

- Optimizing factor checking (checking only up to √n)
- Improving prime detection efficiency
- Refactoring code into functions
- Improving performance for larger ranges

---

## Author

High school student learning Python and exploring number theory patterns.
