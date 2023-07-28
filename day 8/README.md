# Day 8 Function Parameters & Cipher Caesar Game
## Learning Takeaways/Concepts 
1. **function**: take a complex set of instructions and packaging them together inside a block of code that has a name given to it
2. **Functions with inputs**
```
def my_function(something):
  #do this with something
  #then do this
  #finally do this 
```
  - **argument**: the actual value of data that's going to be passed over to the function when it's being called
  - **parameter**: the name of that data and we use the parameter inside the function to refer to it and to do things with it
3. **functions with more than 1 input**
    - order of the argument matters 
```
def greet_with(name, location):
  print(f"Hello {name}")
  print(f"This is {location}")

greet_with("Billie", "nowhere")
#"Hello Billie"
#"This is nowhere"

greet_with("nowhere", "Billie")
#"Hello nowhere"
#"This is Billie"
```
4. **Positional argument**: arguments that need to be included in the proper position or order
```
def my_function(a,b,c):

my_function(3,1,2)
#a=3, b=1, c=2
```   
5. **keyword argument**: values that, when passed into a function, are identifiable by specific parameter names
   - order does not matter the value of the argument
```
my_function(a=1, b=2, c=3)
```  
## Exercises 
* https://replit.com/@wuxinge/day-8-1-exercise
* https://replit.com/@wuxinge/day-8-2-exercise
## Project 

![](caesar_cipher_game.gif) 
* Final Version: https://replit.com/@wuxinge/day-8-project-caesar-cipher-4

* Step 1: create a function to encrypt the message <br>
https://replit.com/@wuxinge/day-8-project-caesar-cipher-1
* Step 2: create a function to decrypt the message and let the user choose either encrypt or decrypt functions <br>
https://replit.com/@wuxinge/day-8-project-caesar-cipher-2
* Step 3: combine both encrypt and decrypt functions into a single function Caesar <br>
https://replit.com/@wuxinge/day-8-project-caesar-cipher-3
