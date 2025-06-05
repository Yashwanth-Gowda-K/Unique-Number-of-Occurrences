# Unique-Number-of-Occurrences


Problem Description
Given an array of integers arr, return True if the number of occurrences of each value is unique, otherwise return False.

Example
Input: arr = [1,2,2,1,1,3]
Output: True

Explanation:
- 1 appears 3 times
- 2 appears 2 times
- 3 appears 1 time
All counts are unique (3, 2, 1).

Solution Approaches
1. Frequency Dictionary (Optimal)
Time Complexity: O(n)
Space Complexity: O(n)

Approach:
Count occurrences using a dictionary
Compare length of frequency values vs unique frequency values

2. Counter One-Liner (Concise)
Time Complexity: O(n)
Space Complexity: O(n)
Uses Python's collections.Counter for clean implementation
