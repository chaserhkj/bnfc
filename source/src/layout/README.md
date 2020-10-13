Andreas, 2020-10-11

- Alfa2.cf

  In comparison to /examples/Alfa, this directory contains a simpler
  version of the Alfa grammar.

- Sorting.alfa

  The file Sorting.alfa can be parsed with this grammar, but does not
  seem to make a lot of use of layout.  The version in /examples/Alfa
  has been modified to use some layout.

- Untok.hs

  Function to turn a token stream back into a string.

- ResolveLayoutAlfa.hs

  This seems to have been the original implementation of the layout
  resolution phase (placed between lexer and parser).  Should be
  obsolete now, since an improved layout resolver is generated by
  BNFC.