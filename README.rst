conda-hint
==========

Hint generation for conda resolver. Hints as to why a given set of conda package specs are unsatisfiable.

Examples
--------
::

  $ conda-hint 'numpy 1.9*' 'python 3.5*' statsmodels
  $ conda-hint 'msmbuilder' 'numpy 1.9*' 'python 3.5*' --platform win-32

Installation
------------
::

  $ pip install git+git://github.com/rmcgibbo/conda-hint

Requires ``conda``, ``termcolor``, and Python 3.5+.
