# Intro-to-Python
Python
Python is constantly growing in the market. With Python knowledge, you may find yourself in top positions within a few years, but you should increase your knowledge as much as possible.
Installing Anaconda on Windows
 To install Anaconda on Windows, follow these steps:

1. **Download Anaconda**:
Go to the Anaconda website at https://www.anaconda.com/products/distribution and download the Anaconda distribution for Windows. Choose the version that is appropriate for your system (typically 64-bit, unless you have a specific reason to use 32-bit).

2. **Run the Installer**:
Once the installer file is downloaded, locate it in your downloads folder and double-click to run it.

3. **Begin Installation**:
The Anaconda installer will start. Click "Next" to begin the installation.

4. **Read and Accept the License Agreement**:
Read the license agreement and, if you agree, click "I Agree."

5. **Choose the Installation Type**:
You can choose to install Anaconda just for your user or for all users on the system. It's usually recommended to select "Just Me."

6. **Select Installation Location**:
Choose the directory where Anaconda will be installed. The default location is typically fine, but you can change it if needed.

7. **Add Anaconda to System PATH Environment Variable**:
It's important to check the box that says "Add Anaconda to my PATH environment variable." This makes it easier to use Anaconda from the command line.

8. **Register Anaconda as the Default Python**:
You can choose to register Anaconda as your default Python. This makes Anaconda's Python the default Python interpreter on your system.

9. **Install Anaconda**:
Click "Install" to begin the installation. The installer will copy the necessary files to your computer.

10. **Installation Complete**:
Once the installation is complete, click "Next."

11. **Install Visual Studio Code (Optional)**:
Anaconda Navigator, which is included, offers a graphical interface for managing your Anaconda packages and environments. If you prefer, you can also install Visual Studio Code at this point.

12. **Finish**:
Click "Finish" to exit the installer.

13. **Verify the Installation**:
Open the Anaconda Navigator from your start menu and make sure it launches without any issues. You can also open a Command Prompt or Anaconda Prompt and type `conda list` to see a list of installed packages.

That's it! You've successfully installed Anaconda on your Windows system. You can now create Python environments, manage packages, and start working on data science and machine learning projects.
History of Python
 Python was conceived in the late 1980s and Guido van Rossum started implementing it at CWI in the Netherlands in December 1989. Python has become one of the most popular and versatile programming languages in the world, used in a wide range of applications, from web development and data analysis to scientific computing and machine learning. Its large and active community, along with a vast ecosystem of libraries and frameworks, has contributed to its enduring success.
Invoking the Interpreter
 Python was conceived in the late 1980s and Guido van Rossum started implementing it at CWI in the Netherlands in December 1989. Python has become one of the most popular and versatile programming languages in the world, used in a wide range of applications, from web development and data analysis to scientific computing and machine learning. Its large and active community, along with a vast ecosystem of libraries and frameworks, has contributed to its enduring success.
Interactive mode
 Interactive mode in Python refers to the way you can interact with the Python interpreter directly, one command at a time, and receive immediate feedback. You can run Python code interactively in several ways:

1. **Python Shell**: You can open a terminal or command prompt and simply type `python` (or `python3`, depending on your Python version). This opens the Python shell, and you can start entering Python commands and getting immediate results.

2. **IDLE (Integrated Development and Learning Environment)**: IDLE is Python's built-in Integrated Development Environment that includes an interactive mode. You can launch IDLE from your system's applications or by typing `idle` in your terminal.

3. **Jupyter Notebooks**: Jupyter notebooks provide an interactive environment for running Python code in a web-based interface. You can use Jupyter notebooks for interactive data analysis, visualization, and more.

Here's a brief example of using Python's interactive mode:

```python
>>> x = 5
>>> y = 10
>>> x + y
15
>>> name = "John"
>>> print("Hello, " + name)
Hello, John
```

In interactive mode, you can quickly test and experiment with small code snippets, perform calculations, and get immediate feedback. This is often useful for debugging, learning, and exploring Python's capabilities.

