Exercise 2
==========

.. note::

    Please complete this exercise by **the start of the next lesson**.

.. admonition:: Start your assignment

    **You can start working on your copy of Exercise 2 by** `accepting the GitHub Classroom assignment <https://classroom.github.com/a/j69Xfiow>`__.

You can also take a look at the template repository for `Exercise 2 on GitHub <https://github.com/NIGS-GeoPython-2024/Exercise-2>`__ (does not require logging in).
Note that you should not try to make changes to this copy of the exercise, but rather only to the copy available via GitHub Classroom.

.. admonition:: Pair programming

    Students attending the course in UP Diliman, **note that we continue working in pairs**.
    We will only grade the repository of the member of your pair that is responsible for this week's exercise.
    See more information in week 2: `Why are we working in pairs? <https://geo-python-upd.readthedocs.io/en/latest/lessons/L2/why-pairs.html>`_

Cloud computing environments
----------------------------

.. image:: https://img.shields.io/badge/launch-binder-red.svg
   :target: https://mybinder.org/v2/gh/GeoPython-UPD/Binder/main
   

Exercise 2 hints
----------------

Here are a few things that may be helpful in completing Exercise 2.

Git
~~~

You can find step-by-step instructions for using Git `here <git-basics.html>`__.
Remember to commit your changes after each major edit! Also, it's better to push your changes to GitHub frequently, rather than only at the very end of the exercise.

Indentation woes
~~~~~~~~~~~~~~~~

We have not really run into this problem in the lessons, but Python codes are sensitive to how much you indent the start of each line.
This is perhaps easiest to see with an example.

.. code:: python

    name = 'Dave'
        dogs = 0
    print('My name is', name, 'and I own', dogs, 'dogs.')

If you copy and paste this code into a **Jupyter Notebook** cell and run it, you will see that is gives an ``IndentationError``.

.. code:: python

        dogs = 0
        ^
    IndentationError: unexpected indent

We will see examples later of why indentation matters, but for now just be sure you don't indent lines to different levels.
Thus, the fix is simply to remove the spaces on the second line.

.. code:: python

    name = 'Dave'
    dogs = 0
    print('My name is', name, 'and I own', dogs, 'dogs.')

Now, running the code results in the expected output.

.. code:: python

    My name is Dave and I own 0 dogs.
