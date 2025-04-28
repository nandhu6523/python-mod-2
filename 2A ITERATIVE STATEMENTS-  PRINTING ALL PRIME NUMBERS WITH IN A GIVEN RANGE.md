# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING ALL PRIME NUMBERS WITH IN A GIVEN RANGE

###  Aim

To create a Python program for printing all prime numbers within a given range.

###  Algorithm

1. Begin the program.
2. Input an integer r.
3. For each number a from 2 to r:
   Set k = 0.
   For each number i from 2 to a // 2:
     If a % i == 0, increment k.
   If k == 0, print a (it is a prime number
7. Terminate the program.

### Program

```


r=int(input())
for a in range(2,r+1):
    k=0
    for i in range(2,a//2+1):
        if(a%i==0):
            k=k+1
    if(k<=0):
        print(a)

```
### OUTPUT

![image](https://github.com/user-attachments/assets/6e3379f1-62f9-4f81-8b9b-d73ccbc7ab03)

### RESULT

Thus the Python program for printing all prime numbers within a given range was syccessfully created.

