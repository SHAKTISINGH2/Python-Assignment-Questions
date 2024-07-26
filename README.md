# Python Programs Collection

This repository contains various Python programs demonstrating basic and intermediate concepts.

## Table of Contents

1. [Sum and Product of First 10 Natural Numbers](#sum-and-product-of-first-10-natural-numbers)
2. [Electricity Bill Calculator](#electricity-bill-calculator)
3. [Numbers List and Cubes Divisible by 4 or 5](#numbers-list-and-cubes-divisible-by-4-or-5)
4. [Vowel Counter](#vowel-counter)

## Sum and Product of First 10 Natural Numbers

This program calculates the sum and product of the first 10 natural numbers using both `for` and `while` loops.

### Usage

Run the `sum_and_product.py` file to see the output.

```python
# sum_and_product.py

def sum_and_product_for_loop():
    sum_for = 0
    product_for = 1

    for i in range(1, 11):
        sum_for += i
        product_for *= i

    print("Using for loop:")
    print(f"Sum of first 10 natural numbers: {sum_for}")
    print(f"Product of first 10 natural numbers: {product_for}")

def sum_and_product_while_loop():
    sum_while = 0
    product_while = 1
    i = 1

    while i <= 10:
        sum_while += i
        product_while *= i
        i += 1

    print("Using while loop:")
    print(f"Sum of first 10 natural numbers: {sum_while}")
    print(f"Product of first 10 natural numbers: {product_while}")

if __name__ == "__main__":
    sum_and_product_for_loop()
    sum_and_product_while_loop()
