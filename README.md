# maxima-stack

My [maxima](maxima.sourceforge.net/) snippets for use with [STACK](https://github.com/maths/moodle-qtype_stack/). Reading comments in the individual files may perhaps help a bit.

`generators.mac` contains several separate bits to generate small matrices with "nice" properties (e.g. integer, nice eigenvalues and eigenvectors, and such).

`q_perms_stack.mac` has functions that deal with permutations. It would be nicer if we could use the `combinatorics` maxima package in STACK, but that's too new at the moment.

`groups8.mac` has setup for question(s) about an 8-element group described by its group table.

`maximaout.tex` is a LaTeX file for transforming some raw "tex" maxima output into a pdf.

`sym3mats.txt` contains code for copy/pasting into STACK: it produces a random symmetric 3x3 matrix with small integer entries and distinct eigenvalues (one of which is an integer and the other two are not - with some small square roots). It is produced by some of the code in `generators.mac`.

`stack_rands.mac` and `rref.mac` are excerpts from STACK's maxima functions, so that I can use them in pure maxima for testing (note: the code in these files is [GPLv3](https://github.com/maths/moodle-qtype_stack/blob/master/COPYING.txt) licensed).

