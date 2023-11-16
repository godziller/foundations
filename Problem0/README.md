# Problem 0: Introductory Algo and Problem Solving: Questions and Answers

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

## Question 5
```
Write an algorithm which takes three separate pieces of input (h,m,s), representing a length of time
in hours, minutes and seconds, and produces as output the same length of time in seconds.
```

### Answer

- **Reminder - An Algo is _ORDERED_ , _DETERMINISTIC_, _EXECUTABLE_ and _TERMINATING_**
- Assumption - even though the question mentions hours etc - we assume each HH:MM:SS represets cumulative duration, not clock time to be reset post 24hrs for example.

```
Input: three seperate integers - represeting HH:MM:SS
    totalSeconds <-0
    hh <- the input integer represeting HH
    mm <- the input integer represeting MM
    ss <- the input integer repsenting SS

    totalSeconds <- totalSeconds + (HH*3600)
    totalSeconds <- totalSeconds + (MM*60)
    totalSeconds <- totalSeconds + ss
    return totalSeconds

```
