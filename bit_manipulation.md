## Bit Manipulation
**A Refresher**
1. `n & (n - 1)` clears the least significant (rightmost) 1-bit of `n`
2. Arithmetic shift `>>` preserves the signedness of a number by extending the sign-bit (1 for negative, 0 for positive);
   Logical shift `>>>` just adds 0s to the left after the shift.
   
**Some Examples**
- [136. Single Number](https://leetcode.com/problems/single-number/)
- [137. Single Number II](https://leetcode.com/problems/single-number-ii/)
- [260. Single Number III](https://leetcode.com/problems/single-number-iii/)
- [191. Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)
