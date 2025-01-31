# java-rpn-calculator
Reverse Polish Notation calculator implemented with Java

## Description
Implmentation of Reverse Polish Notation calculator that can handle addition, subtraction,
multiplication, division and cosine (input radians). The operands can be integers or real
numbers and the operators can be symbols or text.

### Implementation details
- OS: Ubuntu 18
- Java: 11
- compile: javac rpn.java
- run: java rpn
  - examples: java rpn 3 3 2 '*' +
              java rpn 3 3 2 m +
              java rpn 3 cos 
              java rpn 1 3 cos +

- @param  operands  integers or real numbers
- @param  operators +, -, *, /, cos (also respitively add, subtract, multiply, divide, cosine)
- @return the value of the operation

## NOTES
- This java code is provided for example purposes only and left in the spirit it was written for, ie, a coding test for a job
- There is an unchecked test that I missed and I leave it to the reader to discover
- I hope this example helps you in your coding journey
- Enjoy the regular expression that consumes the command line arguments
