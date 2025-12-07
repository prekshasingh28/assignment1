#ASSIGNMENT1
#task1

num1 = input("Enter the first number: ")
num2 = input("Enter the second number: ")

# performing basic mathematical operations
addition = int(num1) + int(num2)
subtraction = int(num1) - int(num2)
multiplication = int(num1) * int(num2)
division = round(float(num1) / float(num2), 2)

# to perform mathematical operations
print("Addition: ", addition)
print("Subtraction: ", subtraction)
print("Multiplication: ", multiplication)
print("Division: ", division)


#task2
firstname = input(" Enter your first name: ")
lastname = input(" Enter your last name: ")
add = firstname + " " + lastname  #concatenation
# added a space string in the middle to give space between firstname and lastname
print("Hello, " +add+ "! welcome to the python program")
