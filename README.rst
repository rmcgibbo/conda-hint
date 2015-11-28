conda-hint
==========

Hint generation for conda resolver. Hints as to why a given set of conda package specs are unsatisfiable.

Examples
--------
::

  $ conda-hint 'numpy 1.9*' 'python 3.5*' scikit-learn
  $ conda-hint 'numpy'