To exit the Python shell or IDLE, you can type `exit()` or use the keyboard shortcut (Ctrl+Z followed by Enter on Windows, or Ctrl+D on Unix-based systems). In Jupyter notebooks, you can simply close the notebook or use the appropriate menu options to shut down the kernel.
Comments in Python
 In programming, comments are a programming language construct used to insert human-readable text in the source code of a program. These extra pieces of text are ignored by the compiler and interpreter but can be potentially significant to programmers. Comments are added to make the source code easier to understand.
Day 2
Introduction to Variables
 Variables are a temporary storage space in a computer’s memory. When a variable’s value changes the program’s current state also changes. A variable acts as a container to hold a different number of data items or values. All programming languages use variables, as they are among the most important elements in programming, and that is why a good understanding of variables will only make your job easier when writing programs.

Every variable is created with an initial value. A variable can be in three states:

Variable creation (Declaration)
Variable assignment (Initialization)
Variable changed (Execution)
Once the code which created the variable has finished executing, the variable is destroyed.
Using variables
 All variables have to be assigned to a data type like a string (a series of characters) or an integer (positive and negative whole numbers).
Python has a powerful feature regarding the assignment. A variable is assigned automatically to an appropriate data type.
Casting
 In Python, casting refers to the process of converting one data type to another. This is also known as type conversion or type casting. Python provides various built-in functions that allow you to perform casting between different data types. Here are some common data type casting functions in Python:

1. **int()**: Used to convert a value to an integer.

   ```python
   x = 5.7
   y = int(x)
   ```

2. **float()**: Used to convert a value to a floating-point number.

   ```python
   x = 42
   y = float(x)
   ```

3. **str()**: Used to convert a value to a string.

   ```python
   x = 123
   y = str(x)
   ```

4. **bool()**: Used to convert a value to a boolean (True or False).

   ```python
   x = 0
   y = bool(x)
   ```

5. **list()**: Used to convert an iterable (e.g., a tuple or a string) to a list.

   ```python
   x = (1, 2, 3)
   y = list(x)
   ```

6. **tuple()**: Used to convert an iterable to a tuple.

   ```python
   x = [4, 5, 6]
   y = tuple(x)
   ```

7. **set()**: Used to convert an iterable to a set (removing duplicate elements).

   ```python
   x = [1, 2, 2, 3, 3, 4]
   y = set(x)
   ```

8. **dict()**: Used to create a dictionary from an iterable of key-value pairs.

   ```python
   x = [('a', 1), ('b', 2)]
   y = dict(x)
   ```

9. **ord()**: Used to get the Unicode code point of a character.

   ```python
   x = 'A'
   y = ord(x)
   ```

10. **chr()**: Used to get the character from a Unicode code point.

    ```python
    x = 65
    y = chr(x)
    ```

11. **hex()**: Used to convert an integer to a hexadecimal string.

    ```python
    x = 255
    y = hex(x)
    ```

12. **oct()**: Used to convert an integer to an octal string.

    ```python
    x = 64
    y = oct(x)
    ```

Casting is particularly useful when you need to ensure that a value is of a specific data type, or when you want to perform operations that require data in a particular format. Keep in mind that not all types can be converted to each other, and inappropriate casting may result in errors or unexpected results.
Defining Functions
 In Python, you can define a function using the `def` keyword followed by the function name, a pair of parentheses containing the function's parameters, a colon `:`, and an indented block of code that represents the function's body. Here's the basic syntax for defining a function:

```python
def function_name(parameters):
    # Function body
    # Code to execute
    return result  # Optional return statement
```

Let's break down the elements of a function definition:

1. `def`: This keyword is used to indicate the start of a function definition.

2. `function_name`: You should replace this with the name you want to give your function. Function names in Python should follow the same naming conventions as variable names (e.g., use lowercase letters and underscores for multi-word names).

3. `parameters` (optional): Inside the parentheses, you can specify zero or more parameters that the function accepts. Parameters are like variables that the function can use within its body. If your function doesn't require any parameters, you can leave the parentheses empty. For functions with multiple parameters, separate them with commas.

