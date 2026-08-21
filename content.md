# Boolean Operators in Python

Python provides three boolean operators: `not`{.python}, `and`{.python}, and `or`{.python}. These allow you to combine boolean values and expressions which return boolean values (such as comparisons) to create more complex conditions.

# The `not`{.python} Operator

The `not`{.python} operator reverses a boolean value:

```py-cell
print(not True)
print(not False)
print(not (5 > 3))
```

# The `and`{.python} Operator

The `and`{.python} operator returns `True`{.python} only if both operands are `True`{.python}:

```py-cell
print(True and True)
print(True and False)
print(False and True)
print(False and False)
print(5 > 3 and 2 < 4)
print(5 > 3 and 2 > 4)
```

# The `or`{.python} Operator

The `or`{.python} operator returns `True`{.python} if at least one operand is `True`{.python}:

```py-cell
print(True or True)
print(True or False)
print(False or True)
print(False or False)
print(5 > 10 or 2 < 4)
print(5 > 10 or 2 > 4)
```