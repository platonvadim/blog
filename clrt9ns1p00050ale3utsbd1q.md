---
title: "#01 Python Programming for Beginners: Introduction"
datePublished: Thu Jan 25 2024 13:45:14 GMT+0000 (Coordinated Universal Time)
cuid: clrt9ns1p00050ale3utsbd1q
slug: 01-python-programming-for-beginners-introduction
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/npxXWgQ33ZQ/upload/9150543d8cfa7b1a7d58dbb80f44469f.jpeg
tags: python, coding, beginners, course

---

Hello everyone, and welcome to our very first **Python** programming lesson! Whether you're a curious kid, a teenager, or an adult eager to dive into the world of coding, you're in the right place. Today, we'll embark on an exciting journey to explore the basics of **Python** – a powerful and beginner-friendly programming language. I'm ***Vadim Platon***\*, master of engineering\*, and I'm thrilled to be your guide!

# Python Introduction

**Python** is not just a snake 🐍; it's also a programming language! It's like a set of instructions that computers understand and follow. Python is known for its simplicity, readability, and versatility, making it a great choice for beginners.

![Python Logo](https://cdn.worldvectorlogo.com/logos/python-6.svg align="center")

Python was created by [Guido van Rossum](https://en.wikipedia.org/wiki/Guido_van_Rossum) in the late 80s. First version was released in *20 February 1991*. It was designed as a high-level **Object Oriented** and **Functional** programming language. **TIOBE** Index for January 2024 awarded **Python** with 1st place (The most popular programming language it the world).

## Installation

Now, let's get started by installing Python on your computer. Don't worry; it's easier than it sounds. Just head over to [python.org](http://python.org), click on "**Downloads**," and follow the instructions for your operating system.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1706188084275/f6343b38-bb0c-4e67-abbc-ebc87d5c4b34.png align="center")

You can use any text editor to write code in Python, however I recomand to use **Sublime** or **PyCharm IDE**. There are links to some editors and IDE that you may use:

1. [Sublime Text](https://www.sublimetext.com/)
    
2. [Notepad](https://notepad-plus-plus.org/downloads/)++
    
3. [PyCharm](https://www.jetbrains.com/ru-ru/pycharm/)
    
4. [Visual Studio Code](https://code.visualstudio.com/download)
    
5. [Jupyter Notebook](https://jupyter.org/)
    

Another option, is to use online editor. It's good idea when you learning language, but if you want to write complicated programmes, it's better to use IDE.

## First line of code

Okay, now that we have Python installed, let's write our first program! Every programmer's journey begins with a simple *"Hello, World!"* program. Open your Python editor, type in `print("Hello, World!")`, and run it. Voila! You've just made your computer say hello to the world!

To run Python file just open terminal or command line and type this command:

```powershell
python filename.py
```

So, what did we just do? The `print()` function is like telling the computer to show something on the screen. In this case, we told it to display the text **"Hello, World!"** Pretty cool, huh? Let me explain it in more details.

| Thing | Explanation |
| --- | --- |
| *print* | Python built-in function name. This function outputs its parameters to screen. |
| *()* | **()** after function name are used to call function. Inside in parenthesis there are function parameters (objects that we send to function). |
| *"Hello, World!"* | String. Text in Python must be surrounded by quotation marks. |

## Reading characters from keyboard

Now, let's make our program a bit more interactive. We'll use variables to store information. For example, you can ask the user for their name using the `input()` function and store it in a variable. Try this: `name = input("What's your name? ")`. Then, print a personalized greeting using the variable: `print("Hello, " + name + "!")`.

```python
name = input("What's your name? ")
print("Hello, " + name + "!")
```

| Thing | Explanation |
| --- | --- |
| *name* | **variable**. Used to store and manipulate with some data. |
| *input()* | **function** that read text from keyboard. To end text introduction just hit **Enter** button. |
| + | (in this case) **concatenation**. Used to join 2 string variables. |

Let's run this code. Just type in your terminal `python filename.py`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1706190010437/40d892fa-c235-4e9a-9956-0904e80710ca.png align="center")

## Summing up

Great job, everyone! In this first lesson, we've learned how to install Python, write our first program, use variables for input, and even run the code. The journey has just begun, so keep practicing and experimenting with code. Remember, every programmer starts somewhere!

Thank you for joining me in this Python adventure! If you have any questions or topics you'd like to explore in future lessons, feel free to leave a comment below. Happy coding, and see you in the next lesson!