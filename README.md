# wordle-cheat

Usage:

`/home/rbowen/bin/wordle -m '.a.b.c' -i 'str' -o 'qxz'`

Prints words that match the pattern -m, includes the letters -i, and omits the letters -o

Pro tip: You can also do stuff like `-m '..[^xy]..'` to indicate that x and y are included, just not in that spot. 

Yes, of course it's cheating.

Requires Perl and the `Getopt::Long` module.

Assumes the presence of `/usr/share/dict/words` (present on most Linux systems).
