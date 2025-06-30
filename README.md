# 🧮 Calculator Application in Java

A **Console-Based Calculator Application** developed in Java using basic principles of Object-Oriented Programming and control structures. This application allows the user to perform arithmetic operations such as Addition, Subtraction, Multiplication, Division, and Modulo with continuous operation and graceful exit options.

---

## 📘 About the Project

This calculator application is designed as a beginner-friendly **Java + DSA mini project**, allowing users to understand:

- How to structure Java applications.
- How to interact with users via the command line.
- How to apply control flow using `switch-case`, `if-else`, and loops.
- How to use Java classes, methods, and input handling with `Scanner`.

The application keeps running in a loop, allowing users to perform multiple operations until they choose to exit.

---

## 🛠️ Features

- 🔢 Perform basic arithmetic operations:
  - Addition `+`
  - Subtraction `-`
  - Multiplication `*`
  - Division `/` (with divide-by-zero check)
  - Modulo `%` (with divide-by-zero check)
- 🔁 Continuous operation loop until the user chooses to exit.
- ❗ Input validation for operations and retry mechanism on invalid choices.
- 🚫 Graceful exit with max 5 retries if the user fails to provide correct input for exit.

---

## 🧪 Sample Output

```text
Welcome to Calculator Application - By Java Plus DSA
Choose an Operation: ( *, +, -, %, / )
-> +
Enter a number ->
10
Enter a number ->
20
Addition -> 30
Do you want to continue? (y/n)
-> y
Choose an Operation: ( *, +, -, %, / )
-> /
Enter a number ->
15
Enter a number ->
0
Divide by zero error
Do you want to continue? (y/n)
-> n
Thanks for using our service
