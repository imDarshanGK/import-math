# import math
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
# math fmod
import math fmod

math.fmod(x,y)

 * Input: Two real numbers x & y, y ≠ 0
 * Return Type: Floating-point number
  
This function takes two numbers as input and returns the floating remainder when x is divided by y. By floating-point remainder, we mean that the result is a number r = x - n*y for some integer n such that r has the same sign as the sign of x and the absolute value of r is less than the absolute value of y.

solution:

     2.0
# math inf
math.inf

Infinity

infinity refers to anything limitless or never-ending in both directions of the actual number line. Numbers cannot adequately represent it. The math.inf returns positive infinity constant. We can use-math.inf to print negative infinity. 

Syntax:

        math.inf
solution:        
        
        inf
       -inf
# math log
import math log

math.log()

Returns the natural logarithm of n.

Syntax:

      math.log(n, base)
      
base is optional and it's the logarithmic base to use.

solutio:

      3.1354942159291497
# math tau
math.tau

Tau

Tau is defined as the ratio of the circumference to the radius of a circle. The math.tau constant returns the value tau: 6.283185307179586

syntax:

        math.tau
        
solution:
        
        6.283185307179586
# import time as t

    1698813990.1599178
    time.struct_time(tm_year=2023, tm_mon=11, tm_mday=1, tm_hour=10, tm_min=16, tm_sec=30, tm_wday=2, tm_yday=305, tm_isdst=0)
    Wed Nov  1 10:16:30 2023
# import power
import power

The pow(x,y) function returns the value of x to the power of y(x^y)

Return the value of 4 to the power of 3 (same as 4*4*4):

    64
# import fabs
import math

math.fabs(x)

*Input:Real number

*Return Type: Floating-point number

This function returns the absolute value of the number given as an argument. By absolute, we mean that if the number is -5 it would become positive i.e.5.

The number on the left side of the origin on the x-axis becomes positive i.e it gets multiplied by -1 when returned. Example, math.fabs(-5.4) = ((-1)x(-5.4))=5.4

solution:

     13.4
# math isfinite
math.isfinite

* Input: A real number
* Return Type: Boolean value

solution:

     True

math.isinf(x)

* Input: A real number.
* Return type: Boolean value

This function takes a number x as an argument and returns true if x is infinite else it returns false.

solution:

    r= False
# math floor
import math math.floor

The math.floor() method rounds a number DOWN to the nearest integer, if necessary, and returns the result.

Tip: To round a number UP to the nearest integer, look at the math.ceil() method

Syntax:

       math.floor()
       
Solutions:

        0
        11
        15
        -6
        122
        10
        111
        1110
