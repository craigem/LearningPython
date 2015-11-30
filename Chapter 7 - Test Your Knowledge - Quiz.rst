===========
 Chapter 7
===========


Test Your Knowledge: Quiz
-------------------------

#. Can the string find method be used to search a list?

    A) No as methods are always type specific.

#. Can a string slice expression be used on a list?

    A) Yes as expressions are generic and apply to many types.

#. How would you convert a character to its ASCII integer code? How would you convert the other way, from an integer to a character?

    A) str(integer), ie :str(42) and the reverse int("string"), ie: int("42")

#. How might you go about changing a string in Python?

    A) They are immutable so they cannot be changed. An new string will need to be created.

#. Given a string S with the value "s,pa,m" , name two ways to extract the two characters in the middle.

    .. code:: python
      :number-lines:

      S[2:4]
      S.split(',')[1]

#. How many characters are there in the string "a\nb\x1f\000d" ?

    A) 3

    .. code:: python
      :number-lines:

      >>> print("a\nb\x1f\000d")
      a
      bd

# Why might you use the string module instead of string method calls?

    A) Never, it's deprecated.
