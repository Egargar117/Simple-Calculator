[Simple-Calc.py](https://github.com/user-attachments/files/23150666/Simple-Calc.py)
#simple-calc
def addition(x, y):
    return x + y
def subtract(x, y):
    return x - y
def divide(x, y):
    return x/y
def multiply(x, y):
    return x*y
print("select an operation ")
print("1 = add")
print("2 = subtract")
print("3 = divide")
print("4 = multiply")
sel = int(input("Select operation 1-4 "))
x = int(input("Enter the first number "))
y = int(input("Enter the second number "))
if sel == 1:
    addition(x, y)
    print(x, "+", y, "=", addition(x, y))
elif sel == 2:
    subtract(x, y)
    print(x, "-", y, "=", subtract(x, y))
elif sel == 3:
    divide(x, y)
    print(x, "divided by", y, "=", divide(x, y))
elif sel == 4:
    multiply(x, y)
    print(x, "times", y, "=", multiply(x, y))
else:
    print("error. Select a number from 1-4")

input("press enter to exit")
