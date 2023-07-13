# Day 6 Python Functions and Karel

## Learning Takeaways 
### Functions/Concepts 
* **Defining functions:** to specify what should do 
```
def my_function():
    #Do this
    #Then do this
    #Finally do this
```
* **Calling functions:** to execute the function
```
my_function()
```

* **While loop:** this is a loop that will keep repeating itself until the while condition becomes false.
```
while something_is_true:
    #Do this
    #Then do this
    #Finally do this
```
#### While loop vs For loop 
|while loop        |for loop        | 
| :------------- |:-------------| 
|carry out functionally many times until sort of condition is met     | when you want to iterate over something and you need to do something with each thing that you are iterating over | 

 ![](https://github.com/wuxinge/100-days-of-code/blob/eef10d39ba19cfe5f05a9b1454632d3a94847683/day%206/while%20loop%20vs%20for%20loop.png)

*** Method:** a function that “belongs to” an object. 
#### List methods 
```
fam = ['Liz', 1.73, 'emma', 1.68. 'mom', 1.71, 'dad', 1.89]

fam.index('mom') #result is 4
fam.count(1.73) #result is 1
```
#### str methods 
```
sister = 'liz'
sister.capitalize() #result is 'Liz'
sister.replace("z", "sa") #result is 'lisa'
```

## Exercises 
* [Hurdle 1](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Hurdle%201&url=worlds%2Ftutorial_en%2Fhurdle1.json)
![](hurdle1.gif)
```
def turn_right():
    turn_left()
    turn_left()
    turn_left()

def jump():
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()
        
for i in range(0,6):
    jump()
```

* [Hurdle 2](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Hurdle%202&url=worlds%2Ftutorial_en%2Fhurdle2.json)
![](hurdle2.gif)
```
def turn_right():
    turn_left()
    turn_left()
    turn_left()

def jump():
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()
        
while not at_goal():
    jump()
```
    
* [Hurdle 3](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Hurdle%203&url=worlds%2Ftutorial_en%2Fhurdle3.json)
![](hurdle3.gif)
```
def turn_right():
    turn_left()
    turn_left()
    turn_left()

def jump():
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()
        
while not at_goal():
    if wall_in_front():
        jump()
    else:
        move()
```

* [Hurdle 4](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Hurdle%204&url=worlds%2Ftutorial_en%2Fhurdle4.json)
![](hurdle4.gif)
```
def turn_right():
    turn_left()
    turn_left()
    turn_left()

def jump():
    turn_left()
    while wall_on_right():
        move()
    turn_right()
    move()
    turn_right()
    while front_is_clear():
        move()
    turn_left()
        
while not at_goal():
    if wall_in_front():
        jump()
    else:
        move()
````

## Projects 
![](lost_in_maze.gif)
```
def turn_right():
    turn_left()
    turn_left()
    turn_left()
while front_is_clear():
    move()
turn_left()

while not at_goal():
    if right_is_clear():
        turn_right()
        move()
    elif front_is_clear():
        move()
    else:
        turn_left()
```
* https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Maze&url=worlds%2Ftutorial_en%2Fmaze1.json

