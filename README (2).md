# Dynamic Programming

Dynamic Programming is a powerful algorithmic technique used to solve problems by breaking them down into smaller subproblems and efficiently solving and storing the solutions to those subproblems. It is particularly useful for optimization problems where you need to find the best solution among a set of possible solutions.

### Key Concepts:

1. **Overlapping Subproblems:** In dynamic programming, a problem is broken down into smaller subproblems. Importantly, these subproblems often overlap, meaning that the same subproblem is solved multiple times. Dynamic programming optimizes this by solving each subproblem only once and storing its solution for future use.

2. **Optimal Substructure:** Dynamic programming problems exhibit optimal substructure, which means that the optimal solution to the larger problem can be constructed from the optimal solutions of its smaller subproblems. This property is essential for dynamic programming to work effectively.

3. **Memoization:** Memoization involves storing the results of expensive function calls and returning the cached result when the same inputs occur again. In dynamic programming, memoization can be applied by storing the solutions to subproblems in a data structure (like an array or a dictionary) to avoid redundant calculations.

4. **Tabulation:** Tabulation is an alternative approach to dynamic programming that involves building a table (usually a 2D array) to store solutions to subproblems in a bottom-up manner. This avoids recursion and usually uses less memory compared to memoization.

### Steps to Solve Dynamic Programming Problems:

1. **Identify the problem:** Determine whether the problem can be solved using dynamic programming by checking for overlapping subproblems and optimal substructure.

2. **Define the recurrence relation:** Express the problem's solution in terms of solutions to its smaller subproblems. This recursive relationship forms the foundation of dynamic programming.

3. **Choose a solving method:** Decide whether to use top-down (memoization) or bottom-up (tabulation) approach to implement dynamic programming.

4. **Implement the solution:** Write the code based on the recurrence relation using the chosen approach. If using memoization, ensure to store and retrieve solutions from a cache. If using tabulation, construct the table iteratively.

5. **Optimize and handle base cases:** Ensure that the solution handles base cases effectively, preventing infinite recursion or incorrect results. Optimize the solution by avoiding redundant computations.

6. **Fill the table (for tabulation):** If using tabulation, fill the table iteratively, starting from the smallest subproblems and working up to the original problem.

7. **Retrieve the solution:** Once the table is filled (for tabulation) or the memoization cache is populated, retrieve the solution to the original problem as stored in the table or cache.

### Common Problems Solved Using Dynamic Programming:

- Fibonacci Sequence
- Longest Common Subsequence
- Knapsack Problem
- Shortest Path in Graphs
- Matrix Chain Multiplication
- Coin Change Problem

Dynamic programming can significantly improve the efficiency of algorithmic solutions, making it a fundamental technique in computer science and problem-solving.

## How to identify a DP question?

### Repeated Subproblems:
Watch for patterns where the same problem is solved multiple times, indicating potential redundancy.

### Solution Reuse: 
Identify opportunities to store and reuse solutions to subproblems, saving time and effort.

###  Subproblem Relationships: 
Recognize how solutions to smaller subproblems contribute to solving the overall problem.

### Optimal Substructure: 
Look for problems where the optimal solution relies on optimal solutions to subproblems.

### Memoization/Tabulation: 
Notice if the problem involves caching solutions (memoization) or building solutions iteratively (tabulation).

### Optimization Focus: 
Dynamic programming often addresses optimization problems where the best solution must be found among possibilities.

### Classic Examples: 
Familiarize yourself with classic dynamic programming problems to recognize similar patterns.

### Progressive Complexity: 
Expect the problem to gradually increase in complexity as you solve smaller instances.


## Dynamic Programming Interview Questions
### 1. Fibonacci Sequence
Question: Calculate the nth number in the Fibonacci sequence using dynamic programming.

Hint: Use an array to store previously calculated Fibonacci numbers to avoid redundant calculations.

### 2. Longest Common Subsequence
Question: Given two strings, find the length of their longest common subsequence.

Hint: Create a 2D array to store the lengths of common subsequences between different prefixes of the two strings.

### 3. 0/1 Knapsack Problem
Question: Given a set of items with weights and values, determine the maximum value that can be obtained by selecting a subset of items without exceeding a given weight limit.

Hint: Create a 2D array where rows represent items and columns represent different weights. Fill in the array based on whether including an item at a given weight is optimal.

### 4. Coin Change Problem
Question: Given a set of coin denominations and a target amount, find the minimum number of coins needed to make up that amount.

Hint: Create an array to store the minimum number of coins needed for different amounts, building up from smaller amounts to the target.

### 5. Edit Distance
Question: Given two strings, determine the minimum number of operations (insertions, deletions, substitutions) needed to convert one string into the other.

Hint: Create a 2D array to represent edit distances between substrings of the two strings.

### 6. Maximum Subarray Sum
Question: Find the contiguous subarray within an array (containing at least one number) that has the largest sum.

Hint: Use Kadane's algorithm to efficiently find the maximum subarray sum.

### 7. Unique Paths in a Grid
Question: Given a grid, find the number of unique paths from the top-left corner to the bottom-right corner, moving only down and right.

Hint: Use a 2D array to store the number of paths for each cell, building up from the starting point.

### 8. Rod Cutting Problem
Question: Given a rod of length n and a list of prices for different rod lengths, determine the maximum revenue that can be obtained by cutting and selling the rod.

Hint: Use an array to store the maximum revenue for different rod lengths, based on optimal cuts.

### 9. Palindromic Substrings
Question: Find the total number of palindromic substrings in a given string.

Hint: Create a 2D array to keep track of whether substrings are palindromic or not.

### 10. Word Break Problem
Question: Given a string and a dictionary of words, determine whether the string can be segmented into space-separated words from the dictionary.

Hint: Use dynamic programming to track whether substrings can be segmented.


#### Here's a list of 30 important dynamic programming questions that cover a wide range of problem types and concepts:

1. Fibonacci Sequence
2. Longest Common Subsequence
3. 0/1 Knapsack Problem
4. Coin Change Problem
5. Edit Distance
6. Maximum Subarray Sum (Kadane's Algorithm)
7. Unique Paths in a Grid
8. Rod Cutting Problem
9. Palindromic Substrings
10. Word Break Problem
11. Longest Increasing Subsequence
12. Maximum Product Subarray
13. Paint House Problem
14. Climbing Stairs
15. Minimum Path Sum in Grid
16. Combination Sum
17. House Robber Problem
18. Subarray Sum Equals K
19. Largest Divisible Subset
20. Partition Equal Subset Sum
21. Distinct Subsequences
22. Regular Expression Matching
23. Interleaving String
24. Decode Ways
25. Shortest Common Supersequence
26. Russian Doll Envelopes
27. Minimum Cost to Reach Destination
28. Count Palindromic Subsequences
29. Best Time to Buy and Sell Stock (with cooldown)
30. Longest Palindromic Subsequence

You can also refer to Love Babbar DSA sheet and striver DSA sheet along with GFG articles and Aditya Vikram playlist on youtube.