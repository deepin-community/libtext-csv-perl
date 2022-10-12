Text::CSV version 1.33
----------------------

Text::CSV provides facilities for the composition and decomposition of
comma-separated values.  An instance of the Text::CSV class can combine
fields into a CSV string and parse a CSV string into fields.

The module accepts either strings or files as input and can utilize any
user-specified characters as delimiters, separators, and escapes so it is
perhaps better called ASV (anything separated values) rather than just CSV.

Please refer to the [complete documentation of Text::CSV](https://metacpan.org/pod/Text::CSV)
for more information.


#### Installation ####

    cpanm Text::CSV

Or manually:

    perl Makefile.PL
    make
    make test
    make install


#### Copyright and License ####

Copyright (C) 1997 Alan Citterman. All rights reserved.
Copyright (C) 2007-2015 Makamaka Hannyaharamitu. All rights reserved.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
