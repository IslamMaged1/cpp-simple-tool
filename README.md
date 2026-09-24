# C++ Project

This is a practice project, and the goal is to build toward real tools.

## Decimal to Binary Converter

Takes a decimal number and prints it in binary.

### How to compile and run
```
g++ main.cpp -o converter
./converter
```

### Example
```
Enter a number: 13
Binary: 1101
```

### What I learned
How a while loop works, when and why to place different conditions to avoid bugs related to loops, bugs related to semicolon endings (for example placing one in the same line as the while condition) and the logic behind the binary conversion.

### How it works
The user runs the program and enters a number,the program first checks if it's less than (-128) since it's only an 8 bit switch (to be fixed later in v3) and outputs that it can't handle less than (-128)
Giving it a positive number checks if the number is even or odd, if it is even, 0 is given, if it is odd, then 1 is given.
the program then performs a floor division and throws the leftovers for example (10) which then gives us (5) in this case there is no leftover. 
The process repeats until the number reaches 0 in which case the final binary number is printed.
if the binary box is empty, which only occurs if 0 was inputted, the program outputs 0.
