[HOME](https://driphtyio.github.io/python-yu/)

## Day 1

### Exercise 1 - Printing 


```
# Write a program in main.py that prints the same notes from the previous lesson using what you have learnt about the Python print function.

print("Day 1 - Python Print Function")
print('The function is declared like this:')
print("print('what to print')")
```
### Exercise 2 - Debugging Practice


```
# Look at the code in the code editor on the right. There are errors in all of the lines of code. Fix the code so that it runs without errors

print("Day 1 - String Manipulation")
print('String Concatenation is done with the "+" sign.')
print('e.g. print("Hello " + "world")')
print("New lines can be created with a backslash and n.")
```

### Exercise 3 - Input Function
```
# Write a program that prints the number of characters in a user's name. You might need to Google for a function that calculates the length of a string

x = input("What is your name?")
print(len(x))
```

### Exercise 4 - Variables


```
# Write a program that switches the values stored in the variables a and b

a = input("a: ")
b = input("b: ")

c = a
a = b
b = c

print("a: " + a)
print("b: " + b)
```

### Day 1 - Project: Band Name Generator
```
#1. Create a greeting for your program.
#2. Ask the user for the city that they grew up in.
#3. Ask the user for the name of a pet.
#4. Combine the name of their city and pet and show them their band name.

print("Welcome to the Band Name Generator.")
street = input("What's name of the city you grew up in?\n")
pet = input("What's your pet's name?\n")
print("Your band name could be " + street + " " + pet)
```


