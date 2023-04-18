Day 1: Print Statements and Taking Input from Users
Welcome to Day 1 of the 100 Days of Python Challenge! Today, we will be exploring how to use print statements to display messages on the screen, as well as how to take input from users.

Using Print Statements
In Python, the print() function is used to display messages on the screen. To use the print() function, you simply need to provide the message that you want to display inside the parentheses. For example:

bash
Copy code
print("Hello, world!")
This will display the message "Hello, world!" on the screen.

You can also use the print() function to display variables. For example:

makefile
Copy code
name = "John"
age = 30
print("My name is", name, "and I am", age, "years old.")
This will display the message "My name is John and I am 30 years old." on the screen.

You can also format the message using string interpolation. For example:

python
Copy code
name = "John"
age = 30
print(f"My name is {name} and I am {age} years old.")
This will also display the message "My name is John and I am 30 years old." on the screen, but it's a bit more concise and easier to read.

Taking Input from Users
In Python, you can use the input() function to prompt the user to enter some input. For example:

lua
Copy code
name = input("What is your name? ")
print("Hello, " + name + "!")
This will prompt the user to enter their name, and then display the message "Hello, [name]!" on the screen.

You can also use the input() function to prompt the user to enter a number. For example:

python
Copy code
num = int(input("Enter a number: "))
print("The square of", num, "is", num**2)
This will prompt the user to enter a number, convert the input to an integer using the int() function, and then display the message "The square of [num] is [num**2]" on the screen.

That's all for today! Practice using print statements and taking input from users in your own Python programs. See you tomorrow for Day 2!

