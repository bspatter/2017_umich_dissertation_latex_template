# 2017_umich_dissertation_latex_template
University of Michigan 2017 dissertation latex template - Rackham complient
# Adapted by Brandon Patterson, 2017 - awesome@umich.edu

The two most important files meeting Rackham dissertation guidelines
are main.tex and thesis-umich.cls. These two files dictate the
structure and form of the dissertation.  In theory, you should only
need to change main.tex and its dependencies. Only modify
thesis-umich.cls if necessary, because .cls errors often don't produce
useful debug messages and it can it can be a pain to debug.

To compile, run ./compile_main.sh in a terminal. This effectively
runs pdflatex and bibtex enough times and in the right order to handle
all labels and references.  This script also filters out a lot of
unuseful compile output information, making it easier to find errors.

Good luck!