4. `:` (colon): The colon signifies the end of the function declaration and the beginning of the function body.

5. Function body: This is the indented block of code where you define what the function should do. You can use the parameters and write any Python code within this block.

6. `return` statement (optional): If your function is supposed to produce a result, you can use the `return` statement to specify what value the function should return. You can have multiple `return` statements within the function, but once a `return` statement is executed, the function's execution will stop, and the specified value will be returned. If no `return` statement is used, the function returns `None` by default.

Example of a simple function that adds two numbers:

```python
def add_numbers(a, b):
    result = a + b
    return result

# Calling the function
sum = add_numbers(3, 5)
print(sum)  # Output will be 8
```

You can define functions for a wide range of tasks in Python, from simple calculations to complex operations. Functions make your code more organized, reusable, and easier to understand.
Day 3
In Python, data types represent the type or category of values that a variable can hold. Understanding data types is crucial because they determine how data is stored in memory and what operations can be performed on that data. Python supports a variety of built-in data types. Here are some of the most common data types in Python:

1. **int**: Represents integers, which are whole numbers with no fractional or decimal part.

   Example:
   ```python
   x = 42
   ```

2. **float**: Represents floating-point numbers, which are real numbers with a decimal point or in exponential notation.

   Example:
   ```python
   y = 3.14
   ```

3. **str**: Represents strings, which are sequences of characters enclosed in single or double quotes.

   Example:
   ```python
   name = "Alice"
   ```

4. **bool**: Represents boolean values, which can be either `True` or `False`.

   Example:
   ```python
   is_sunny = True
   ```

5. **list**: Represents ordered, mutable sequences. Lists can contain elements of different data types.

   Example:
   ```python
   numbers = [1, 2, 3, 4, 5]
   ```

6. **tuple**: Represents ordered, immutable sequences. Like lists, tuples can contain elements of different data types.

   Example:
   ```python
   coordinates = (2.5, 4.0)
   ```

7. **set**: Represents an unordered collection of unique elements.

   Example:
   ```python
   unique_numbers = {1, 2, 3, 4, 5}
   ```

8. **dict**: Represents dictionaries, which are collections of key-value pairs.

   Example:
   ```python
   student = {"name": "Bob", "age": 20}
   ```

9. **NoneType (None)**: Represents a special data type for indicating the absence of a value. It is often used as a placeholder.

   Example:
   ```python
   result = None
   ```

10. **complex**: Represents complex numbers with real and imaginary parts.

   Example:
   ```python
   z = 2 + 3j
   ```

Float
These are the fundamental built-in data types in Python. Additionally, Python allows you to create your own custom data types using classes.

It's important to note that Python is dynamically typed, which means that the data type of a variable is determined at runtime. You don't need to explicitly specify the data type of a variable when declaring it; Python infers it based on the assigned value. This flexibility makes Python a versatile and easy-to-use language for a wide range of programming tasks.
In Python, floating-point numbers, often referred to as "floats," are a built-in data type used to represent real numbers with a fractional or decimal part. Floats are used to store both rational and irrational numbers. Here are some examples of floating-point numbers in Python:

```python
x = 3.14159
y = -0.5
z = 2.0
```

In these examples, `x` is a positive float, `y` is a negative float, and `z` is a float representing a whole number.

You can perform various mathematical operations on floating-point numbers, just like with integers. For example:

```python
a = 3.0
b = 1.5

sum_result = a + b  # Addition
difference_result = a - b  # Subtraction
product_result = a * b  # Multiplication
division_result = a / b  # Division
power_result = a ** b  # Exponentiation
```

In the code above, `sum_result` will be `4.5`, `difference_result` will be `1.5`, `product_result` will be `4.5`, `division_result` will be `2.0`, and `power_result` will be `5.196152422706632` (the result of 3.0 raised to the power of 1.5).

