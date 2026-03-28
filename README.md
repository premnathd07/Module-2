~~~
Developed by:PREMNATH D
RegisterNumber:212225230217 
~~~

# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
x=16
y=bin(x)
print(y)
```

## Output
<img width="326" height="277" alt="image" src="https://github.com/user-attachments/assets/e7e8f2dd-72da-48d4-b775-87a449138f77" />

## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    return a % b

a = int(input())
b = int(input())
print("The result of the modulo operation is:", result(a, b))
```
## Output
![442893816-1d6cd4c7-b1ce-42b7-87a8-054b1cc2b7f8](https://github.com/user-attachments/assets/73565b25-fa40-4cce-b63d-ca9a04fe24a6)
## Result
The program successfully defines a function that computes the modulo of two numbers and returns the result.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input())
b=int(input())
c=int(input())
f=a+b+c
print(f)
```

## Output
<img width="1046" height="339" alt="image" src="https://github.com/user-attachments/assets/166044be-1aa0-49f3-a6db-e155d3eb89a1" />

## Result
Thus, the python program was executed successfully.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
a=int(input())
for i in range(a):
    
    for j in range(a-i-1):
        print(end=" ")
    for m in range(i+1):          
             ncr=1
             if(i>0):
                ncr=1
                for k in range(1,m+1):
                     c=(i-k+1)/k
                     ncr=ncr*c
             print(int(ncr), end=" ")
    print("")
```

## Sample Output
<img width="727" height="602" alt="image" src="https://github.com/user-attachments/assets/af9fb9b7-4c6e-48b7-b8aa-89f845f1dc3e" />


## Result
Thus, the python program was executed successfully.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```
## Output
<img width="593" height="114" alt="image" src="https://github.com/user-attachments/assets/fbc45cbf-8cf2-47de-947f-58a2e7d476f2" />

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
