# Variables and Assignment in Python 3

In Python, variables and assignment are core concepts that you will use constantly. Let's explore them in detail, specifically for Python 3.

## 1. What is a Variable?

A variable in Python is a name that refers to a value stored in memory. Think of it as a label you attach to some data so you can use it later in your program. In Python, variables don’t need to be declared with a specific type before use.

In simple terms, you can think of a variable as a container or box that holds some value.

### Example:

```python
age = 25


## 2. Rules for Naming Variables
There are a few rules and guidelines when naming variables in Python:

Variable names can contain letters, numbers, and underscores (_), but they cannot start with a number.
Variable names are case-sensitive. So name and Name are different variables.
You cannot use reserved keywords in Python like if, else, for, etc., as variable names.
### Example of Valid Variable Names:
``` python

name = "Alice"
total_price = 100.50
_is_valid = True

Example of Invalid Variable Names:
``` python
1st_name = "Alice"  # Cannot start with a number
total-price = 100.50  # Cannot use hyphens (-), must use underscores (_)
for = 10  # 'for' is a reserved keyword


### 3. Assigning Values to Variables
In Python, you use the assignment operator = to assign a value to a variable.

Example:
python
Copy code
age = 25
name = "Alice"
is_active = True
Here:

The variable age stores an integer value 25.
The variable name stores a string value "Alice".
The variable is_active stores a boolean value True.
In each case, the variable is assigned a value, and Python knows the type based on the value.


