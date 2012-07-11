Javascript:

    parseInt(1 / 0, 19)
    18


Python:

    >>> int(1/0, 19)
    Traceback (most recent call last):
      File "<stdin>", line 1, in <module>
    ZeroDivisionError: integer division or modulo by zero
    >>> int("Infinity", 19)
    Traceback (most recent call last):
      File "<stdin>", line 1, in <module>
    ValueError: invalid literal for int() with base 19: 'Infinity'
    >>> int("I", 19)
    18
    >>>
    
via [http://stackoverflow.com/questions/11340673/why-does-parseint1-0-19-return-18](http://stackoverflow.com/questions/11340673/why-does-parseint1-0-19-return-18)