Floating-point numbers can represent a wide range of values, including values with very small or very large magnitudes. However, it's important to be aware that floating-point numbers have limited precision, which can lead to rounding errors in certain calculations. This is a common issue in numerical computing, and it's important to be cautious when comparing floating-point numbers for equality.

Python provides a built-in module called `math` that offers various mathematical functions for working with floats, and another module called `decimal` for higher precision decimal arithmetic when needed.

In summary, floating-point numbers are used in Python to handle real numbers with decimal components and are an essential part of numerical and scientific computing.
String
In Python, a string is a built-in data type used to represent a sequence of characters. Strings are enclosed in single (''), double (" "), or triple (''' ''' or """ """) quotes. Here are some examples of strings in Python:

```python
single_quoted_string = 'Hello, World!'
double_quoted_string = "Python Programming"
triple_quoted_string = '''This is a
multi-line string.'''
```

Strings are versatile and can contain letters, numbers, symbols, and even white spaces. They are used for various purposes, such as representing text, working with textual data, and manipulating strings in different ways.

Here are some common operations and examples involving strings in Python:

1. **Concatenation**: You can concatenate strings using the `+` operator:

   ```python
   first_name = "John"
   last_name = "Doe"
   full_name = first_name + " " + last_name
   ```

2. **Length**: You can find the length of a string using the `len()` function:

   ```python
   text = "Hello, World!"
   length = len(text)  # length will be 13
   ```

3. **Indexing and Slicing**: You can access individual characters or substrings of a string using indexing and slicing:

   ```python
   text = "Python"
   first_letter = text[0]  # Access the first character (P)
   substring = text[1:4]   # Slicing (yth)
   ```

4. **String Methods**: Python provides numerous built-in string methods for performing operations like changing case, splitting, joining, replacing, and more:

   ```python
   text = "Python Programming"
   lowercase = text.lower()         # Convert to lowercase
   uppercase = text.upper()         # Convert to uppercase
   words = text.split()             # Split into words
   new_text = text.replace("Python", "JavaScript")  # Replace substring
   ```

5. **String Formatting**: You can format strings using various methods, including f-strings and the `str.format()` method:

   ```python
   name = "Alice"
   age = 30
   formatted_string = f"My name is {name} and I am {age} years old."
   ```

6. **Escape Sequences**: Escape sequences are used to represent special characters within a string. For example, `\n` represents a newline, and `\"` represents a double quote within a string.

   ```python
   message = "This is a new line.\nThis is a \"quoted\" word."
   ```

Strings are a fundamental data type in Python and are widely used in text processing, input/output, and many other aspects of programming. Python provides a rich set of methods and features to work with strings, making it a powerful tool for text manipulation and data processing.
 Lambda Expressions
In Python, a lambda expression, also known as a lambda function, is a small, anonymous, one-liner function that can have any number of arguments but can only have one expression. Lambda functions are typically used when you need a simple function for a short period and don't want to define a full function using the `def` keyword. They are particularly useful in functional programming and are often used with functions like `map()`, `filter()`, and `reduce()`.

The basic syntax of a lambda expression is as follows:

```python
lambda arguments: expression
```

- `lambda`: This keyword is used to define a lambda function.
- `arguments`: These are the input parameters or arguments that the lambda function can accept. You can have zero or more arguments separated by commas.
- `expression`: This is a single Python expression that gets evaluated and returned as the result of the lambda function.

Here are some examples of lambda expressions:

1. A lambda function that adds two numbers:

```python
add = lambda x, y: x + y
result = add(3, 5)  # result will be 8
```

2. A lambda function that squares a number:

```python
square = lambda x: x ** 2
result = square(4)  # result will be 16
```

3. Using lambda with `sorted()` to sort a list of tuples by the second element:

```python
points = [(1, 5), (2, 3), (0, 8)]
sorted_points = sorted(points, key=lambda x: x[1])
# sorted_points will be [(2, 3), (1, 5), (0, 8)]
```

4. Using lambda with `filter()` to filter even numbers from a list:

