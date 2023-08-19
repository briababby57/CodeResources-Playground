Classes and Objects
===================

.. contents:: Table of Contents
    :backlinks: none

List Attributes
---------------

.. code-block:: python

    >>> dir(list)  # check all attr of list
    ['__add__', '__class__', ...]

Get Instance Type
-----------------

.. code-block:: python

    >>> ex = 10
    >>> isinstance(ex, int)
    True

Declare a Class
---------------

.. code-block:: python

    >>> def fib(self, n):
    ...     if n <= 2:
    ...         return 1
    ...     return fib(self, n-1) + fib(self, n-2)
    ...
    >>> Fib = type('Fib', (object,), {'val': 10,
    ...                               'fib': fib})
    >>> f = Fib()
    >>> f.val
    10
    >>> f.fib(f.val)
    55
