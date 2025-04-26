# EX 1A Reverse a String
## DATE:26.04.2025
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1. Define a recursive function revstr that takes a string as input.
2.Check if the length of the string is zero (base case).
3.If true, return the string.
4.Otherwise, call revstr on the substring excluding the first character and concatenate the first character at the end.
5.Take input from the user and call the recursive function.
6.Print the result 
 

## Program:
```
/*
Program to implement Reverse a String
Developed by: HEMAPRASAD N
Register Number:  212222040054
*/

def fac(n):
    if n==1:
        return n
    else :
        return n* fac(n-1)
n=int(input())
print(f"Factorial of number {n} =",fac(n))
```

## Output:
![Screenshot 2025-04-26 150020](https://github.com/user-attachments/assets/71266a84-bf78-45f7-94b2-665d7e722b14)



## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
