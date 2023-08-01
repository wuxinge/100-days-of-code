# Day 10 Fuctions with Outputs 

## Learning Takeaways/Concepts 
* **return**: tells the computer that this is the end of the function and you should now exit the function
  ```
  def my_function():
    result = 3*2
    return result
  #output = 6
  ```
* return vs print
    * with return, I'm able to take the result from that calculation and plug it right back into another calculation function using the result of that function call as the input to another funciton call.
    * with print, it will just print the result but not cannot be used for further purposes
* **docstrings**: a way for us to create little bits of documentation as we are coding along in functions or in other blocks of code
  """ this is the docstrings """
    * can be on different lines (comments can only be on the same line)
 
* **recursion**: a function that calls itself
  ```
  def calculation():
    if something: 
      #do this
    else:
      #do that
      calculation()
  
  calculation()
  ```
## Exercise 
* https://replit.com/@wuxinge/day-10-1-exercise 
## Project: Calculator 
![](calculator.gif)
* https://replit.com/@wuxinge/day-10-project-calculator
