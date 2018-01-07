# myCrappyRPN
RPN calculator for Bash

* HOW IT WORKS

-It is mostly like a norma RPN calculator
-It supports up to 10 stacks (0-9)
-Just type a number in and press ENTER to put it into stack 0
-Once there is a number in both stacks 0 and 1 then you can perform some standard operations
-ADDITION: press + then ENTER to add stacks 0 and 1
-SUBTRACTION: press - then ENTER to subtract stacks 0 and 1
-MULTIPLICATION: press x then ENTER to add multiply 0 and 1 (I used x since * is used for regex)
-DIVITION: press / then ENTER to divide stack 1 by stack 0
-EXPONENTIATION: press ^ then ENTER to take stack 1 to the stack 0-th power

NOTE: there is no concept of an empty stack in this program, just stacks with the number 0 in them

-OTHER FUNCTIONS:
  -SINE: type sin then press ENTER to take the sin of stack 0
  -COSINE: type cos then press ENTER to take the cos of stack 0
  -TANGENT: type tan then press ENTER to take the tan of stack 0
  -COTANGENT: type cot then press ENTER to take the cot of stack 0
  -SECANT: type sec then press ENTER to take the sec of stack 0
  -COSECANT: type csc then press ENTER to take the csc of stack 0
  -NATURAL LOG: type ln then press ENTER to take the ln of stack 0
  -LOG BASE 10: type log then press ENTER to take the log base 10 of stack 0

-CONSTANTS:
  -e: type e then press ENTER to get euler's constant
  -pi: type pi the press ENTER to get pi
  
-STACK MANIPULATIONS:
  -SWAP: type swap or sp then the number of which two stacks you want to swap values ex: "swap 0 1" ENTER
  -DELETE: type del then the number of which stack you want to delete the value of ex: "del 4" ENTER
  -ROTATE: type rot then ENTER to rotate all of the values down i.e. stack 1 goes to stack 0
  -UNROTATE: type unrot then ENTER to rotate all of the values up i.e. stack 0 goes to stack 1
  -COPY: type copy or cp then the number of the stack you want to copy from then the number of the stack you want to copy to
  -CLEAR: type clear then ENTER to set all values to 0
  
-TURNING IT OFF:
  -type off, done, stop, or exit then ENTER to stop the program