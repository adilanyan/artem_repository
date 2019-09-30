I want to show you how to define a simple function, use a module, and add a variable.

Example:

First, we need to create a new file called define.py.

Then we need to define a simple function:

>>> def new_function()
>>>     print("Use this function")

Now we need need to create a new file named your_function.py. We can now import the function.py module and call the function:

>>> import define
>>> define.new_function()

Finally, we can our file named your_function.py. We will get the following result:

>>> Use this function

In addition, we can assigned a variable to our function. We need to define a variable into our define.py.

>>> def new_function()
>>>     print("Use this function")
>>> variable = "Please add a variable"

Now we can can a print() function in your_function.py file.

>>> import define
>>> define.new_function()
>>> print(define.variable)

If we run this program, we should get the following result:

>>> Use this function
>>> Please add a variable

Now you learned how you can insert a function into your module.
