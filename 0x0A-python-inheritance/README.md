Project Name

0x0A. Python - Inheritance

Author's Details

Name: Amsal Fitsum

Email:amsalfessha21@gmail.com

Tel: +251961046155

TASKS

Lookup #mandatory Write a function that returns the list of available attributes and methods of an object:
Prototype: def lookup(obj): Returns a list object You are not allowed to import any module

My list #mandatory Write a class MyList that inherits from list:
Public instance method: def print_sorted(self): that prints the list, but sorted (ascending sort) You can assume that all the elements of the list will be of type int You are not allowed to import any module

Exact same object #mandatory Write a function that returns True if the object is exactly an instance of the specified class ; otherwise False.
Prototype: def is_same_class(obj, a_class): You are not allowed to import any module

Same class or inherit from #mandatory Write a function that returns True if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class ; otherwise False.
Prototype: def is_kind_of_class(obj, a_class): You are not allowed to import any module

Only sub class of #mandatory Write a function that returns True if the object is an instance of a class that inherited (directly or indirectly) from the specified class ; otherwise False.
Prototype: def inherits_from(obj, a_class): You are not allowed to import any module

Geometry module #mandatory Write an empty class BaseGeometry.
You are not allowed to import any module

Improve Geometry #mandatory Write a class BaseGeometry (based on 5-base_geometry.py).
Public instance method: def area(self): that raises an Exception with the message area() is not implemented You are not allowed to import any module

Integer validator #mandatory Write a class BaseGeometry (based on 6-base_geometry.py).
Public instance method: def area(self): that raises an Exception with the message area() is not implemented Public instance method: def integer_validator(self, name, value): that validates value: you can assume name is always a string if value is not an integer: raise a TypeError exception, with the message must be an integer if value is less or equal to 0: raise a ValueError exception with the message must be greater than 0 You are not allowed to import any module

Rectangle #mandatory Write a class Rectangle that inherits from BaseGeometry (7-base_geometry.py).
Instantiation with width and height: def init(self, width, height): width and height must be private. No getter or setter width and height must be positive integers, validated by integer_validator

Full rectangle #mandatory Write a class Rectangle that inherits from BaseGeometry (7-base_geometry.py). (task based on 8-rectangle.py)
Instantiation with width and height: def init(self, width, height):: width and height must be private. No getter or setter width and height must be positive integers validated by integer_validator the area() method must be implemented print() should print, and str() should return, the following rectangle description: [Rectangle] /

Square #1 #mandatory Write a class Square that inherits from Rectangle (9-rectangle.py):
Instantiation with size: def init(self, size):: size must be private. No getter or setter size must be a positive integer, validated by integer_validator the area() method must be implemented

Square #2 #mandatory Write a class Square that inherits from Rectangle (9-rectangle.py). (task based on 10-square.py).
Instantiation with size: def init(self, size):: size must be private. No getter or setter size must be a positive integer, validated by integer_validator the area() method must be implemented print() should print, and str() should return, the square description: [Square] /

My integer #advanced Write a class MyInt that inherits from int:
MyInt is a rebel. MyInt has == and != operators inverted You are not allowed to import any module

Can I? #advanced Write a function that adds a new attribute to an object if it’s possible:
Raise a TypeError exception, with the message can't add new attribute if the object can’t have new attribute You are not allowed to use try/except You are not allowed to import any module
