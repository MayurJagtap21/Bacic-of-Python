# Basics of Python

# Variables
a = int(input("Enter 1st number: "))
b = int(input("Enter 2nd number: "))
print(a + b)

lecture_day2: int = 2
print(lecture_day2)

# Operators
circle_area = 6.5
square_area = 40
iota = (-1) ** (1/2)
print(circle_area, square_area, iota)
print(square_area + circle_area)

x = int(input("Value of x: "))
y = int(input("Value of y: "))
print(x + y)

a = 5
less_than_equal = (a <= 5)
print(less_than_equal)
print(type(less_than_equal))

a = 5
equal_5 = (a == 5)
print(equal_5)

a = 10
not_equal = (a != 10)
print(not_equal)

# if else conditions
x = int(input())
if x < 1 or x >= 10:
    print("Mayur")
else:
    print("Jagtap")

vegetable_market = ["cabbage", "onion", "apple", "mango"]
if "carrot" in vegetable_market:
    print("Buy the carrot")
elif "cabbage" in vegetable_market:
    print("Buy the cabbage")
else:
    print("Back with empty hand!")
    
# Loops

# for loop
for i in range(1, 6):
    print(i)
# while loop
i = 1
while i <= 5:
    print(i)
    i = i + 1

# Print number from 1 to 10
for i in range(10):
    print(i)

for i in range(1, 11):
    print(i)

# Print even number
for i in range(2, 11, 2):
    print(i)
# Print odd number
for i in range(1, 11, 2):
    print(i)

for i in range(11, 2, -2):
    print(i, end=' ')

counter = 1
while counter <= 10:
    print(counter, end=' ')
    counter += 1
print()

n = int(input())
for multiple in range(1, 11):
    for number in range(1, n + 1):
        print("%4d" % (number*multiple), end=' ')
    print()
    
# jump statement
alphabets = ["a", "b", "c", "d", "e"]
for alphabet in alphabets:
    print(alphabet)
    if alphabet == "d":
        break

for alphabet in alphabets:
    if alphabet == "d":
        continue
    print(alphabet)"""

# function
def hello():
    print("hello world!")
hello()

def add(num1, num2):
    return num1 + num2

x = int(input())
y = int(input())
print(add(x , y))
