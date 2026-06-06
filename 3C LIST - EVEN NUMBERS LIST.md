# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that creates a list of even numbers from 12 to n and prints the list and its sum.

---

### ALGORITHM
~~~
1.Start the program. 
2.Define a function named createlist that accepts a single parameter n. 
3.Initialize an empty list l. 
4.Iterate from 12 to n-1 using a for loop: For each number i in the range: Check if i is even using the condition i % 2 == 0. 
5.If the condition is true, append i to the list l. After the loop ends, print the list using print("List =", l). 
6.Calculate the sum of the list using sum(l) and print the result. End the function. 
7.Terminate the program.
~~~

### PROGRAM

```
def createlist(n):
    l=[]
    for i in range(12,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list",sum(l))
```

### OUTPUT
<img width="1256" height="312" alt="image" src="https://github.com/user-attachments/assets/3c106ccd-6171-4f03-9180-a672c6570dd7" />


### RESULT
Thus the program is executed and verified.
