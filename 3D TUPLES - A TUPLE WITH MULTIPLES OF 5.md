# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
n = eval(input())
a = []
for i in range(1, n):
    if i % 9 == 0:
        a.append(i)
b = tuple(a)
print(b)
print("Length of the tuple is", len(a))
```

### OUTPUT
<img width="691" height="237" alt="image" src="https://github.com/user-attachments/assets/9a236588-e2ac-4f0d-8536-a696e5b0589a" />


### RESULT
Thus the program is executed and verified.
