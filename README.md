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
How a while loop works, bugs related to semicolon endings (for example placing one in the same line as the while condition) and the logic behind the binary conversion.

### How it works
The user runs the program and enters a number, e.g (10), the program then performs a floor division and throws the leftovers which then gives us (5) in this case there is no leftover. 
The program checks if the number is even or odd. If it is even, 0 is given, if it is odd, 1 is given. 
The process repeats until the number reaches 0 in which case the final binary number is printed.
Finally inputting 0 gives nothing yet, which is to be fixed in v2
