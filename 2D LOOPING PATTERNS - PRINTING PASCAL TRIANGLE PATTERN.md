# Exp.No:2d
## LOOPING PATTERNS - PRINTING PASCAL TRIANGLE PATTERN

### AIM  

To write a Python program to build pascal triangle using numbers .Get the number of rows as input .

### ALGORITHM

1. Begin the program.  
2. Input number of rows (rows).
3. For each row i from 0 to rows - 1:
   For each position j from 0 to i:
     Calculate the binomial coefficient (nCr) using decide_number(i, j):
       Set num = 1.
       If k > n - k, set k = n - k.
       For i from 0 to k - 1, update num = num * (n - i) // (i + 1).
       Print the number.
4. Move to the next line after printing all numbers in the row.
5. Terminate the program.

### PROGRAM
```


def print_pascal_triangle(size):
    for i in range(0, size):
        for j in range(0, i + 1):
            print(decide_number(i, j), end=" ")
        print()


def decide_number(n, k):
    num = 1
    if k > n - k:
        k = n - k
    for i in range(0, k):
        num = num * (n - i)
        num = num // (i + 1)
    return num

# set rows
rows = int(input())
print_pascal_triangle(rows)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/a6c23aae-f81d-4a6e-9b90-d3033a31dff8)

### RESULT

Thus the a Python program to build pascal triangle using numbers was successfully created.

