# Python language basics 
#### Python Interpreter - 
1. Python is an interpreted language. The Python interpreter runs a program by executing one statement at a time. 
we can run it by executing the following command (the hello_world.py file must be in your current working terminal directory): 
                       $ python hello_world.py 
2. We can execute arbitrary Python statements by typing them in and pressing Return (or Enter). When we type just a variable into IPython, it renders a string representa‐
tion of the object:
#### Running Jupyter notebook -
1. One of the major components of the Jupyter project is the notebook, a type of interactive document for code, text (with or without markup), data visualizations, and other
output.
2. To create a new notebook, click the New button and select the “Python 3”. If this is our first time,try clicking on the empty code “cell” and entering a line of Python code. Then press Shift-Enter to execute it.
3. When we save the notebook (see “Save and Checkpoint” under the notebook File menu), it creates a file with the extension .ipynb
#### Tab Completion -
-  Tab completion is found in many IDEs, While entering expressions in the shell, pressing the Tab key will search the namespace for any variables (objects,functions, etc.) 
1. For List we have some methods like:
b.append     b.count    b.insert  b.reverse
b.clear      b.extend   b.pop     b.sort
b.copy       b.index    b.remove
2. For Datetime module we have:
 datetime.<Tab>
datetime.date       datetime.MAXYEAR      datetime.timedelta
datetime.datetime   datetime.MINYEAR      datetime.timezone
datetime.datetime_CAPI   datetime.time    datetime.tzinfo
####  Introspection-
  >  If the object is a function or instance method, the docstring, if defined we have to follow that function and call that function when we have to pass the arguments
#### Magic Command -
  > A magic command is any command prefixed by the percent symbol %. For example, we can check the execution time of any Python statement, such as a matrix multiplication, using the %timeitmagic function.
  > The %matplotlib magic function configures its integration with the IPython shell or Jupyter notebook. This is important, as otherwise plots we create will either not appear (notebook) or take control of the session until closed (shell).
#### Variables and Argument Passing -
  - When assigning a variable in Python, we are creating a reference to the object on the righthand side of the equals sign. 
  - When we pass objects as arguments to a function, new local variables are created referencing the original objects without any copying. If we bind a new object to a 
  variable inside a function, that change will not be reflected in the parent scope.
  - isinstance can accept a tuple of types if we want to check that an object’s type is among those present in the tuple.
#### Attributes and Methods:
  > Objects in Python typically have both attributes (other Python objects stored “inside” the object) and methods. Both of them are accessed via the syntax
obj.attribute_name:
#### Duck typing - 
  > isiterable function would return True for strings as well as most Python collection types.
