+++
title = "MERC"
description = "MERC formal verification tool."
+++

I am the owner of the [MERCorg](https://github.com/MERCorg/) GitHub
organisation, where I experiment with my ideas for a new model checking tool
written in the Rust programming language. It's main project is
[MERC](https://github.com/MERCorg/merc), as an experimental successor to the
various model checking tools; among others [mCRL2](https://www.mcrl2.org/),
[CADP](http://cadp.inria.fr/) and [ltsmin](https://ltsmin.utwente.nl/). Within
this project I have the complete freedom to explore my ideas of how I believe
software should be developed.

As a greenfield project there are many distinct advantages in terms of software
quality based on lessons learned from the mCRL2 toolset, which at large is also
written by researchers whose main focus is extending the theory and not
necessarily software engineering. However, in this project we also demonstrate
that Rust is a viable language for developing performant software.

So far, this toolset has been used in several scientific publications,
including:

- Jan J.M. Martens and Maurice Laveaux. Faster Signature Refinement for Branching Bisimilarity Minimization. TACAS 2026.

- Menno Bartels, Maurice Laveaux, Thomas Neele, Tim A. C. Willemse:
Control Flow-Based Symmetry Reduction for Parameterised Boolean Equation Systems. FORTE 2026.

- Maurice H. Beek, Maurice Laveaux, Erik P. de Vink, Tim A.C. Willemse: Family-Based Model Checking Using VPG. In submission.

# Advantages

Both C++ and Rust are at a similar level of abstraction as far as programming
languages are concerned, and generally the same can be achieved in either
language. However, there are several clear advantages of using Rust.

# AI usage

Parts of the MERC toolset are generated using large language models (LLMs) both
for learning opportunities, and to explore the potential of LLMs in software
development. As far as code generation is concerned, this is mostly the
`merc_typecheck` crate.

# Benchmarking

