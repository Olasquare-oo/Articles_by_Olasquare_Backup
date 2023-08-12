---
title: "Python Programming for Beginners:
Jumpstart Your Coding Journey"
datePublished: Sun Jul 16 2023 17:00:39 GMT+0000 (Coordinated Universal Time)
cuid: clk5onozj000409ld4ssk7vfu
slug: python-programming-for-beginners-jumpstart-your-coding-journey
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/D9Zow2REm8U/upload/a12266c89a724f36df7997da9539d6ce.jpeg
tags: programming-blogs, python, python3, programming-languages, python-beginner

---

## An Introduction to Python

Python is arguably the most popular programming language in 2023 and is sometimes referred to as the future of programming languages.

Why is this so? Python is relatively easy to learn as a result of its simplified and English-like syntax.

Also, Python has gained so much popularity because of its speed and versatility. As a result of all these, python is being used by both programmers and non-programmers for a lot of tasks including automation.

### Python's use cases

Python can be used for a wide range of applications. The following are some of the main uses of Python:

* **Automation and Scripting**
    
    Automation is the use of technology (often software or scripts) to carry out operations automatically, requiring no ongoing human involvement.
    
    Scripting is the process of creating sets of instructions or code to automate particular operations or carry out specified actions.
    
* **Web Development**
    
    Web development is the process of designing, constructing, and maintaining websites and web applications that are accessible via the Internet.
    
* **Game Development**
    
    Game development is the process of creating video games or interactive digital entertainment experiences.
    
* **Desktop Applications**
    
    Desktop app development is the process of creating software applications that run on desktop computers or laptops.
    
* **Data Science and Data Analysis**
    
    [Data Analysis](https://en.wikipedia.org/wiki/Data_analysis) is a subfield of [Data Science](https://en.wikipedia.org/wiki/Data_science) that focuses on examining and interpreting data to uncover patterns, relationships, and meaningful insights.
    
* **Artificial Intelligence (AI) and Machine Learning (ML)**
    
    Artificial intelligence (AI) and machine learning (ML) are two related fields that focus on developing systems that can carry out activities that normally need human intelligence and learning abilities.
    
    While the term "artificial intelligence" (AI) refers to a variety of methods for mimicking human intelligence, "machine learning" (ML) is a subset of AI that focuses especially on enabling computers to learn from data and improve performance on particular tasks.
    

Finally, python has a large and supportive community, so help is always around the corner.

> This article is a guide for anyone looking to dive into the world of Python programming, including complete beginners. if you're new to programming and not sure what a programming language is, check out this [article](https://www.computerhope.com/jargon/p/programming-language.htm) to get a grasp of what programming languages are.

Let's get started, shall we?

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688173298050/13e9356c-3924-4305-a068-b0636ce7d1ae.jpeg align="center")

## Installation and Setup

