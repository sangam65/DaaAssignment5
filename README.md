# Assignment-5
#### Team Members

|Enrollment No.|Name|GithubId|
|--------------|----|--------|
|IIT2019094|Sangam Kr Barnwal|sangam65|
|IIT2019095|Sanjana Reddy|sanjana179|
|IIT2019096|Riya Goyal|riyag0512|

**Group No-1**

**Faculty Name-** Dr. Rahul Kala

**Mentor Name-** Bulla Rajesh

---
## Problem Statement
Given a large binary string, find the length of substring which is having
maximum difference of number of 0s and number of 1s (number of 0s –
number of 1s). In case of all 1s print -1. Solve using Dynamic programming.

---
## How to use code

Download project
```
git clone https://github.com/sangam65/DaaAssignment5.git
```
Project Initialize
```
#Opening Assignment folder
cd DaaAssignment5

#Compiling The code
g++ daa.cpp -o output
```
---

Run the code
```
./output
```
Input
```
First line of input contains  s.
where s is the string  .

```
Ouput
```
Printing the maximum difference between no. of zeroes and no. of ones in the substring.
```
---
**Test case**

Test Case-1
```
Input:
1100
Output:
2
```

Test Case-2
```
Input:
1111111111
Output:
-1
```

Test Case-3
```
Input:
11100100100011
Output:
5
```

---
### Theory
Logic
```
We check for each character present in the string and update our variable called current_sum and max_sum.
```
Implementation
```
We will name a variable current_sum, which increases when the current character is '1' and decreases if current character is '0'. Then we check if current_sum is negative then we make it equal to 0 and we check whether it is greater than the variable called max-sum and if it is we update the value of max_sum to current_sum.
```
---
### Analysis

**Time Complexity**
```
For all the cases : o(n)
```
n is the size of the string and it is O(n) as we are iterating on the size of the string.
**Space Complexity**
```
For all the cases : o(1)
```

---
### References

GFG : Dynamic Programming and Kadane's Algorithm

Tutorials Point : Kadane's Algorithm
