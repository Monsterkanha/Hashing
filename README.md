# Hashing
Here, I will be posting some hashing techniques.

Techniques :- 
1. 2 sum when we require number of certain subarray that follow certain condition. We use 2 sum technique maintain a hashmap and in that use count to see indicate this much have
found this much time. 
Eg. Longest subarray having number of 1 one more than zero. We maintain hashmap and use index to map current number of zero.
At certain position check the least index of sum - 1 because just after than index we have got only 1 sum.
Here 1 sum indicate number of 1s are one more than no of 0s.

for sum use A[i] == 1 then increament else decrement by 1.

eg. Subarray with B odd number, subarray with given xor, etc.

2. Use of sliding window, move j to expand to reach to the condition and move i to restore that index.
