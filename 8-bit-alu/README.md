# 8-bit ALU
## Summary

This module is a continuation of my 2-bit ALU.
[Here's a link to the module and a testbench on EDA Playground.](https://www.edaplayground.com/x/gqr8)

*This module is not complete yet.*

Features include:
 - 8-bit I/O
 - 5-bit instruction register (only 4 bits used right now, but support exists for more)

Supported Operations:
 - 00000 - n/a; IDLE
 - 00001 - OR
 - 00010 - AND
 - 00011 - ADDITION
 - 00100 - SUBTRACTION
 - 00101 - XOR
 - 00110 - NOR
 - 00111 - NAND
 - 01000 - LOGICAL SHIFT LEFT
 - 01001 - LOGICAL SHIFT RIGHT
 - 01010 - ROTATE LEFT
 - 01011 - ROTATE RIGHT
 - 01100 - COMPLEMENT (1's Complement for Unary Operation)
 - 01101 - INCREMENT (Unary Operation, i.e., A + 1)
 - 01110 - DECREMENT (Unary Operation, i.e., A - 1)
 - 01111 - SET LESS THAN (Comparison, sets output to 1 if A < B, 0 otherwise)