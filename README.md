# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
# Program to find gcd of two numbers
# Create by: V.SREEVALSAN
# Register no: 23012962
def gcd():
    a,b=int(input()),int(input())
    while b:
        a,b=b,a%b
    print("GCD of two numbers is:",a)    
```

## Output:
![Alt text](image.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
