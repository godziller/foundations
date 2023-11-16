# Questions and Answers

## Question 4

```
The following is an attempt to write an algorithm for the same task as Q2. What is wrong with it?
Input: A list of numbers
1. m <- first number in list
2. while there are still numbers after m
3.
if m > next number after m
4.
m <- next number after m
5. return m
```
### Answer

This algorithm is wrong because, while m is set to the first number - 4 in step 1, in step 2 the while condition will loop infinitely because all number after m (4) are 4,5,6,7....infinity
So this algorithm is non-terminaniting, ergo this is the error.
