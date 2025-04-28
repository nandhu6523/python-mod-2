# Exp.No:2b  
## FUNCTIONS - SUM OF FIRST N NATURAL NUMBERS USING FUNCTION

### AIM  

To write a Python program to find the sum of first N Natural Numbers using function.

### ALGORITHM

1. Begin the program.  
2. Input a number n.
3. Initialize sum1 = 0.
4. While n > 0:
   Add n to sum1.
   Decrease n by 1.
5. Print sum1 as the sum of the first n natural numbers.
6. Terminate the program.

### PROGRAM
```


def sum(n):
    sum1 = 0
    while(n > 0):
        sum1=sum1+n
        n=n-1
    print("The sum of first n natural numbers is",sum1)
    
    
number=int(input())
sum(number)

```
### OUTPUT

![image](https://github.com/user-attachments/assets/d79973bd-a471-4b7d-8b77-935b93495f21)

### RESULT

Thus the Python program to find the sum of first N Natural Numbers using function was successfully created.

