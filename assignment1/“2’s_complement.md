
The two's complemented do not have to deal with end around borrow and end around carry. 

The two's coimplemented have only one representation of zero which is very atomic, since everything we deal with on the machine level needs atomic to be truly deterministic. 

The two's complemented is the easiest way for humans and machines to deal negative numbers. In machine terms, the two's complemented of any number added to that number pre two's complement would yield zero. 

Two's complement addition is very simple. You add numbers normally and any carry bit at the end is discarded. So they're added as follows: This example is from stack overflow, however it really shows the power of two's complement. 

  0010
+ 1111
=10001
= 0001 (discard the carry)

We do not need to examine the operands for twos complement addition and substraction which makes caluculations to have more precision. 

A adder works by adding, it is up to you how you intrepret the numbers, unsigned or signed, however it makes no difference to the adder. 




