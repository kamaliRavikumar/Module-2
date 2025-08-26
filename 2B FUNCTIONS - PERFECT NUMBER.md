# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No:
#Name:
#Add your Code Here

n=int(input())
sum=0
for i in range(1,n):
    if (n%i==0):
        sum=sum+i
if (sum==n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")

```
### OUTPUT
<img width="1113" height="263" alt="Screenshot 2025-08-26 193631" src="https://github.com/user-attachments/assets/4ef0c37a-ef16-428e-a982-7574f092913a" />

### RESULT
 Thus the Python program to check if a number is a Perfect number using the concept of functions is executed successfully.
