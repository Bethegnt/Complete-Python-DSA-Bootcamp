# Python 
python is a `high level`, `interpreted programming language` with easy-to-understand syntax, just like we use hindi or english to communicate with each other, we use a programming language like python to communicate with the computer. its a way to instruct the computer to perform various tasks. Python was `conceived in the late 1980's` by `Guido van rossum` at centrum wiskunde & informatica in the netherland as `successor of the ABC language.`

- Python 1.0 - 1994
- Python 2.0 - 2000
- Python 3.0 - 2008
- Latest version till now - 3.13.3 as per may 2025

The name `Python` is a tribute to the british comedy group `Monty Python.`
<br>

</br>

---
#  Why should learn python ?
- Huge community support.
- Future is with AI.
- Easy to learn and implement.
- General purpose programming language.
<br>

</br>

---
# Feature of python ?

1. **Simple and Easy to Learn**
> Python is `clean and readable`, without `semicolon (;)` and `curly brackets ({})`.
<br>

</br>

2.  **Interpreted Language**
> In python code is executed line by line, which makes debugging and testing easier.
<br>

</br>

3. **High-level Language**
> -  `Human-friendly syntax` - Its designed to be `easy for humans` to `read and write.` Just like we use English or Hindi to communicate with each other, we use Python to communicate with the computer — but in a way that is closer to natural language than other low-level programming languages.
> - `Abstraction from hardware` - You don’t need to manage complex details like memory allocation or CPU instructions. which allows developers to `focus on solving problems` rather than worrying about
system-level details.
> - `Readability & productivity `- The syntax is clean and simple, making it `easier for beginners.`
``` 
print("Hello, world!") 
```
<br>
</br>

4. **Highly Extensible** :
> - You can `integrate` Python with code from `C/C++ or other languages.`
> - The `flexibility` of Python increases because it can also work with other languages.
> - Example : Libraries like `Numpy`, `Pandas`, and `TensorFlow` are internally written in C languages, which makes Python fast. 
``` 
import numpy as np             # numpy written in c lang and use in py.
arr = np.array([1, 2, 3, 4])
print(arr) 
```
<br>

</br>

5. **Dynamic Typing and Dynamic Binding**
> - `Dynamic Typing` - you don't have to `declare the data type` of a `variable` before using it. The interpreter `automatically determines` the`type of variables` during `execution`. and also type can change. There is a `drawback` here as well. Due to excess flexibility, there is a chance of mistakes, especially in large programs beacuse of data types. That is why one has to focus on testing and debugging.
> - `Dynamic Binding` (Late Binding) - In Python means that the `method` or `function to be invoked` is determined at `runtime, not at compile time`. It is mainly used in `polymorphism`, where `overridden methods` are resolved dynamically based on the object’s type.
```
x = 5         # x is an integer
x = "Hello"   # now x is a string
x = 3.14      # now x is a float
```
<br>

</br>

6. **Rich Standard Library**
> - It already includes a `huge collection` of `built-in modules and packages` that you can use without installing anything extra. and each and every module has seperate offically documentions. 
<br>

</br>

7. **Cross-platform**
> - You can `run Python code` on `different operating systems`(mac,window,linux) without changing it.
<br>

</br>

8. **Object-Oriented**
> - Python supports Object-Oriented Programming (OOP), which helps in `structuring code` using `classes and objects`. Key concepts include `encapsulation`, `inheritance`, `polymorphism`, and `abstraction`. It makes code `modular`, `reusable`, and `easier to manage`.
<br>

</br>

9. **Automatic memory management**
> - `Refrence counting` - Whenever you `assign a value` to a variable, Python maintains a `reference count` for that value. When the `reference count becomes 0` (i.e. no variable is pointing to that value), Python `frees that memory`.
> - `Garbage collector` - Python has a `built-in garbage collector` that periodically `checks` whether any unused object is occupying the memory. If such an object is found, `Python automatically deletes` it – thereby clearing the memory.
```
# Refrence counting
a = [1, 2, 3]  # Reference created
b = a          # Reference count increases
del a          # Reference count decreases
del b          # Now reference count = 0 => memory freed

# Garbage collector
import gc     # gc = garbage collector
gc.collect()  # Forcefully runs garbage collection
```
<br>

</br>

10. **Indentation base block of code**
> - The structure of `code blocks` (like loops, functions, if-else, classes) in Python is based on indentation, not through curly braces {} like in C, C++ or Java. The `space or tab` at the `beginning of a line` is what helps Python understand which code belongs to which block.
```
x = 10
if x > 5:
    print("x is greater than 5")  # This line is indented and part of if-block
    print("Inside if block")      # Same block

print("Outside if block")         # Not indented, outside the if-block
```
<br>

</br>

---
# Where python can be used ?
- Developing websites
- Task automation
- Data visualization
- AI/Ml/IOT 
- Developing desktop applications
- Developing mobile applications
- Client based of AJAX based applications
<br>

</br>

---
# How to develop a software using python ?
`source file` → `hidden compiler turn into bytecode (.py file to .pyc)` → `Interpreter means PVM(Python Virtual Machine) which reads bytecode line by line` → `CPU run machine level code and perform the final action - output on screen.`
<br>

</br>

---
# How to run a py file or script ?

1. `Run from Terminal/Command Prompt/VSCode` - you use the python command followed by the script's filename to run it. 
```
python filename.py
```

2. `Run from Python Interactive Mode` - only for testing purpose, not for py files.
```
python
>>> print("hello Gagan")     # here >>> means python interpreter is ready to in use.
```

3. `Run from Jupyter Notebook (.ipynb)` - Use run button on top right or for mac press shift+command.