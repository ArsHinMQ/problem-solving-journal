- Link: https://neetcode.io/problems/first-missing-positive
- Difficulity: Hard

## 2026, Feb 17
So this was actually a challenging one; a few things that I need to remember:
- Negative numbers do not matter in this problem, their value is 0
- Negative numbers and the input itself can be used as a markers
- We need to try to use the input both as a hashmap and in a way that we don't change the original data
- In worst case scenario, the smallest int that is not in the array would be len(nums) + 1; range(0, len(nums) + 1)