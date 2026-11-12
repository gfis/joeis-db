# joeis-db
Subset of jOEIS for program generation and testing

This repository is related to Sean Irvine's project https://github.com/archmageirvine/joeis, a
collection of pure Java programs implementing sequences from [The
On-Line Encyclopedia of Integer Sequences](https://oeis.org/) (OEIS).

The OEIS contains large groups of sequences with common definitions, for example:
* Linear Recurrences
* Ordinary generating functions
* Coordination sequences for tilings
* Cellular automata
* Continuous fraction expansions for square roots
* Decimal expansion of constants

In jOEIS, the sequences in such groups of OEIS sequences are usually implemented
by a common Java class that has one or more parameters.

The main assets in joeis-db are the parameter tables that allow the automatic generation
of programs for all sequences in a specific group. The tables are used in and tested by
the implementation of Java programs for jOEIS, but they can likewise be used to generate
Python, SageMath, C, PARI, Maple etc.

There is a Wiki with further details.
