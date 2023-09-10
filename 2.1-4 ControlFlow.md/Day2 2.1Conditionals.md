# 2.1
## If, Elif, Else 
__You can use if, elif (short for “else if”), and else to perform different actions based on certain conditions.__

**Here’s a simple example:**

````python
age = 18

if age < 18:
    print("You are a minor.")
elif age < 60:
    print("You are an adult.")
else:
    print("You are a senior citizen.")
````

# If 
In Python, there are three forms of the if...else statement.

1. if statement
2. if...else statement
3. if...elif...else statement

## The syntax of if statement in Python is:
if condition: 
````python
if condition:
# body of if statement
````

the if statement evaluates condition.

If condition is evaluated to True, the code inside the body of if is executed.
If condition is evaluated to False, the code inside the body of if is skipped.
````python 
number = 10

# check if number is greater than 0
if number > 0:
    print('Number is positive.')

print('The if statement is easy')
````
number greater than 0 so condition evaluates true

## The syntax of if.... else

````python
if condition:
    # block of code if condition is True

else:
    # block of code if condition is False
````


