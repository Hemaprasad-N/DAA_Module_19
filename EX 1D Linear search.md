# EX 1D Linear search
## DATE:26.04.2025
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1.Read an integer l and then take l string inputs into a list List.
2.Read the target string n to be searched.
3.Initialize a variable found as False.
4.Iterate through each element in List and compare with n. If a match is found, set found = True and break.
5.Print "Found" if found is True; otherwise, print "Not Found".
## Program:
```
/*
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: HEMAPRASAD N
Register Number:  212222040054
*/

def search(List,n):
    
    found = False
    for ele in List:
        if ele == n :
            found = True
            break
    if found :
        print("Found")
    else:
        print("Not Found")

l = int(input())
List = [str(input()) for _ in range(l)]
n = str(input())
```

## Output:
![437670361](https://github.com/user-attachments/assets/cf76a838-9c86-41f2-8716-2eb3fc39c10a)



## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
