## Golden Sprial in TeX

This code typesets the digits of the golden ratio along the classic spiral
associated to that ratio.
The list of digits was obtained from [the Mathematics department at
Surrey](http://www.maths.surrey.ac.uk/hosted-sites/R.Knott/Fibonacci/phi10000dps.txt).

The number of digits stored is 10,001 (including the decimal point),
but for some unknown reason TeX can only do up to 9,999.  It claims to
run out of memory at that point.

(Note that the parameter includes the initial `1.` so actually typesets `N -
2` decimal places.)

In addition, for a different size diagram change the way that `\l__radius_fp`
is defined.  Currently, it produces a large diagram that almost fills the
page.
