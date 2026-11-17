
<div align="center">

# MODY UNIVERSITY OF SCIENCE AND TECHNOLOGY

### School of Engineering and Technology

<img width="154" height="157" alt="Mody University Logo" src="https://github.com/user-attachments/assets/11e32514-7869-4f2d-afc9-b45171b58488" />

# PYTHON PROGRAMMING LAB
## LAB RECORD

**Student Name:** Priyanka Meena

**Enrollment Number:** 250001

**Faculty Name:** Dr. P. K. Bishnoi

**Mody University of Science and Technology**

**School of Engineering and Technology**

**Lakshmangarh, Rajasthan**

</div>

---

<a id="index"></a>

# INDEX

| S. No. | Program | Link |
|:---:|:---|:---:|
| 1 | Addition of Two Numbers | [View Program 1](#program-1-addition-of-two-numbers) |
| 2 | Largest of Three Numbers | [View Program 2](#program-2-largest-of-three-numbers) |
| 3 | Factorial of a Number | [View Program 3](#program-3-factorial-of-a-number) |
| 4 | Prime Number Check | [View Program 4](#program-4-prime-number-check) |
| 5 | Fibonacci Series | [View Program 5](#program-5-fibonacci-series) |

---

## Program 1: Addition of Two Numbers

### Aim
To write a Python program to find the sum of two numbers.

### Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum = a + b

print("Sum =", sum)
```

### Sample Output

```text
Enter first number: 10
Enter second number: 20
Sum = 30
```

[⬆ Back to Index](#index)

---

## Program 2: Largest of Three Numbers

### Aim
To write a Python program to find the largest among three numbers.

### Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    largest = a
elif b >= a and b >= c:
    largest = b
else:
    largest = c

print("Largest number =", largest)
```

### Sample Output

```text
Enter first number: 10
Enter second number: 25
Enter third number: 15
Largest number = 25
```

[⬆ Back to Index](#index)

---

## Program 3: Factorial of a Number

### Aim
To write a Python program to calculate the factorial of a given number.

### Program

```python
n = int(input("Enter a number: "))

fact = 1

for i in range(1, n + 1):
    fact = fact * i

print("Factorial =", fact)
```

### Sample Output

```text
Enter a number: 5
Factorial = 120
```

[⬆ Back to Index](#index)

---

## Program 4: Prime Number Check

### Aim
To write a Python program to check whether a given number is prime or not.

### Program

```python
n = int(input("Enter a number: "))

prime = True

if n < 2:
    prime = False
else:
    for i in range(2, n):
        if n % i == 0:
            prime = False
            break

if prime:
    print(n, "is a Prime Number")
else:
    print(n, "is not a Prime Number")
```

### Sample Output

```text
Enter a number: 7
7 is a Prime Number
```

[⬆ Back to Index](#index)

---

## Program 5: Fibonacci Series

### Aim
To write a Python program to generate the Fibonacci series.

### Program

```python
n = int(input("Enter number of terms: "))

a = 0
b = 1

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

### Sample Output

```text
Enter number of terms: 7
0 1 1 2 3 5 8
```

[⬆ Back to Index](#index)

---
