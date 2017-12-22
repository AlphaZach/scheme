This file holds the tests that you create. Remember to import the python file(s)
you wish to test, along with any other modules you may need.
Run your tests with "python3 ok -t --suite SUITE_NAME --case CASE_NAME -v"
--------------------------------------------------------------------------------

Suite 1

    >>> from scheme_reader import *
    >>> from scheme import *

    Case Example
    	>>> read_line('(define (sum n total) (if (zero? n) total (sum (- n 1) 9)))')