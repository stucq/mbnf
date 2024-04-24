# Modern BNF (MBNF)

Modern BNF is an extension of BNF (not compatible with base BNF or extensions
like ISO EBNF) meant to be modern, pragmatic, and easy to read. The normative
reference for MBNF is its grammar, specified in MBNF itself in the file
[`syntax.mbnf`](./syntax.mbnf).

Contributions are always welcome, open an issue or a PR to contribute.

## TODO

It would be helpful to specify names for given values scanned and to specify
certain expressions whose values are ignored (this would always be the case for
string literals). If this is done, a full parser generator could hypothetically
be built around MBNF.