```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8]
even_numbers = list(filter(lambda x: x % 2 == 0, numbers))
# even_numbers will be [2, 4, 6, 8]
```

Lambda functions are concise and can be handy in cases where a short, simple function is needed, but they are not suitable for more complex operations that require multiple statements or additional logic. In such cases, it's better to define a regular named function using the `def` keyword.
 Conventions about the content and formatting of documentation strings
In Python, documentation strings, often referred to as "docstrings," are used to provide documentation for modules, classes, functions, and methods. They serve as a form of inline documentation, helping developers understand how to use the code and what it does. Conventions for the content and formatting of docstrings are outlined in Python's PEP 257, which is a style guide for docstring conventions. Here are some key conventions for writing docstrings in Python:

1. **Triple Quotes**: Docstrings are enclosed in triple quotes (either triple single-quotes or triple double-quotes). The choice of single or double quotes should be consistent within your project.

2. **Module-Level Docstrings**: At the top of each module, you should include a module-level docstring that provides an overview of the module's purpose and functionality.

   ```python
   """
   This is a module-level docstring.
   It provides an overview of what this module does.
   """
   ```

3. **Function and Method Docstrings**: Functions and methods should have docstrings that describe their purpose, parameters, return values, and any exceptions they may raise. The docstring should be placed immediately after the function or method definition and should follow this format:

   ```python
   def function_name(param1, param2):
       """
       Brief description of the function.
       
       More detailed description of the function's purpose and behavior.

       :param param1: Description of the first parameter.
       :type param1: Data type of the first parameter (optional)
       :param param2: Description of the second parameter.
       :type param2: Data type of the second parameter (optional)
       :return: Description of the return value.
       :rtype: Data type of the return value (optional)
       :raises ExceptionType: Description of the exception (if applicable)
       """
       # Function code here
   ```

4. **Class Docstrings**: Classes should have docstrings that describe the class's purpose and provide an overview of its attributes and methods. The docstring should be placed immediately after the class definition.

   ```python
   class MyClass:
       """
       Brief description of the class.

       More detailed description of the class's purpose and behavior.
       """
       
       def __init__(self, param1):
           """
           Constructor for MyClass.

           :param param1: Description of the parameter.
           :type param1: Data type of the parameter (optional)
           """
           # Constructor code here
   ```

5. **One-Line Docstrings**: For simple functions or methods, a one-line docstring can be used. It should start and end with triple quotes and provide a concise description of the function's purpose.

   ```python
   def add(a, b):
       """Return the sum of two numbers."""
       return a + b
   ```

6. **Consistency**: Follow a consistent and readable style for your docstrings. Be clear, concise, and informative. Use proper punctuation and grammar.

7. **ReStructuredText**: While not required, it's common to format docstrings using ReStructuredText (reST) syntax. This allows for easy conversion to other documentation formats, such as HTML or PDF.

Day 4
The conventions outlined here are important for writing readable and maintainable code. Good documentation helps other developers understand and use your code, and it also helps tools like Sphinx generate documentation for your project. Following PEP 257 and other relevant style guides is recommended to ensure consistency and clarity in your docstrings.
Introduction to operators
 Operators are used to testing conditions and manipulating values. Most statements contain expressions: an example of an expression is: 2 + 3. When two objects of a different type, like str and int, are compared they are never equal, except for different numeric types like int and float which can be equal. The <, <=, > and >= operators raise a TypeError exception when any operand is a complex number if the objects are different types that cannot be compared to one another, or where there is no defined ordering.
Using Operators
 Operators in Python are special symbols or keywords that perform various operations on data and variables. They are used to manipulate values, perform arithmetic, make comparisons, and more. Python supports a wide range of operators, including:

1. **Arithmetic Operators**:
   - `+` (Addition)
   - `-` (Subtraction)
   - `*` (Multiplication)
   - `/` (Division)
   - `//` (Floor Division)
   - `%` (Modulo, Remainder)
   - `**` (Exponentiation)

   Example:
   ```python
   a = 10
   b = 3
   addition = a + b
   division = a / b
   exponentiation = a ** b
   ```

