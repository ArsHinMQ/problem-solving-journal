- Link: https://neetcode.io/problems/longest-consecutive-sequence
- Difficulity: Medium

## 2026, Feb 14
First, I solved this problem with converting it into a set, sorting it, and using a dict to count the duplicates; this solution has time complexity of `O(n log n)` because of the sort.
I knew the problem could be solved in `O(n)` time complexity, so I checked the solution section and saw that it's using a `set`, and I couldn't understand how `while (num + length) in nums` inside a loop still means this algorithem is running in O(n)? Turned out `sets` in python work similarly to `dicts`, meaning trying to find each number in the set will cost `O(1)` most of the times!
+ Even if I didn't know that, I could still solve this problem using a dict and it would still cost `O(n)` which is probably what I should do later.