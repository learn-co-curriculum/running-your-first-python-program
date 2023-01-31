# Running Your First Python Program

## Learning Goals

- Open a [Replit](https://replit.com/~) account.
- Set up a Replit Python environment.
- Run Python programs on Replit.

## Introduction

We have looked at what programming is and why we will be using Python. In this
lesson, we will learn which Python version to learn and how to set up an online
environment on Replit.

## Which Python Version Should I Use?

There are several versions of Python. If you go to
[Python.org](https://www.python.org/), you’ll find the latest version. You
should use Python 3.8+ when setting up your local environment.

For this course, we will be using an online environment which will set up
version `3.10.8`.

## Replit Set Up

We will be using Replit to run our code. Once you’ve gone through the course, we
highly recommend
[setting up a local environment](https://realpython.com/installing-python/) and
using an [IDE like PyCharm](https://www.jetbrains.com/pycharm/) to write,
manage, and run your projects.

### Sign Up Steps

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/01.png)

- Go to [https://replit.com/signup](https://replit.com/signup).
- Create an account. You can also use your Google, GitHub, Facebook, or Apple
  account to sign up.

### Create a Python Environment

- Go to the Replit homepage at [https://replit.com/](https://replit.com/).
  ![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/02.png)
- Under the “My Repls” section, click on “+ Create”.
  ![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/03.png)
- Search for the “Python” template and select it.
- Under title, name it “playground-python” (or whatever you prefer).
  ![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/04.png)
- Click on “+ Create Repl” to create and start the environment.

## Replit Environment Overview

You should see the following screen after following the previous steps:

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/05.png)

Let’s go over the key areas of the UI:

### Files

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/06.png)

- This is where we can create `.py` files which we can run using Python.
- You can ignore the files under “Packager files”, “Tools”, the resource section
  (CPU, RAM, Storage), and “Help”.

### Code Editor

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/07.png)

- This area is where we will be writing our code.
- The code written here by clicking on the green play button on top of the
  editor
  ![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/08.png)
- Note that the green button only runs the code in the
  `[main.py](http://main.py)` file. If you want to create new `.py` files and
  run the code, you’ll have to run a command in the “Shell” tab. We will only be
  running the `main.py` file.

### Console/Shell

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/09.png)

- The “Console” tab is where the output of our code will be displayed.
- The “Shell” area is where we can run Python or system commands. Try typing
  `python --version` in the “Shell” and press enter.
  ![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/10.png)
- Press on the trash icon on the top right to clear the “Shell”.

## Run Your First Program!

As mentioned earlier, we will be writing and running all of our code in the code
editor area. Write the following code in the editor. Programming languages are
very strict about their syntax so you need to write the code exactly as it is
written.

```python
print('Hello, world!')
```

Once you’ve written the code, click on the green play button on top of the
editor. The sentence “Hello, world!” will should show up in the “Console”!

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/11.png)

Here’s what the code is doing:

- `print`: It is a function (will be explained later) in Python which can be
  used to show output in the console.
- `()`: The parenthesis is where we supply the words that we want to output. Try
  changing `Hello, World!` to `Hello, your_name!` and run the program again!
- `''`: The quotation marks are required as it tells the computer that you are
  supplying text to the `print` function. Your program will run show an error if
  the words are not in quotation marks. We can also use `""` (double quotation
  marks) to represent text.

Try running the program without the quotation marks and observe what happens.

```python
# wrong code
print(Hello, world!)
```

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/12.png)

Note that the line that starts with a `#` is ignored by Python. This is called a
comment in programming languages. They are used to make notes about the code
that is run.

You should see the following error in the console:

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/13.png)

## An Alternate Way to Run the Code

We can also use the “Shell” to run the code. Follow these steps to run the code:

- Click on the “Shell” tab.
- Type `python main.py`.
- Press the enter button.

![Untitled](https://curriculum-content.s3.amazonaws.com/intro-to-coding-python/running-your-first-python-program/14.png)

The `python` command tells the environment to use Python to run a file. In this
case, we are specifying the `[main.py](http://main.py)` file.

Going forward, the output of programs will be shown as follows:

```python
Hello, World!
```

The above is what you would see in the “Console” tab of the Replit interface.

## Conclusion

Congrats on running your first program! In the following lessons, you should run
all of the code examples in the Replit environment.

Now that you understand the Replit interface and can run a program, we can start
learning more programming concepts!
