# Nassi-Shneiderman diagrams

Overview

Nassi-Shneiderman diagrams (also called structograms) are a way to visually design
algorithms using structured blocks instead of flowchart symbols.
They help you represent program logic in a clear, 
step-by-step structure without arrows or loops crossing each other.

You will learn:

- What Nassi-Shneiderman diagrams are
- The basic building blocks
- How to represent sequence, selection, and loops
- How to read and interpret diagrams

## 1. What are Nassi-Shneiderman Diagrams?

Nassi-Shneiderman diagrams are structured charts used in programming to design algorithms.

Instead of using flowchart arrows, they use stacked rectangles to show:

- Order of execution
- Decisions (if/else)
- Repetitions (loops)

They are commonly used in structured programming and were covered in the BITLC foundation course.

## 2. Basic Structure

A diagram is made of rectangular blocks arranged from top to bottom.

Each block represents an instruction or control structure.

There are 3 main types:

### 1. Sequence

Instructions are executed one after another.

Example:
```
        Step 1: Read A  
        Step 2: Read B  
        Step 3: Calculate Sum  
        Step 4: Output Result  
```
### 2. Selection (IF / ELSE)

Used for decisions.

Example:
```
        IF age >= 18  
            Output "Adult"  
        ELSE  
            Output "Minor"  
```
### 3. Iteration (Loops)

Used when steps repeat.

Example (WHILE loop):  
```
        WHILE counter < 5  
                Output counter  
                counter = counter + 1  
```
## 3. How to Read a Nassi-Shneiderman Diagram

Step-by-step method:
Look at the top block first
Follow the structure downward
Check for conditions (IF / WHILE)
Execute blocks in order or based on conditions

Example 1: Simple Decision  
```
        IF number > 0  
            Output "Positive"  
        ELSE  
            Output "Not Positive"  
```
Meaning:

- Check the condition
- Choose only one path

Example 3: Combined Logic  
```
        Read number  
        IF number % 2 == 0  
            Output "Even"  
        ELSE  
            Output "Odd"  
```
Meaning:

- First input is taken
- Then decision is made
- One of two outputs is shown

## 4. Summary

Nassi-Shneiderman diagrams are based on:

Structured blocks instead of arrows
Clear control flow (sequence, selection, iteration)
Easy-to-read program logic

Once you understand the structure, you can design and analyze algorithms more easily before writing actual code.

[🏠 Mainpage](https://github.com/IT-W1zard/BITLC-Preliminary-Course/tree/main) 
