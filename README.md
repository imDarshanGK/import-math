# import-math
math modules in python  



    720
    120
    6
    1
    5.0
    5.830951894845301
    24
    585
    8.06225774829855
    2.23606797749979
    78125.0
    1679616.0

math radians

* Input: A real number.
* Return Type: A floating-point number.

This function takes one number x in degrees as input and returns the converted value of x in radians.

solution:

     3.141592653589793

math acos

* Input: A real number
* Return Type: A floating-point number

This function takes one number x and returns the arc cosine of x in radians. The value returned lines between 0 and pi

solution:

     0.6761305095606613
     
  math.ldexp
  
* Input: A real number and an integer.
* Return type: A floating-point number.

This function takes a real number x and an integer i as arguments and returns the value of the expression x*2i.

solution:

    l= 80.0

math.erfc(x)

* Input: A real number
* Return type: A floating-point number

This function takes a number x as an argument and returns the complement of the error function of x

solution:

     v= 1.6715105790914593e-07
     
math fsum

* Input: An integrable object containing real numbers.
* Return type: A floating-point number.

This function takes an integrable object like a list as an argument and returns the floating-point sum of the iterable object.

solution:

      3.3
# math comb
import math

math.comb(n,r)

 * Input: Positive integers n and r

* Return Type: Integer number

This function takes two positive integers as input and returns the value of nCr i.e. the number of ways of choosing r items from n items without any repetition and without any order. In terms of real life, let there be 14 books on a shelf: A B C D Then, the ways of selecting 14 books out of 2 books are as follows :

A B A C A D B C B D C D

In total there are 91 ways of selecting them without repetition. This is what the value of math.comb(14,2) = 91 means. This function would give an error when negative numbers are given as input.

solution:

           91
