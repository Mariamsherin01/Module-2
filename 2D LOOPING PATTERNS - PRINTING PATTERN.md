# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program that prints a downward pyramid pattern of stars based on the number of rows given as input.

---

### ALGORITHM

1.Accept the number of rows from the user.

2.Use a for loop starting from the input number down to 1.

3.Inside the loop, use the print() function to display that many stars (*) separated by spaces.

4.Reduce the number of stars printed in each successive row by 1.

---

### PROGRAM
```
#Reg.No: 212222060143
#Name: Mariam Sherin
rows = int(input())
for i in range(rows + 1, 0, -1):
    # nested reverse loop
    for j in range(0, i - 1):
        # display star
        print("*", end=' ')
    print(" ")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/b1604a25-33d2-483e-adf7-b824cfa4c13c)

### RESULT
Thus, The Python program that prints a downward pyramid pattern of stars based on the number of rows given as input was implemented and executed.
