# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Aswinth T
RegisterNumber:  212222230015
def newton_method(n,ni=100):
    a=float(n)
    for i in range(ni):
        n=0.5*(n+a/n)
    return n
    
a=int(input())
print("Square root of the number:",newton_method(a))
*/
```

## Output:
![image](https://github.com/Aswinth21/Square-root-of-a-number/assets/120236638/95ce748e-03d3-448e-9fce-9723214cde6d)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
