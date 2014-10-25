## Golden Sprial in TeX

This code typesets the digits of the golden ratio along the classic spiral
associated to that ratio.
The list of digits was obtained from [the Mathematics department at
Surrey](http://www.maths.surrey.ac.uk/hosted-sites/R.Knott/Fibonacci/phi10000dps.txt).

Up to 10,000 decimal places are allowed for in the code, but typsetting all of
them takes quite some time and normal TeX (aka `pdflatex`) runs out of memory.
Use `lualatex` or reduce the number of digits typeset by adjusting the
parameter to `\GoldenChars`.

(Note that the parameter includes the initial `1.` so actually typesets `N -
2` decimal places.)

In addition, for a different size diagram change the way that `\l__radius_fp`
is defined.  Currently, it produces a large diagram that almost fills the
page.

There's a fair amount of old code from previous versions buried in this which
could do with clearing out.
