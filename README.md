# beginner-python

## Variables
Variables are phrases that store some type of data. For example:
`my_variable = 1`

There are different types of variables. Two of these are integers and strings.
```
int = 10
str = "Hello"
boolean = True
```
Integers store numbers and strings store text. Booleans are set to either `True` or `False`.

To assign a value to a variable use the name and = and then the value.
Like this `variable = value`

## Conditionals
Conditionals allow an action to be preformed only when specific conditions are met. `If` and `elif` are two examples of this.

Expressions are the conditions that are passed into a conditional statement. These are like `and`, `or`, and `not`.

Let's look at an example.
```
if x > 0 and y > 0:
  # do something
elif x > 0 or y > 0:
  # do something else
```
The first `if` statement checks if two values are greater than 0.
The `elif` checks the values before moving on to the next if statement.

You can also check if a value is set to `True` or `False`

```
if boolean:
  # code: this executes when it is True
```

Branching is done like below.

```
if x > 0:
  print "x is greater than 0"
else:
  print "x is not greater than 0"
```

In the above example the `if` statement is checked and if it is not true than the program executes the `else` statement.


## Functions

Functions are blocks of code that can be reused to preform the same task over and over again.

For example:
```
def my_function(a):
  return a + 10
```
This function accepts an integer `a` and returns the sum of a + 10.
This block of code could be used over and over in many different scenarios.
Instead of writing a separate line every time I need to add 10 I use this function.

Let's look at how it's written.

The first part `def` stands for define. This defines the function which you then give a name.
In the example above the name is `my_function`.
Then a set of parentheses with any input variables inside, followed by a colon.
Then you can write the code for the function below this line and indented.
