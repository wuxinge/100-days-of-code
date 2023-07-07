# Day 2  Understanding Data Types and How to Manipulate Strings

## Learning Takeaways 
### Functions/Concepts 
* **type():** check data type
```
x = 5
print(type(x))
```

* **round(number, digits):** returns a floating point number that is a rounded version of the specified number, with the specified number of decimals.
  
* limiting floats problem: Most numbers cannot be exactly represented in floats. For example, round(2.675, 2) gives 2.67 instead of the expected 2.68. Alternatively, use:

* **format()** function
  ```
  '{:,.2f}'.format(1333.949999999)
  #result = 1333.95
  # it is a string
  ```
#### Data Types 
| Data Types    | Definition    | Examples |
| ------------- |:-------------| :-----|
| Integers      | whole numbers | 1234556|
| Float      | numbers with decimal places    |  3.1415|
| String | a string of characters      |    text |
| Boolean | represents one of two values: True or False.  |   True  |

#### Maths
| Arithmetic Operators   | Signs    | Examples |
| ------------- |:-------------| :-----|
| Add      | + | 5+1|
| Subtract      | -  |  5-2|
| Multiply | *      |    5*2 |
| Divide | /|   5/2  |
| Exponent | **  |  5**2  |

#### Data Casting
| Function   | Definition   | 
| ------------- |:-------------| 
|float()    | convert to float | 
|int()     | convert to int |  
|string() | convert to string     |    

### Syntax 
* **Subscript:** the method of pulling out a particular element from a string 
```[index]``` 
<br> index = the position of a character 
<br> programmers always start counting from 0.

* **The += operator:** takes the existing value in a variable and adds to it.
```
my_number = 4
my_number += 2
#result is 6
```
* **f-strings:** insert a variable into a string
```
days = 365
print(f"There are {days}in a year")
```

## Exercises 
* https://replit.com/@wuxinge/day-2-1-exercise
* https://replit.com/@wuxinge/day-2-2-exercise
* https://replit.com/@wuxinge/day-2-3-exercise

  
## Project 
![](tip_calculator.gif)

* https://replit.com/@wuxinge/day-2-project-tip-calculator 
