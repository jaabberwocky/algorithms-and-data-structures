# Notes for week 1

## Karatsuba Multiplication

There is a better way to multiply than long division.

**Input**: two integers x and y
**Output**: multiplication of x * y

x = 5678
y = 1234

a = 56; b=78; c=12; d=34;

**Steps**:
1. Compute a*c = 672
2. Compute b*d = 2652
3. Compute (a+b)(c+d) = 134.46 = 6164
4. Compute steps (3) - (2) - (1) = 2840


# Simpler recursive algorithm to multiplication
