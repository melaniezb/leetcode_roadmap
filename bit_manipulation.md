Bit Manipulation
==
This section dives deep into tips and examples of the loved and hated topic: bit manipulation.
## Refresher
1. `n & (n - 1)` clears the least significant (rightmost) set bit, or 1-bit, of `n`.
2. __Arithmetic shift__: `>>` preserves the signedness of a number by extending the sign-bit (1 for negative, 0 for positive);
   __Logical shift__: `>>>` just adds 0s to the left after the shift.
3. `n ^ (-n)` returns the least significant (rightmost) 1-bit.
   
## Some Examples
- [136. Single Number](https://leetcode.com/problems/single-number/)
- [137. Single Number II](https://leetcode.com/problems/single-number-ii/)
- [260. Single Number III](https://leetcode.com/problems/single-number-iii/)
- [191. Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)
