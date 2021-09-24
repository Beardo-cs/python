1. Fraction Project.
1. Implement the simple methods get_num and get_den that will return the numerator and denominator of a fraction.
Please refer to #1 comment in Fraction.py file (same directory) for solution to this problem.
Test code is added in the Fraction_main.py with #1 comment.
2. In many ways it would be better if all fractions were maintained in lowest terms right from the start. Modify the constructor for the Fraction class so that GCD is used to reduce fractions immediately. Notice that this means the __add__ function no longer needs to reduce. Make the necessary modifications.
Refer to #2 comment in the Fraction.py file (current directory)
3. Implement the remaining simple arithmetic operators ( __sub__ , __mul__ , and __truediv__ ).
Refer to #3 comment in the Fraction.py and Fraction_main.py files.
4. Implement the remaining relational operators ( __gt__ , __ge__ , __lt__ , __le__ , and __ne__ )  (greater than, greater than or equal to, less than, less than or equal to, not equal respectively).
Refer to #4 comment in the Fraction.py and Fraction_main.py files.
5. Modify the constructor for the fraction class so that it checks to make sure that the numerator and denominator are both integers. If either is not an integer the constructor should raise an exception.
Refer to #5 comment in the Fraction.py and Fraction_main.py files.
6. In the definition of fractions we assumed that negative fractions have a negative numerator and a positive denominator. Using a negative denominator would cause some of the relational operators to give incorrect results. In general, this is an unnecessary constraint. Modify the constructor to allow the user to pass a negative denominator so that all of the operators continue to work properly.
Refer to #6 comment in the Fraction.py file.
Please refer  Fraction.py and Fraction_main.py file.