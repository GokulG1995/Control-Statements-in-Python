# Control-Statements-in-Python
Control statements in Python are used to control the flow of execution in a program. They help in making decisions, repeating actions, or controlling the program's flow based on conditions. The primary control statements in Python
1. Conditional Statements (If-Else):
Used to make decisions based on conditions.

if: Executes a block of code if the condition is true.
else: Executes a block of code if the condition is false.
elif: Checks multiple conditions.
python
Copy code
x = 10
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")
2. Looping Statements:
Used to repeat a block of code multiple times.

for: Loops through a sequence (like a list, tuple, or string) and executes the code block for each item.

python
Copy code
for i in range(5):
    print(i)
while: Loops as long as the condition is true.

python
Copy code
i = 0
while i < 5:
    print(i)
    i += 1
3. Control Flow Statements:
These control the execution of loops or block of code.

break: Exits the current loop.

python
Copy code
for i in range(10):
    if i == 5:
        break
    print(i)
continue: Skips the current iteration and proceeds to the next iteration of the loop.

python
Copy code
for i in range(5):
    if i == 2:
        continue
    print(i)
pass: Does nothing, used as a placeholder for future code.

python
Copy code
for i in range(5):
    pass
These control statements are fundamental for building flexible and efficient programs in Python.
