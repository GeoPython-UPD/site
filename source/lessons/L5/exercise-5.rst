Exercise 5
==========

.. note::

    Please complete this exercise by **the start of the next lesson (01 March 2025, 1 PM)**.

.. admonition:: Start your assignment

    **You can start working on your copy of Exercise 5 by** `accepting the GitHub Classroom assignment <https://classroom.github.com/a/O5OJwD34>`__.

You can also take a look at the template repository for `Exercise 5 on GitHub <https://github.com/NIGS-GeoPython-2024/exercise-5>`__ (does not require logging in).
Note that you should not try to make changes to this copy of the exercise, but rather only to the copy available via GitHub Classroom.

.. admonition:: Pair programming (optional!)

    Students attending the course in UP Diliman, **if you wish, you can continue working in pairs**.
    Those students who want to submit their own solutions, let me know.

Cloud computing environments
-----------------------------

.. image:: https://img.shields.io/badge/Launch-CS_Hub-blue
   :target: http://jhub.science.upd.edu.ph/

.. image:: https://img.shields.io/badge/launch-binder-red.svg
   :target: https://mybinder.org/v2/gh/GeoPython-UPD/Binder/main?urlpath=lab
   

Exercise 5 hints
----------------

Below are some tips for working on Exercise 5.

Selecting date ranges
~~~~~~~~~~~~~~~~~~~~~

In the Part 3 of Problem 3, the aim is to select rows that belong to certain month. The key here is to understand that
the data values in the ``DATE`` column are a string using a format ``YYYY-MM-DD`` where ``YYYY`` is the
year of the observation, ``MM`` is the month, ``DD`` is the day, ``HH`` is the hour, and ``mm`` is the minute.

Using these values it is possible to make simple queries that take advantage of "alphabetical"/numerical sorting, such as finding the values starting from the beginning of August, 2017:

.. code-block:: python

    august_values = data.loc[data['DATE'] >= '2017-08-01']

Here, the value ``2017-08-01`` corresponds to the first day of August..