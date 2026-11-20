=========================================
Learning Microeconometrics with Python
=========================================

* This repository contains Python code using scipy, numpy, statsmodels and Scikit-Learn to reproduce a selection of computations, statistical tables, and figures from the book 'Learning Microeconometrics with R' by Christopher P. Adams (2020).

* Free software: MIT license


Use of AI
---------

* The notebooks of chapters 1 and 2 were written by hand by the author of the repository.

* The notebooks of chapters 3 to 12 and of appendix A were written with an AI assistant (Claude Code), from the R code of the book and in the style of the first two chapters.

* Each of these notebooks was run from top to bottom, and its results were compared with the results of the book. When a result is not the same as in the book, a short note in the notebook says why.

* The matrix inverse in chapter 2 (sections 2.3.2, 2.6.3 and 2.6.5) was corrected with the same assistant.


Data
----

* The data files are in the folder ``data``. The file ``data/README.rst`` lists the data file of each chapter, and where to download the large files which are not in the repository.


References
-------

* Christopher P. Adams (2020). Learning Microeconometrics with R, Chapman and Hall/CRC, ISBN 9780367255381. https://sites.google.com/view/microeconometricswithr

* This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
