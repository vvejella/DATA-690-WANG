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
  - If the object is a function or instance method, the docstring, if defined we have to follow that function and call that function when we have to pass the arguments
#### Magic Command -
  - A magic command is any command prefixed by the percent symbol %. For example, we can check the execution time of any Python statement, such as a matrix multiplication, using the %timeitmagic function.
  - The %matplotlib magic function configures its integration with the IPython shell or Jupyter notebook. This is important, as otherwise plots we create will either not appear (notebook) or take control of the session until closed (shell).
#### Variables and Argument Passing -
  - When assigning a variable in Python, we are creating a reference to the object on the righthand side of the equals sign. 
  - When we pass objects as arguments to a function, new local variables are created referencing the original objects without any copying. If we bind a new object to a 
  variable inside a function, that change will not be reflected in the parent scope.
  - isinstance can accept a tuple of types if we want to check that an object’s type is among those present in the tuple.
#### Attributes and Methods:
  > Objects in Python typically have both attributes (other Python objects stored “inside” the object) and methods. Both of them are accessed via the syntax
obj.attribute_name:
  a.capitalize    a.format   a.isupper  a.rindex     a.strip
a.center          a.index    a.join     a.rjust      a.swapcase
a.count           a.isalnum  a.ljust    a.rpartition a.title
a.decode          a.isalpha  a.lower    a.rsplit     a.translate
a.encode          a.isdigit  a.lstrip   a.rstrip     a.upper
a.endswith        a.islower  a.partition a.split     a.zfill
a.expandtabs      a.isspace  a.replace   a.splitlines
a.find            a.istitle  a.rfind     a.startswith

#### Duck typing - 
  > isiterable function would return True for strings as well as most Python collection types.
#### Binary Operators - 
  > To check if two references refer to the same object, use the is keyword. is not is also perfectly valid if we want to check that two objects are not the same.
#### Mutable and immutable -
  > Mutable are changeable like list, tuples and strings immutable which we can't change.
#### Numeric types -
  > Integer division not resulting in a whole number will always yield a floating-point number
  > Integer division (which drops the fractional part if the result is not a whole number), use the floor division operator //.
#### Bytes and Unicode -
- We can convert this Unicode string to its UTF-8 bytes representation using the encode method
- We know the Unicode encoding of a bytes object, we can go back using the decode method
- It is most common to encounter bytes objects in the context of working with files, where implicitly decoding all data to Unicode strings may not be desired.
we can define your own byte literals by pre‐fixing a string with b.
#### Dates and Time:
- The built-in Python datetime module provides datetime, date, and time types. The datetime type, as we combines the information stored in date and time
- Given a datetime instance, we can extract the equivalent date and time objects by calling methods on the datetime of the same name
- The strftime method formats a datetime as a string
- Strings can be converted (parsed) into datetime objects with the strptime function.
#### Control flow:
- If, elif
- For
- While
### Teranary Expression -
> A ternary expression in Python allows us to combine an if-else block that produces a value into a single line or expression. The syntax for this in Python is:
value = true-expr if condition else false-expr

