# Use-of-Bitwise-Operators

## Aim:
To study how to use bitwise operators is cpp

## Theory:
Bitwise operators change/manipulate the given input or data at individual bits level. They operate on integer operands treating them as sequence of binary digits.

1. Bitwise AND(&): Performs logical AND on corresponding bits of 2 inputs.
2. Bitwise OR(|): Performs logical OR on corresponding bits of 2 inputs.
3. Bitwise XOR(^): Performs logical XOR on corresponding bits of 2 inputs.
4. Bitwise NOT(~): Performs logical NOT on corresponding input.
5. Left shift(<<): Shifts the desired bit to 2 spaces left.
6. Right shift(>>): Shifts the desired bit to 2 spaces right.

## Algorithm:
1.Start
2.Declare variables:
a, b as integers to store input values
bit_and, bit_or, bit_xor, bit_not_a, bit_not_b as integers to store results
3.Prompt the user:
4.Display "Enter the first number:"
5.Read the input value and store it in a
Display "Enter the second number:"
6.Read the input value and store it in b
7.Perform bitwise operations:
Calculate bit_and = a & b
Calculate bit_or = a | b
Calculate bit_xor = a ^ b
Calculate bit_not_a = ~a
Calculate bit_not_b = ~b
Calculate a = a << 2
Calculate b = b << 2
Calculate a = a >> 2
Calculate b = b >> 2
8.Print results:
Display the value of bit_and
Display the value of bit_or
Display the value of bit_xor
Display the value of bit_not_a
Display the value of bit_not_b
Display the value of a
Display the value of b
9.End
