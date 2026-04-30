# Number Systems

## Number Systems (Binary, Decimal, Hexadecimal)

Overview

Number systems are different ways of representing numbers.  
In computing, the most important systems are binary, decimal, and hexadecimal.  

You will learn:

- What binary, decimal, and hexadecimal are
- How each number system works
- How to convert between them
- Why computers use binary

## 1. Decimal System (Base 10)

The decimal system is the standard number system used by humans.

It uses 10 digits:
0, 1, 2, 3, 4, 5, 6, 7, 8, 9

Each position represents a power of 10.

Example:
```
345 = 3×100 + 4×10 + 5×1
```
## 2. Binary System (Base 2)

The binary system is used by computers.

It uses only two digits:
0 and 1

Each position represents a power of 2.

Example:
```
1011 = 1×8 + 0×4 + 1×2 + 1×1 = 11
```
So:

- 1011₂ = 11₁₀
## 3. Hexadecimal System (Base 16)

The hexadecimal system is used in programming and computer systems.

It uses 16 symbols:
0–9 and A–F

Where:

- A = 10
- B = 11
- C = 12
- D = 13
- E = 14
- F = 15

Example:
```
2F = 2×16 + 15 = 47
```
So:

- 2F₁₆ = 47₁₀
## 4. Converting Between Systems
### Decimal → Binary

Divide by 2 and record remainders.

Example:

- 13 ÷ 2 = 6 remainder 1
- 6 ÷ 2 = 3 remainder 0
- 3 ÷ 2 = 1 remainder 1
- 1 ÷ 2 = 0 remainder 1

Result:
```
13 = 1101₂
```
### Decimal → Hexadecimal

Divide by 16 and convert remainders.

Example:
```
47 ÷ 16 = 2 remainder 15 (F)

Result: 2F
```
### Binary → Decimal

Multiply each digit by powers of 2.

Example:
```
1101 = 1×8 + 1×4 + 0×2 + 1×1 = 13
```
### Binary → Hexadecimal

Group binary digits into sets of 4 (from right).

Example:
```
110111 = 0011 0111  
0011 = 3  
0111 = 7  

110111₂ = 37₁₆
```
### Hexadecimal → Decimal

Multiply each digit by powers of 16.

Example:
```
2F = 2×16 + 15×1 = 47
```
### Hexadecimal → Binary

Convert each hex digit into 4 binary bits.

Example:
```
3 = 0011  
7 = 0111  

37₁₆ = 110111₂
```
Quick Reference Table
| Decimal | Binary | Hex |
| ------- | ------ | --- |
| 1       | 0001   | 1   |
| 2       | 0010   | 2   |
| 3       | 0011   | 3   |
| 4       | 0100   | 4   |
| 5       | 0101   | 5   |
| 10      | 1010   | A   |
| 15      | 1111   | F   |

## 5. Why Computers Use Binary

Computers use binary because:

Electronic circuits have two states (on/off)
It is reliable and simple
It reduces errors in processing

6. Summary

Number systems allow us to represent data in different ways:

- Decimal → humans
- Binary → computers
- Hexadecimal → compact computer representation

Conversions between them are essential in programming and computer science.

## Roman Numerals

Overview

Roman numerals are a number system developed in ancient Rome.
Instead of digits like 1, 2, 3, they use letters from the Latin alphabet.

You will learn:
- The basic symbols
- How to read Roman numerals
- How to build numbers using rules
- How to convert Roman numerals to modern numbers

## 1. Roman Numeral Symbols

| Symbol | Value |
| ------ | ----- |
| I      | 1     |
| V      | 5     |
| X      | 10    |
| L      | 50    |
| C      | 100   |
| D      | 500   |
| M      | 1000  |

## 2. Basic Rules
### Rule 1: Addition

When symbols are written from largest to smallest, you add them.

VI = 5 + 1 = 6
XII = 10 + 1 + 1 = 12

### Rule 2: Repetition

Some symbols can be repeated (usually up to 3 times):

III = 3
XXX = 30
CCC = 300

### Rule 3: Subtraction

When a smaller value comes before a larger one, you subtract it.

IV = 5 − 1 = 4
IX = 10 − 1 = 9
XL = 50 − 10 = 40
CM = 1000 − 100 = 900

## 3. How to Read Roman Numerals

Step-by-step method:
Look at the symbols from left to right
Decide if you are adding or subtracting
Apply the rules

### Example 1: XIV
X = 10
IV = 4 (because I before V means subtract)
Total = 10 + 4 = 14

### Example 2: XLII
XL = 40
II = 2
Total = 40 + 2 = 42

### Example 3: MCMXC

Break it down:

M = 1000
CM = 900
XC = 90

Total = 1000 + 900 + 90 = 1990

## 4. Summary

Roman numerals are based on:

Addition (left to right)
Subtraction (special cases)
A fixed set of symbols

Once you understand the patterns, you can read almost any Roman numeral.

[🏠 Mainpage](https://github.com/IT-W1zard/BITLC-Preliminary-Course/tree/main)
