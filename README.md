## Intro to C++ I

# Assign06T-FractionCalculatorII

**Date assigned:** 

**Program due:**

**Points:**

**This is an individual assignment.**

**Goals:**

1.  Code using well-defined functions

2.  Write one function at a time and test before going on

3.  Reuse existing functions as much as possible

4.  Don't copy and paste code

5.  Design your functions as much as possible before writing code

As children progress mathematically, they find the need to be able
to add, subtract, multiply, and divide rational numbers (fractions).
This topic can be quite confusing when numbers become positive and
negative. For instance, what is the simplified value of -1/2 - -2/3
or 2/-3 / -3/-2?

You are to write a program using well-defined functions that will
allow a child the ability to add, subtract, multiply, or divide
any rational number.

Here is exactly what your program is to output (asterisks and all), and
user input is in **bold**:

<pre>
*** Fraction Calculator ***

Enter: <b>-1/2 - -2/3</b>
Answer: 1/6

*** Fraction Calculator ***

Enter: <b>2/-3 / -3/-2</b>
Answer: -4/9

*** Fraction Calculator ***

Enter: <b>0/0 + 1/2</b>
</pre>

**Note1:** Each inputted value is to be \> 0.0. If an inputted value is
entered incorrectly, output the message "Incorrect Input -- Terminating
Program" Here is an example. You are to terminate the program
immediately when an illegal input occurs. **Further, there is to be only
one return statement at the end of your program.**

<pre>
*******************
Mortgage Calculator
*******************

Enter Purchase Price: $<b>115000.00</b>
Enter Down Payment: $<b>15000.00</b>
Enter Interest Rate: %<b>-1.0</b>
Incorrect Input - Terminating Program
</pre>

**Note2:** Do not use any C++ constructs not introduced in the class
thus far.**\
**

You will need to use the pow function. In order to use the pow function,
you will need to include the library cmath by using the preprocessor
directive #include \<cmath>. The pow function accepts two doubles and
returns a double. As an example,

cout \<\< pow (2.0, 3.0); // outputs 8.0 because 2.0<sup>3.0</sup> equals 8.0

**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**

    a.  You are to click on the Assign02 Link to accept this
        assignment as we've done in lab. Once accepted, code up a
        complete solution to the above assignment specification. Your
        complete solution is to be pushed to GitHub no later than the
        date and time specified above for your specific section. I will
        only grade your solution from the proper location on GitHub.

    b.  Pay attention to the example output above. Your program's output
        must look **exactly** like the example output! The spacing and
        newlines in your output must match exactly.

    c.  Make sure that your program compiles and runs correctly with no
        errors and no warnings. If you get any errors, double check that
        you typed everything correctly. Be aware that C++ is
        case-sensitive.

2.   **An electronic copy of your program (punetidAssign02FractionCalculator.pdf) is 
to be emailed to ryandj@pacificu.edu**
