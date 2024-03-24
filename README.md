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
```python
#Program to find the gcd of a given number using function
#Developed by: SANJAY M
#RegisterNumber: 212223230187


def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller = n2
    else:
        smaller = n1
    for i in range (1,smaller+1):
        if(n1%i==0 and n2%i==0):
           hcf=i
    print("GCD of two numbers is:",hcf) 
```

## Output:
![Screenshot 2024-03-24 101148](https://github.com/sanjayofficial2005/GCD-of-two-numbers/assets/148048602/bd6b7a01-697a-4b9d-85bb-46b0774802b6)

![Screenshot 2024-03-24 101208](https://github.com/sanjayofficial2005/GCD-of-two-numbers/assets/148048602/db1f7d04-6389-4996-b819-a3fb4ffa6b9c)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
