# Factorial

## Iterative and Recursive Factorial functions

At the first file Factorial2 i wrote the factorial function of an integer in 2 way Iterative & Recursive

using Iterative, every thing went well till input 20 it gave illogical values like negatives and zeros

and this happened due to ..

1. Stack overflow: It happens when a program's call stack—the region of memory used for managing function calls and local variables—exceeds its allocated size. In simpler terms, the call stack gets filled with too many function calls, and there's no more space available to accommodate additional calls.
2. Data type overflow: a situation where a value exceeds the range or capacity that can be represented by a particular data type.

## Solving of the problem

we looked for a solve and using array was the best solution and it works for any number event its factorial consists of more than 1000 bits , Solving.cpp

Briefly, we store the factorial of the number each bit in an array location then printing it 

we can use Vector or LinkedList either .

---

![Untitled](https://github.com/AbdSarabi/Algorithm/assets/142683476/e7dce432-4bc9-476c-bffe-f40870278fa6)
