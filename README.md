## Introduction to Git and GiTHub and overview of Python Classes

This page is a five minute read that will provide you with a brief introduction to git and github and their differences and their uses. It also covers an overview of python classes/objects with examples included.

### GIT
Is a version control system that lets you manage and keep track of your source code history.

### GITHUB
Is a cloud-based hosting service that lets you manage Git repositories.

### OVERVIEW OF PYTHON CLASSES/OBJECTS
**Class**  A user-defined prototype for an object that defines a set of attributes that characterize any object of the class.
```markdown
**Class Definition Syntax**

class ClassName:
    Statement-1
    
    
    Statement-N
```

**Object** Is an entity that has a state and behavior associated with it. It may be any real-world object like a mouse, keyboard, chair, table, pen, etc. Integers, strings, floating-point numbers, even arrays, and dictionaries, are all objects.

An object consists of :

    State : It is represented by the attributes of an object. It also reflects the properties of an object.
    Behavior : It is represented by the methods of an object. It also reflects the response of an object to other objects.
    Identity : It gives a unique name to an object and enables one object to interact with other objects.
    
    
To understand the state, behavior, and identity let us take the example of the class Student. 

    -The identity can be considered as the name of the student.
    -State or Attributes can be considered as the class, age, or gender of the student.
    -The behavior can be considered as to whether the student is studying or playing.    
    
   Creating an object
   ```markdown
       obj = Student()
   ```
   
   This will create an object named obj of the class Student
   
  **Self method**
  
 1. Class methods must have an extra first parameter in the method definition. We do not give a value for this parameter when we call the method, Python provides it
 2. If we have a method that takes no arguments, then we still have to have one argument.
 
 **The __init__ method**
 
 It is run as soon as an object of a class is instantiated. The method is useful to do any initialization you want to do with your object. 

**Creating Class and objects with methods**
```markdown
class Student:
  
    # class attribute
    attr1 = "Male"
  
    # Instance attribute
    def __init__(self, name):
        self.name = name
          
    def speak(self):
        print("My name is {}".format(self.name))
  
# Driver code
# Object instantiation
Rodger = Dog("Rodger")
Tommy = Dog("Tommy")
  
# Accessing class methods
Rodger.speak()
Tommy.speak()



```
**Output**

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
