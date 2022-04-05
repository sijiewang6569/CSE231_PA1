1. Give three examples of Python programs that use binary operators and/or builtins from this PA, 
   but have different behavior than your compiler. For each, write:
   (a). Python program can compare more than two items, my compiler will throw an error message
        It's because my compiler currently only considers two cases: the number of arguments is 1 and 2. 
        May use an array to temporarily store the inputted items, then compare these items.

   (b). When the inputted number is not integer, my compiler will throw an error message
        My complier currently only supports type "i32"
        May change the type of parameters and allow non-integer inputs in the future. 


   (c). For example, abs(print(1)), my complier outputs "1\n1", but Python program can't run it. 
        The type of return value of my print function is "i32", and it's a valid input for my abs opertion
        May unpdate print function of my complier, let it print out the value immediately instead of returning it.

2. What resources did you find most helpful in completing the assignment?
   Yousef's Tutorial. 

3. Who (if anyone) in the class did you work with on the assignment?
   None. 