
# Exp.No:2e  
## SEB - FIND SUM OF SERIES

### AIM  

To write a Python program to find the sum of series 1!+2!+3!...+n!.

### ALGORITHM

1. Begin the program.  
2. Input a number n.
3. Define a factorial function:
   If num == 0, return 1.
   Else, return num * factorial(num-1) (recursive call).
4. Initialize total = 0.
5. For each i from 1 to n:
   Calculate factorial(i).
   Add it to total.
6. Print the total sum.
7. Terminate the program.

### PROGRAM
```

def factorial(num):
    if num==0:
        return 1
    else:
        return num* factorial(num-1)
def sum_of_factorial(n):
    total=0
    for i in range(1, n+1):
        total += factorial(i)
    return total
    
n=int(input())
result = sum_of_factorial(n)
print(f"The sum of the series =  {result}")

```
### OUTPUT

![image](https://github.com/user-attachments/assets/9e6850bd-7c8d-4688-8b55-8c075f8e1202)

### RESULT

Thus Python program to find the sum of series 1!+2!+3!...+n! was successfully created.
