# test

```python
#!/usr/bin/env python

"""Summary of module.

Description of module.
Can contain multiple lines.

"""

__author__ = 'Name Surname <Email address>'
__version__ = '0.0.0'
__revision__ = '0000000'
__date__ = 'Mon Jan 01 00:00:00 2000 +0000'


# Imports
import package
import package.module
import package.module as mymodule
from package import module
from package import module as mymodule
from package import Class
from package import Class as MyClass
from package import module1, module2, Class1, Class2


# Variables
my_global_variable = "use underscores if needed"
print_ = "avoid collision with keywords"
MY_CONSTANT = 3.1415

# Functions
def my_function(a, b=""):
    """Summary of function.

    Description of function.
    Can contain multiple lines.

    Parameters:
    -----------
    a : int
        A variable.
    b : str, optional
        Another variable.

    Returns:
    --------
    rtn : int
        Sum of a and length of b.

    """

    return a + len(b)


# Classes
class MyClass(ParentClass):
    """Summary of class.

    Description of class.
    Can contain multiple lines.

    """

    class_variable = "a class variable"
    another_class_variabel = "another one"

    @staticmethod
    def static_method(*args):
        """Summary of static method.

        Description of static method.
        Can contain multiple lines.

        Parameters:
        -----------
        args* : list
            A list of arguments.

        """

        pass

    @classmethod
    def class_method(cls, *args):
        """Summary of class method

        Description of class method.
        Can contain multiple lines.

        Parameters:
        -----------
        args* : list
            A list of arguments.

        """

        pass

    def __init__(self, *args):
        """Summary of constructor.

        Description of constructor.
        Can contain multiple lines.


        Parameters:
        -----------
        args* : list
            A list of arguments.

        """

        ParentClass.__init__(self, *args)

        self.arg1 = "public argument"
        self._arg2 = "non-public argument"
        self.__arg3 = "non-public argument, avoids collision with subclasses"

    @property
    def arg2(self):
        """Getter for arg2."""

        return self._arg2

    @arg2.setter
    def arg2(self, value):
        """Setter for arg2."""

        self._arg2 = value

    def instance_method(self, *args):
        """Summary of instance method.

        Description of instance method.
        Can consist of multiple lines.


        Parameters:
        -----------
        args* : list
            A list of arguments.

        """
```
