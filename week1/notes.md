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

## Course topics

1. Vocabulary for design and analysis of algorithms
- big "oh" notation

2. Divide and conquer algorithm design paradigm
- integer multiplication, sorting, matrix mul, closest pair
- general analysis methods ("master method/theorem")

3. Randomization in algorithm design
- will apply to: quicksort, primality testing, graph partioning, hashing
- allowing randomizing leads to simpler and more practical solutions

4. Primitives for reasoning about graphs
- connectivity information, shortest paths, structure of information and social networks

5. Use and implementation of data structures
- heaps, balanced binary search trees, hashing and some variants (e.g. bloom filters)

## Topics in Sequel Course (part 2)

1. Greedy algorithm design paradigm

2. Dynamic programming algorithm design paradigm

3. NP-complete problems and what to do about them

4. Fast heuristics/ fast exact algorithms

5. Exact algorithms that beat brute-force search

## Skills you'll learn

- 