2. **Comparison Operators**:
   - `==` (Equal)
   - `!=` (Not Equal)
   - `<` (Less Than)
   - `>` (Greater Than)
   - `<=` (Less Than or Equal To)
   - `>=` (Greater Than or Equal To)

   Example:
   ```python
   x = 5
   y = 7
   is_equal = x == y
   is_less_than = x < y
   ```

3. **Logical Operators**:
   - `and` (Logical AND)
   - `or` (Logical OR)
   - `not` (Logical NOT)

   Example:
   ```python
   is_true = True
   is_false = False
   logical_and = is_true and is_false
   logical_not = not is_true
   ```

4. **Assignment Operators**:
   - `=` (Assignment)
   - `+=` (Add and Assign)
   - `-=` (Subtract and Assign)
   - `*=` (Multiply and Assign)
   - `/=` (Divide and Assign)

   Example:
   ```python
   x = 10
   x += 2  # x is now 12
   ```

5. **Bitwise Operators**:
   - `&` (Bitwise AND)
   - `|` (Bitwise OR)
   - `^` (Bitwise XOR)
   - `~` (Bitwise NOT)
   - `<<` (Left Shift)
   - `>>` (Right Shift)

   Example:
   ```python
   a = 5  # 101 in binary
   b = 3  # 011 in binary
   bitwise_and = a & b  # Result is 1 (001 in binary)
   ```

6. **Membership Operators**:
   - `in` (Checks if an element is in a sequence)
   - `not in` (Checks if an element is not in a sequence)

   Example:
   ```python
   fruits = ["apple", "banana", "cherry"]
   is_apple_in_fruits = "apple" in fruits
   ```

7. **Identity Operators**:
   - `is` (Checks if two objects are the same)
   - `is not` (Checks if two objects are not the same)

   Example:
   ```python
   x = [1, 2, 3]
   y = x
   are_same = x is y
   ```

8. **Other Operators**:
   - `:` (Colon, used for defining code blocks)
   - `,` (Comma, used to separate items in a list or tuple)
   - `.` (Dot, used to access object attributes or methods)

   Example:
   ```python
   numbers = [1, 2, 3]
   length = len(numbers)
   ```

Operators are fundamental to performing operations and making decisions in Python, and understanding how to use them is crucial for writing effective code. Depending on the context and the data you're working with, you'll use different operators to achieve specific tasks.
Activity 1
 # Input from the user
liters_of_water = float(input("Enter number of liters: "))

# Calculate the number of bottles that can be filled
bottles_filled = int(liters_of_water * 1000 // 500) # 500 ml per bottle

# Calculate the remaining water in liters
remaining_liters = liters_of_water - (bottles_filled * 500 / 1000)

# Print the message
print(f"{liters_of_water:.2f}L water will fill {bottles_filled} bottles ({remaining_liters:.2f}L remains)")
Activity 2
 # Prompt the user to input the millilitres of water released
millilitres_released = int(input("Enter the millilitres of water released: "))

# Convert millilitres to litres
litres_released = millilitres_released / 1000

# Calculate the litres remaining in the Albasini Dam
dam_capacity = 1000000 # 1 megalitre
litres_left = dam_capacity - litres_released

# Calculate the percentage of litres left
percentage_left = (litres_left / dam_capacity) * 100

# Generate the report
print("\nWater Conservation Report for Albasini Dam:")
print(f"Millilitres of water released: {millilitres_released} ml")
print(f"Litres of water released: {litres_released} L")
print(f"Litres of water remaining in the dam: {litres_left} L")
print(f"Percentage of litres remaining: {percentage_left:.2f}%"
 Operators are used to testing conditions and manipulating values. Most statements contain expressions: an example of an expression is: 2 + 3. When two objects of a different type, like str and int, are compared they are never equal, except for different numeric types like int and float which can be equal. The <, <=, > and >= operators raise a TypeError exception when any operand is a complex number if the objects are different types that cannot be compared to one another, or where there is no defined ordering.





