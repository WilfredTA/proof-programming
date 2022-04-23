# Proof Programming

This repository contains proof engineering examples utilizing the [Athena](http://proofcentral.org/athena/) proof development language.

Some of the content is modified adaptation of examples taken from the book [*Fundamental Proof Methods in Computer Science*](http://proofcentral.org/).

Athena was developed by Konstantine Arkoudas at MIT where he formalized a class of languages referred to as ["Denotational Proof Languages"](https://dspace.mit.edu/handle/1721.1/81531)

# Contents

The `predicate-logic` directory contains a module of useful methods for reasoning with quantifiers.

The `propositional-logic` directory contains:
1. A module of useful methods for propositional reasoning
2. An example implementation of a dpll-based SAT solver
3. An example of applying the SAT solver to the graph-coloring problem

The `programming_languages` directory contains examples of formal syntax & semantics of programming languages, as well implementations (and accompanying proofs of correctness) of the language (e.g., compiler, interpreter, etc.). Currently, this directory only contains a toy language for arithmetic called "Calculator Language".

It is based on chapter 17 of FPMICS with some modifications.

