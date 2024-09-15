# Fibonacci Sequence Generator

This repository contains a Python script to generate the Fibonacci sequence up to a specified number of terms. It prompts the user for a positive integer and prints the Fibonacci sequence up to that number.

## How It Works

The Fibonacci sequence is a series of numbers in which each number is the sum of the two preceding ones. The sequence starts from 0 and 1 by default. This script generates the sequence using a recursive function.

### Fibonacci Function

The main function `fibonacci(n)` calculates the Fibonacci number recursively:

```python
def fibonacci(n):
    if n == 1 or n == 0:
        return n
    else:
        return fibonacci(n-2) + fibonacci(n-1)
