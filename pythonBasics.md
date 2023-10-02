##<u>PYTHON</u> 


*guido van rossum* started working on python in 1980 as a successor of ABC programming. 

#####*<u>Design philosophy</u>*

* Python uses dynamic typing and a combination of reference counting and a cycle-detecting garbage collector for memory management. It uses dynamic name resolution (late binding), which binds method and variable names during program execution.

#####*<u>main motto</u>*
> 'Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated'.
Readability counts.

* ##### *<u>Comments</u>*
  it starts with # in python and multiline comments are without indentation between """ sdsf """

* ##### *<u>if else</u>*
>       if ---:
>       elif --:

* ##### *<u>Operators</u>*
>* *logical operators* : and, or, not.
>* *identity operators* : is | is not
>* *membership operators* : in | not in

    Note: in python / represent the float division and // represents the integer division.


* ##### *<u>For Loops</u>*
    In Python, for keyword is less in other keyword language. It works more like an iterator here.

        for eg: 
        fruits = ["yahoo","tum","pops"]
        for x in fruits:
        for x in range(2,5)
                
* ##### *<u>Lists Data type</u>*
   It Stores multiple items into a single variable and ordered.
      
        for eg:
        my_lists = ["Ram",1,2]
        my_lists+=["Sam",2.2,3]

* ##### *<u>Tuple Data type</u>*
   It Stores multiple items into a single variable but they are immutable and ordered.Mostly used in the return type of function.
      
        for eg:
        my_tuples = (1,2,2)
        #  my_lists+=(5)  it will throw an error

* ##### *<u>Difference between lists and tuple</u>*


| Lists  | Tuples |
| ------------- |:-------------:|
| mutable, i can add remove elements in same lists       | they are unmutable , for addming removing elements i have to create a new tuple    |
| requires more memory and processing overhead for especially for large collections, because python interpreter needs to allocate memory for potential changes.     | slightly faster and memory effecient due to immuatiblity     |

* ##### *<u>Sets Data type</u>*
   It Stores multiple items into a single variable but they should be unique and elements here unchangble, unordered, and unindxed. but we can add items here.
      
        for eg:
        my_sets = {"ram","shyam","sunny"}

* ##### *<u>Dictionary Data type</u>*
   It is used to store data values in Key:Value pairs. It's collection which is ordered, changeable but not allow duplicate values.
      
        for eg:
        my_dict = {
          "brand":"Royal Royce",
          "Model":"La Rose Noire Droptai",
          "Price":"2000000000"
        }

* ##### *<u>Lambda functions </u>*
   It is a small annonymous function used for creating simple, short, and one time use funtions.
      
      syntax:
      lambda arguments: expression
      eg: square = lambda x: x**2
          print(square(6))

* ##### *<u>Classes and Objects in python</u>*
  we use 'class' keyword to create to create a class in python. All Classes have __init__() funtion, which is always executed when the class is beign exectued.
    
      eg:
      class Person:
        def __init(self, name, age):
          self.name = name
          self.age = age
      P1 = Person()

  > __ str __() : funtions return the string reprsentation of the object.

  <u>*__self__ Parameter </u> :* reference to the current istance of the class and is used to access variable that belongs to that class. It should be first parameter of any function defined in the class.

   *Inheritance in python :* just the pass the parent class name to the child class's parameter. 
        
        eg: Class Student(Person):

* ##### *<u>Python Date and Time</u>*
In Python, we have 'datetime' module to work with dates. 

__Creating Date using datetime() constructor__ :

      my_date = datetime.datetime(2003,9,11)


__getting the current datetime using now() method__

__Formating datetime using strftime() method__

      eg: current_datetime.strftime("%Y-%M-%d")



* ##### *<u>Python JSON</u>*
used for storing and exchanging data , we have to import the module for that.

*<u>JSON loads():</u>* if we pass the json string into it , the result will be a dictionary.

*<u>JSON dumps():</u>*  it converts python objects into a json string.

* ##### *<u>Python Regex</u>*
used to check if a string contains a specific patterns or not. For that we have to import module 're'.

* ##### *<u>Python PIP</u>*
Package manager in python.

* ##### *<u>File Handling</u>*
*<u>open():</u>* it expects two arguments, filename and mode. for reading mode we dont have to specify it. we use readline() method to read a single line for multiple lines we loop through it.

* ##### *<u>Map function </u>*
it is used to apply a function to every item in an iterable(lists, tuple, or string) and returns a new iterable with the results.

      for eg:
      numbers = [1,2,3,4,5]
      squared_numbers = map(lambda x:x**2,numbers)
      squared_numbers_list = list(squared_numbers)

* ##### *<u>Range function </u>*
it returns a sequence of numbers, starting from 0 by default and increments by 1 default.

      Syntax : range(start,stop,step)

* ##### *<u>Center function </u>*
Center align will align the string, using a specified character 

      Syntax : string.center(length,parameter)











        


