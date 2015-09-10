===========
 Chapter 6
===========


Test Your Knowledge: Quiz
-------------------------

1. Consider the following three statements. Do they change the value printed for A ?

    .. code:: python
      :number-lines:

      A = "spam"
      B = A
      B = "shrubbery"

    A) No because strings are immutable.

#. Consider these three statements. Do they change the printed value of A ? ::

        A = ["spam"]
        B = A
        B[0] = "shrubbery"

      A) Yes as they both point to the same object

#. How about these—is A changed now? ::

        A = ["spam"]
        B = A[:]
        B[0] = "shrubbery"

      A) No because A was copied using splicing.



.. code:: python
  :number-lines:

  A = "spam"
  B = A
  B = "shrubbery"
