# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 9

---

### AIM  
To write a Python program that finds all numbers divisible by 9 from 1 to n-1, stores them in a tuple, displays the tuple, and prints its length.

---

### ALGORITHM
~~~
1.Start the program and read the value of n from the user.
2.Create an empty list a.
3.Iterate through numbers from 1 to n-1.
4.For each number, check whether it is divisible by 9; if yes, add it to the list a.
5.Convert the list into a tuple b, display the tuple, print its length, and stop the program.
~~~

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
