# Introduce a typo to make an error

Changing 'print' to 'printr' produces the following error:

`Traceback (most recent call last):
  File "C:\Users\rlewis\GitRepos\github.com\pythonCrashCourse\chapter1\Exercise1-2\hello_world_typo_error.py", line 1, in <module>
    printr("Hello Python world!")
NameError: name 'printr' is not defined. Did you mean: 'print'?`

It helpfully suggests that I meant 'print'!

Leaving out the closing parenthesis produces this error:

`PS C:\Users\rlewis\GitRepos\github.com\pythonCrashCourse\chapter1\Exercise1-2> python .\hello_world_typo_error.py
  File "C:\Users\rlewis\GitRepos\github.com\pythonCrashCourse\chapter1\Exercise1-2\hello_world_typo_error.py", line 1
    print("Hello Python world!"
         ^
SyntaxError: '(' was never closed`

Again, it helpfully tells me what I did.
