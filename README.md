# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Define a function.
### Step 2:
Get the two numbers from the user.
### Step 3:
Compare the two values, to find the smaller number.
### Step 4:
Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: S.Jaiganesh
RegisterNumber: 212222240037
*/
def gcd():
    x=int(input())
    y=int(input())
    if x<y:
        small=x
    else:
        small=y
    for i in range(1,small+1):
        if(x%i==0 and y%i==0):
            gcd=i
    print("GCD of two numbers is:",gcd)        
```

## Output:
![Screenshot (93)](https://github.com/Jaiganesh235/GCD-of-two-numbers/assets/118657189/9221acce-58c2-4f41-9e83-0427c9cf082a)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
