# Functions and Methods

Overview

Functions and methods are used to organize code into reusable blocks.  
They help make programs easier to read, maintain, and reuse.  

You will learn:

- What functions and methods are
- How to define and use them
- How to pass data to functions
- How to return values

## 1. What are Functions?

A function is a block of code that performs a specific task.

It can be reused multiple times in a program.

## 2. What are Methods?

A method is a function that belongs to an object.

In many cases (especially in simple programs), the idea is similar to functions.

## 3. Defining a Function

A function has:

- A name
- Optional inputs (parameters)
- A task
- Optional output (return value)

Example:  
```
FUNCTION add(a, b)
    result = a + b
    RETURN result
END FUNCTION
```
## 4. Calling a Function

To use a function, you call it by its name.

Example:  
```
SET sum = add(5, 3)
OUTPUT sum
```
## 5. Functions with Parameters

Parameters allow you to pass values into a function.

Example:  
```
FUNCTION greet(name)
    OUTPUT "Hello " + name
END FUNCTION

CALL greet("Alex")
```

## 6. Functions with Return Values

Functions can return results to the main program.

Example:  
```
FUNCTION square(x)
    RETURN x * x
END FUNCTION

SET result = square(4)
OUTPUT result
```
## 7. Why Use Functions?

Functions help you:

- Avoid repeating code
- Make programs more organized
- Break problems into smaller parts

## 8. Summary

Functions and methods allow you to:

- Structure your code
- Reuse logic
- Improve readability

They are essential for writing larger and more complex programs.

[🏠 Mainpage](https://github.com/IT-W1zard/BITLC-Preliminary-Course/tree/main)
