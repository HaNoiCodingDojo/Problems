# Prime Filter

A prime number is the number which has the following properties:

- It is a **natural number**.
- It has exactly **2 distinct natural divisors**: 1 and itself.
  I.e. it's divisible only by 1 and itself.

For example:

* The following numbers are prime numbers: 2, 3, 11, 23, ...
* The following numbers are not prime numbers: 0, 1, 4, 10, 24, ...

Given a list of numbers, find out which numbers are prime numbers and
return the list of them in ascending order.  Elements in the result
list are not duplicated (see examples below).

For example:

    Input:  '(1 2 3 4 5 6 7)
    Output: '(2 3 5 7)

    Input:  '(12 2 5 12 10 5)
    Output: '(2 5)

    Input:  '(10 20 30 20 10)
    Output: '()
