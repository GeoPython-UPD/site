.. Geo-Python documentation master file, created by
   sphinx-quickstart on Thu Aug 23 14:00:02 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. figure:: img/banner/geo-python-2020.png

Welcome to Geo-Python, UPD Geology edition!
===========================

The **Geo-Python** course teaches you the basic concepts of programming and scientific data analysis using the Python programming language
in a format that is easy to learn and understand (no previous programming experience required).
Each lesson is a tutorial with specific topic(s) where the aim is to gain skills and understanding
how to solve common data-related tasks using Python.

For Geol 197 GDAM and Geol 297 GDA, we have adapted the Geo-Python course originally offerred at the `Department of Geosciences and Geography <https://www.helsinki.fi/en/faculty-of-science/faculty/geosciences-and-geography>`__
at the University of Helsinki.

.. admonition:: Open Access!

    The course is **open for everyone to follow online**. The aim of this course is to share the knowledge and help people to get started with their journey for doing science more efficiently and in a reproducible manner
    using Python programming.

.. admonition:: To anyone accessing this course

    Now on the 4th year of offering, this course has content slightly tailored and localized towards the average senior-standing University fo the Philippines geology student.  The course is a work in progress, and we continue to improve the materials, so please forgive any inconsistencies or mistakes.  Contact us if you notice anything!

Course format
-------------

The course consists of interactive lectures and weekly exercises. The exercises will focus on developing
basic programming skills using Python and applying those skills to various analytical problems.
Typical exercises will involve a brief introduction followed by topical computer-based tasks.
For each exercise, you may be asked to submit the Python codes you have written, output figures and answers
to related questions. You are encouraged to discuss and work together with other students while working
on the weekly exercises. However, the exercises you submit must be completed individually and
must clearly reflect your own work (in short, don't copy paste from other students).


This course is used for the first 2/3 of two courses: Geology 197 Special Topics: Geoscience Data Analysis and Modeling Techniques, and Geology 297 Special Topics: Geoscience Data anlaysis.  The former is an undergraduate course designed to give students a taste of techniques in data science and advanced GIS (hence the name...). 
The latter is designed for graduate students who will work on a mini-project that may or may not be related to their thesis. 


Course topics
-------------

Upon completion of the course, students will be able to: 1) explain computer concepts applicable to both general and geologic use,
as well as 2) manipulate geologic data (raster data, vector data, and satellite imageries);

For the Geo-python part, students understand basic programming concepts,
are able to write short programs, and can manage, analyze and visualize scientific data using Python.
The students also learn to use version control (git) and online repositories (GitHub) for documenting and communicating their work.
Themes for each week are listed below. Read more about the weekly :doc:`learning goals in here <course-info/learning-goals>`.

New materials are updated on this course page each Saturday.

+----------+----------------------+
| Week     | Theme                |
+==========+======================+
|**1**     | Basic concepts of    |
|          | Python and           |
|          | computer programs    |
|          |                      |
+----------+----------------------+
|**2**     | Diving into Python   |
|          |                      |
|          |                      |
+----------+----------------------+
|**3**     | Repeating tasks      |
|          | and making decisions |
|          |                      |
|          |                      |
+----------+----------------------+
|**4**     | Creating and using   |
|          | functions            |
|          |                      |
+----------+----------------------+
|**5**     | Data analysis        |
|          | Part I               |
|          |                      |
+----------+----------------------+
|**6**     | Data analysis        |
|          | Part II +            |
|          | Dealing with errors  |
+----------+----------------------+
|**7**     | Data visualization   |
|          |                      |
|          |                      |
+----------+----------------------+
|**8**     | Basic geostatistics: |
|          | Univariate analysis  |
|          |                      |
+----------+----------------------+
|**9**     | Bivariate analysis   |
|          | and regressons       |
|          |                      |
+----------+----------------------+


.. admonition:: Step by step instructions with cloud computing!

    The materials are written in a way that you can follow them step by step exactly as they are written, as long as you use the cloud computing resources that
    we provide for you (namely JupyterLab Notebooks using Binder or the CS JupyterHub). Read more about our cloud computing environment from :doc:`here <lessons/L1/course-environment-components>`.
    If you work from your own computer, **you need to adjust the file paths to the data** accordingly.



.. toctree::
    :maxdepth: 2
    :caption: Course information

    course-info/course-info
    course-info/learning-goals
    course-info/grading
    course-info/licensing

.. toctree::
    :maxdepth: 2
    :caption: Lesson 1

    lessons/L1/motivation
    lessons/L1/overview
    lessons/L1/course-environment-components
    notebooks/L1/a-taste-of-python.ipynb
    notebooks/L1/gcp-1-variable-naming.ipynb
    lessons/L1/exercise-1

.. toctree::
    :maxdepth: 2
    :caption: Lesson 2

    lessons/L2/overview
    notebooks/L2/Python-basic-elements.ipynb
    lessons/L2/intro-to-GitHub
    lessons/L2/git-basics
    lessons/L2/GitHub-classroom
    notebooks/L2/gcp-2-describing-code.ipynb
    lessons/L2/why-pairs
    lessons/L2/exercise-2

.. toctree::
    :maxdepth: 2
    :caption: Resources

    course-info/python-vocabulary
    course-info/installing-miniconda
    course-info/resources

