# hello-world
hello world code

hello github

def divide(x,y):
    try:
        result = x / y
    except ZeroDivisionError:
        print('division by zero!')
    else:
        print('result is ',result)
    finally:
        print('executing finally clause')

# try:
#     raise KeyboardInterrupt
# finally:
#     print('goodbye,world!')
# goodbye,world!
# Traceback (most recent call last):
#   File "D:/code/test/errors and exception.py", line 158, in <module>
#     raise KeyboardInterrupt
# KeyboardInterrupt
