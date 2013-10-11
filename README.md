TI-BASIC Programs
=================

The .tib source files provided here are compiled using [TI-Basic Compiler](http://tibasic.sourceforge.net/), which converts an ASCII .tib file into a binary .8xp file that can be sent to a calculator. You can transfer .8xp programs to Windows or Mac using Texas Instruments' official [TI-Connect](http://education.ti.com/en/us/products/computer_software/connectivity-software/ti-connect-software/features/features-summary) software; for Linux I suggest [TiLP](http://lpg.ticalc.org/prj_tilp/).

### Some assembly required

Unfortunately TI-Basic Compiler is slightly buggy, sometimes mangling the last few characters of programs. If you run into problems, open the program source on your calculator by going to `PRGM > EDIT` and try to manually re-type what appears at the bottom of the corresponding .tib file.

### Finance

- BINTREE2: Two-period binomial tree pricing for European/American puts/calls.
- BINTREE3: Three-period binomial tree pricing for European/American puts/calls.
- BSCHOLES: Black-Scholes formula.

### Games

- BLKJACK: Also known as 21.
- SIMON: The classic memory game.
