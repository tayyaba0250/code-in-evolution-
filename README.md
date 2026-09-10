# code-in-evolution-

# Greeting
name = input("Enter your name: ")

print("Hello,", name + "!")
print("Welcome to Python programming!")

# Basic calculator 

num1=int(input("Enter 1st number"))
num2=int(input("Enter 2nd number"))

answer=num1+num2

print("The answer is:",answer)

#if and else

age = int(input("Enter your age: "))

if age >= 18:
    print("You can vote")
else:
    print("You cannot vote yet")

#loops

for number in range(1, 11):
    print(number)

#Learning how to organize and reuse code

def greet():
    print("Hello!")
    print("Welcome to Python")

greet()