Setting Python up is straightforward. visit [Python's](https://wiki.python.org/moin/BeginnersGuide/Download) official guide to download, install and setup Python up on your system.

![Python official download page ](https://cdn.hashnode.com/res/hashnode/image/upload/v1688458566863/28c50114-23a6-47ee-bb5d-95135a552b7d.jpeg align="center")

<div data-node-type="callout">
<div data-node-type="callout-emoji">⚠</div>
<div data-node-type="callout-text">Note: Make sure to mark the "Add Python to PATH" box shown below while installing Python. Else, you won't be able to access Python from your command prompt or terminal.</div>
</div>

Now that we're done downloading and installing Python, let's move on to some basic concepts in Python.

## Basics of Python

Python is a high-level, interpreted, programming language. High-level, which means Python is written in a syntax closer to human-readable form without having to deal with machine-specific or system details.

Interpreted languages like Python are executed by an interpreter program, which reads and executes the source code directly without having to first compile them into machine code.

Python, just like every other interpreted language has robust error-handling mechanisms. The interpreter can sight and report errors immediately with detailed error messages that help developers diagnose and fix issues quickly.

### Variables

Python variables are containers that hold values. They are used to store and manage data throughout your program.

Python variables are dynamically typed, which means you can assign different types of values to the same variable.

Here are some key points to note about Python variables:

1. **Variable Assignment**: Use an assignment operator `=` to create a variable and assign a value to it. For example:
    
    ```python
    var = "Hello, world!"
    
    print(var) # The print() function displays an output
    ```
    
    **Output:**
    
    `Hello, world!`
    
    `var` is the name of the variable and `"Hello, world!"` is the value assigned to it.
    
2. **Variable Reassignment**: You can reassign a new value to an existing variable, replacing the old one. The variable takes the new value from that point onwards. For example:
    
    ```python
    var = "Hello, world!"    # old value
    var = "Hello mates!"    # new value
    
    print(var)
    ```
    
    **Output:**
    
    `Hello mates!`
    
3. **Variable Names and Naming Conventions:** Python variables mostly follow the snake\_case naming convention, where words are separated by underscores. This is used when you wish to use more than one word to name a variable. For example, `my_name`, `my_user_name`.
    
    Certain rules should be followed when naming variables in Python, which include the following:
    

* They must start with a letter or an underscore.
    
* They can contain letters, digits, and underscores.
    
* They are case-sensitive, so `name` and `Name` are different variables.
    

> Note: "# The print() function displays an output" in our first example is called a comment.
> 
> In Python, comments are short descriptions added to code to increase its readability. Comments are always started with `#` .

Check out this [article](https://ijeomaonwuka.hashnode.dev/demystifying-python-variables-a-beginners-guide-examples) for a more in-depth look into Python variables.

### Data Types

In Python, the word "data type" refers to the classification of data that defines what can be done to the data as well as how the data is kept in memory. Data types define the nature and behavior of variables and objects.

There are multiple built-in data types in Python, each having unique properties and actions.

The following are commonly used data types in Python:

1. **Numeric Types:**
    
    * `int` represents an integer. Integers are positive or negative whole numbers without a fractional part. They are used for indexing and performing arithmetic operations. (eg: 5, -7, 0)
        
    * `float` represents a floating-point number. Floating-point numbers are decimal or fractional numbers with decimal points. They are used when precise decimal calculations are required. (eg: 2.1, -1.5, 4.0)
        
2. **Sequence Types:**
    
    * `str` represents a string. Strings are sequences of characters such as letters, numbers and symbols, enclosed in single quotes `''` or double quotes `""`. For example: `"Hello, world!"` , `"I'm 15yrs old :)"`.
        
    * `list` represents a list. Lists are ordered collections of items enclosed in square brackets `[]`. Lists can contain elements of different data types, and they are mutable (modifiable).
        
        They are commonly used for storing a collection of related items. For example: `[1, 2, 3, "Cats", Dogs", "Bunnies"]`.
        
    * `tuple` represents a tuple. Tuples are ordered collections of items enclosed in parentheses `()`. Tuples are similar to lists but are immutable (cannot be modified once created).
        
        They are used for storing values that should not change, and fixed data structures. For example: `("A1", "B2", "B3", "C4", "C5", "C6")`.
        
3. **Boolean Type:**
    
    * `bool` represents a boolean value. Booleans are logical values that can be either `True` or `False`.
        
        Boolean values are often used for conditional statements, logical operations and comparisons. They help in decision-making.
        
4. **Mapping Type:**
    
    * `dict` represents a dictionary. Dictionaries are collections of key-value pairs enclosed in curly braces `{}`. Dictionaries can help you organize and access data by using specific identifiers.
        
        They allow you to use a key to store and retrieve data. Each key is unique, and its value can be accessed using the key.
        
        For example: `{"babies": 6, "teenagers": 10, "adults": 3}`.
        
        *Note: In the example above,* `"babies"` *is the key and* `6` *is the value assigned to it.*
        

You can use the `type()` function to check the type of variable.

For example:

```python
a = 7
b = "Hello"

print(type(a))
print(type(b))
```

**Output:**

`<class 'int'>`

`<class 'str'>`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689201033222/3ea0a490-befe-43bc-8d50-f988b5000e74.png align="center")

### Input and Output Operations

The `input()` function is used to read user inputs from the console, while the `print()` function is used to display results or outputs.

The `input()` function reads a line of text entered by the user and returns it as a string. It can optionally take a string argument, which serves as the prompt or message displayed to the user.

> An argument is a value that is passed to a function when it is called.
> 
> In cases where a function takes multiple arguments, those arguments are separated by a comma.

For example:

```python
name = input("Enter your name: ")
print("Hello", name)
```

**Output:**

`Enter your name: Olamide`

`Hello Olamide`

> "Olamide" is the response entered by the user.

In the above example, the `input()` function prompts the user with the message "Enter your name: ". Whatever the user types in response will be stored in the variable `name`.

Next, the greeting message and user's name are displayed by the `print()` function.

**Let's move on to printing output.**

The `print()` function is used to display output to the console or terminal. It can take one or more arguments, which are separated by commas.

For example:

```python
name = "Olamide"
fav_color = "green"

print("My name is", name, "and my favorite color is", fav_color)
```

**Output:**

`My name is Olamide and my favorite color is green`

The `print()` function is used in the example above to show the values of the variables, `name` and `fav_color`.

You can also use formatted strings or f-strings to display output with variable values.

For example:

```python
name = "Olamide"
fav_color = "green"

print(f"My name is {name} and my favorite color is {fav_color}")
```

**Output:**

`My name is Olamide and my favorite color is green`

Formatted strings let you include the value of Python expressions (eg: a variable name) inside a string by prefixing the string with `f` before opening quotation marks.

Python expressions (e.g: variable names) are added to formatted strings by writing them between curly braces `{}`, as shown in the example above.

## Conclusion

Covering Python in one article is not feasible, much like any other natural or programming language.

In my future posts, we will explore further Python concepts including control flow, data structures, functions, and modules, among others.

Follow me to stay informed and avoid missing out.

**LinkedIn:** [Olamide Olabode](https://www.linkedin.com/in/olamide-olabode-a6bb12207)

**Twitter:** [i\_am\_olasquare](https://twitter.com/i_am_olasquare_)

Thank you for reading! I hope you found this article insightful.

*Happy learning!!!*

### References

[What is a programming language?](https://www.computerhope.com/jargon/p/programming-language.htm)

[Python's official download guide](https://wiki.python.org/moin/BeginnersGuide/Download)

[Demystifying Python Variables: A Beginner's Guide (+Examples)](https://ijeomaonwuka.hashnode.dev/demystifying-python-variables-a-beginners-guide-examples)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688210562397/1cdb2c7d-f544-44bc-b640-c6ded19a6367.webp align="center")