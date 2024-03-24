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
Program to find the square root for the given number(newton's method) using function.
Developed by: Pavithra.S
RegisterNumber:212223230147
def newton_square_root(number):
    if number<0:
        print("Square root is not defined for negative numbers")
    x=number/2.0
    while True:
        new_x=0.5*(x+number/x)
        if new_x==x:
            break
        x=new_x
    return x
num=int(input())
result=newton_square_root(num)
print(f"Square root of the number: {result}")
```

## Output:
![Screenshot 2024-03-24 200824](https://github.com/pavithraselvaraj30/Square-root-of-a-number/assets/149366880/16092791-3f24-4cdb-ba1b-8f9c6756161b)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
