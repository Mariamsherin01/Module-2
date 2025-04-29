# Exp.No:2e  
## SEB - Sum of All Even Numbers in a Given Range

---

### AIM  
To write a Python program that calculates and displays the sum of all even numbers between two given numbers (inclusive).

---

### ALGORITHM

1.Take two integers as input from the user (start and end of the range).

2.Initialize a variable total to 0.

3.Use a for loop to iterate from the start number to the end number.

4.Inside the loop, check if the current number is even using the modulus operator (% 2 == 0).

5.If even, add it to the total.

6.After the loop, print the sum.



---

### PROGRAM

```
reg.no: 212222060143
name: Mariam Sherin
sum_=0
m=int(input())
n=int(input())
for i in range(m,n+1):
    if(i%2==0):
        sum_+=i
print("Sum is :",sum_)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/8c251f17-8a0f-439b-aa14-e7029d08b23a)

### RESULT
Thus, The Python program that calculates and displays the sum of all even numbers between two given numbers was implemented and executed successfully.
