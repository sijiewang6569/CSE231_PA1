1. Give three examples of Python programs that use binary operators and/or builtins from this PA, 
   but have different behavior than your compiler. For each, write:
   (a). Python program can compare more than two items, my compiler will throw an error message
        It's because my compiler currently only considers two cases: the number of arguments is 1 and 2. 
        May use an array to temporarily store the inputted items, then compare these items.

   (b). When the inputted number is not integer, my compiler will throw an error message
        My complier currently only supports type "i32"
        May change the type of parameters and allow non-integer inputs in the future. 

   
   (c). My compiler can currently only support three binary operations, addition, subtraction and multiplication, 
        and will throw an error message when applying binary division. 
        Since the result of binary division could be non-integer, I don't considers this operation right now.
        May change the type of return variable and implement binary division operation in the future.


2. What resources did you find most helpful in completing the assignment?
   Yousef's Tutorial. 

3. Who (if anyone) in the class did you work with on the assignment?
   None. 