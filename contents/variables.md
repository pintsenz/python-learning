# **variables** 
variables are created when values are assigned 
x= ,y= 
can be printed using print(x)
do not need to be decalred with any particuler type 
## casting 
if you want to specify the variable 
## comments 
can be placed in beginning or end of a code 
multi line needs to be inserted each line for new comment 
## type
can get it by using type()

## quotes and case
string variables can be declared by single or double quotes
variables are cas sensitive!
# **variable names** 
- must start with a letter or underscore    
- name cannot start with number     
- name can only contain alpha numeric characters     
- case sensitive!   
**camel case**  
myVariableName  
**Pascal case**
MyVariableName  
**Snake case**  
my_variable_name    

# **assign multiple values** 
- x, y, z = "xx", "yy", "zz"    
- x = y = z = "vv"  
**Unpack collection**
you can extract values into variables -- unpacking 
- fruits = ["apple", "banana", "cherry"]    
- x, y, z = fruits 
- print(x)...
# **output variables**
the print() is often used to output variables   
multiple variables can be printed by comma  
- print(x, y, z)
- print(x+y+z)  
- the + sign is also for addition so it is best to separate by comma    
# **global variables** 
variables that are created outside of a function    
a variable with the same name inside a function can only be used inside the function    
- def myfun(): will define the variable that is inside the function 
- def myfunc(): 
- x= "great"
- print(x)  
the x=great only applies inside the function    
# **the global keyword**
- variables created inside a function is local  
- global will create a global variable inside a function
- can also change variables inside a function using global