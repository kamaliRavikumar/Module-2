# Exp.No:2e  
## SEB - COMPUTING POWER

---

### AIM  
To write a Python Program to find the sum of series 1!+2!+3!...+n!
---

### ALGORITHM

1. Start the program.
2. Input the value of n (the number up to which the series is calculated).
3. Initialize two variables: sum = 0 (to store the total) and fact = 1 (to calculate factorials).
4. Repeat for each integer i from 1 to n:
5. Multiply fact by i to get the factorial of i.
6. Add this factorial to sum.
7. After the loop ends, sum will hold the total of the series.
8. Display the sum and end the program.

---

### PROGRAM

```
n=int(input())
sum=0
fact=1
for i in range(1,n+1):
    fact*=i
    sum+=fact
print("The sum of the series = ",sum)

```
### OUTPUT
<img width="953" height="259" alt="Screenshot 2025-08-26 195523" src="https://github.com/user-attachments/assets/113cae3a-d387-4c1d-bd54-392bdc0e900e" />

### RESULT
Thus the Python Program to find the sum of series 1!+2!+3!...+n! is executed successfully.
