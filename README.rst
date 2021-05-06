Cachier
#######

|PyPI-Status| |PyPI-Versions| |Build-Status| |Codecov| |Codefactor| |LICENCE|

Persistent, stale-free, local and cross-machine caching for Python functions.

.. code-block:: python

  from chardif import chardif
  import datetime

  chardif("rabbits"", "grab it")

.. role:: python(code)
  :language: python

.. image:: https://raw.githubusercontent.com/shaypal5/chardif/master/chardif_example.png?sanitize=true


.. contents::

.. section-numbering:



Installation
============

Install ``chardif`` with:

.. code-block:: python

    pip install chardif


Use
===

Just a single function, folks:

.. code-block:: python

  from chardif import chardif
  import datetime

  chardif("rabbits", "grab it")


Contributing
============

Package author and current maintainer is Shay Palachy (shay.palachy@gmail.com); You are more than welcome to approach him for help. Contributions are very welcomed.

Installing for development
--------------------------

Clone:

.. code-block:: bash

  git clone git@github.com:shaypal5/chardif.git


Install in development mode with test dependencies:

.. code-block:: bash

  cd chardif
  pip install -e ".[test]"


Running the tests
-----------------

To run the tests, call the ``pytest`` command in the repository's root, or:

.. code-block:: bash

  python -m pytest

To run only pickle core related tests, use:

.. code-block:: bash

  pytest -m mongo


Adding documentation
--------------------

This project is documented using the `numpy docstring conventions`_, which were chosen as they are perhaps the most widely-spread conventions that are both supported by common tools such as Sphinx and result in human-readable docstrings (in my personal opinion, of course). When documenting code you add to this project, please follow `these conventions`_.

.. _`numpy docstring conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt
.. _`these conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt


Credits
=======
Created by Shay Palachy (shay.palachy@gmail.com).

.. Contributers (in chronological order of first commit):

.. * `shaypal5 <https://github.com/shaypal5>`_ (Shay Palachy)
.. * `j-chad <https://github.com/j-chad>`_ (Jackson)



.. |PyPI-Status| image:: https://img.shields.io/pypi/v/chardif.svg
  :target: https://pypi.python.org/pypi/chardif

.. |PyPI-Versions| image:: https://img.shields.io/pypi/pyversions/chardif.svg
   :target: https://pypi.python.org/pypi/chardif

.. |Build-Status| image:: https://travis-ci.org/shaypal5/chardif.svg?branch=master
  :target: https://travis-ci.org/shaypal5/chardif

.. |LICENCE| image:: https://img.shields.io/pypi/l/chardif.svg
  :target: https://pypi.python.org/pypi/chardif

.. |Codecov| image:: https://codecov.io/github/shaypal5/chardif/coverage.svg?branch=master
   :target: https://codecov.io/github/shaypal5/chardif?branch=master

.. |Downloads| image:: https://pepy.tech/badge/chardif
     :target: https://pepy.tech/project/chardif
     :alt: PePy stats

.. |Codefactor| image:: https://www.codefactor.io/repository/github/shaypal5/chardif/badge?style=plastic
     :target: https://www.codefactor.io/repository/github/shaypal5/chardif
     :alt: Codefactor code quality

.. links:
.. _pymongo: https://api.mongodb.com/python/current/
.. _watchdog: https://github.com/gorakhargosh/watchdog