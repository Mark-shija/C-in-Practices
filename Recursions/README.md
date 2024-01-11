# CONCEPTS OF RECURSION IN C
* Recursion or recursive function in C programming Language is a function that calls itself directly or indirectly.

* In other word we can say that a recursive function is a function that solves a problem by dividing it into smaller chunks or smaller instances.
  # Qn?? DO WE NEED RECURSION IN PROGRAMMING

  * Recursive functions in more usefull in programming to solve complex problems that can be broken down into subproblems.
    
    # WRITTING RECURSIVE FUNCTION
     A recursive function has the following components
    * Base case: This is a simplest phase that does not require further recursion. In other way this is a terminating condition that prevent a recursive function from calling itself indefinitely. without termination a recursive function may run infinitely causing more consumption of memory space(stack overflow).
    * Recursive case: In the recursive case, the function calls itself with the modified arguments. This is the essence of recursion – solving a larger problem by breaking it down into smaller instances of the same problem.
    * Let's consider the following example:
  
    ![EXAMPLE1](https://github.com/Mark-shija/C-in-Practices/blob/main/Recursions/screenshoots/example%201.png?raw=true)
* In the example above, a conditional if statement acts as a base case i.e when n == 1 evaluates to TRUE the function returns 1. and when if statement evaluates to FALSE the function evokes a recursive function and continue to call itself untill the condition terminate by evaluating to TRUE
  # WHAT COULD BE THE OUTPUT???
