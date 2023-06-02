# numc

### Provide answers to the following questions.
- How many hours did you spend on the following tasks?
  - Task 1 (Matrix functions in C): 6
  - Task 2 (Speeding up matrix operations): 10
- Was this project interesting? What was the most interesting aspect about it?
  - WE thought this project was very interesting. We're used to coding with the philosophy of "don't repeat yourself" and trying to write human readable code. However, when writing a highly efficient library like NumC we have to add in optimizations, such as loop unrolling that made the code more efficient but much harder to read.
- What did you learn?
  - We learned the diffrenet way of improving the run time of code through the use of SIMD and MIMD. This included methods of Loop unrolling, multi threading, etc. Through the use of OMP and SIMD instruction sets. This project felt like an extention to lab, and showed how to integrate optimized code within a larger project.
- Is there anything you would change?
  - Make the C tests check for type (ex. float vs int).
  - Some of the spec was not clear and could be changed:
    - The nesting of the ifs within deallocate matrix.
    - We created a function called print matrix which we found to be extremely helpful for debugging and could be part of the starter code.
