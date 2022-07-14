****Two Sum DSA****
-
> Given an array of integers nums and an integer target, create a function that returns the two
numbers such that they add up to target.
You may assume that each input would have exactly one solution, and you may not use the
same element twice.

- Example:
Input: nums = [2,7,11,15], target = 9
Output: [2,7]
Explanation: Because 2 + 7 == 9, we return [2, 7]

## Thoughts Process
- Assuming that the input is an array of integers within considerable memory size.
- Assuming the input of arrays is minimal. Ignore the time complexity of the algorithm (O(n**2)).
- Iterate twice, starting from the first iteration at index 0 and the second iteration at index 1. If the sum of the two numbers is equal to the target, return the two numbers.
- Return the answer in any order.
- Return null if there is no answer.
