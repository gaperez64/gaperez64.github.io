---
layout: post
title:  "Combinatorial Solving with Provably Correct Results"
date:   2025-02-26
categories: jekyll update
---

Combinatorial optimization problems are ubiquitous in our lives. They show up in the forms of matching problems (e.g., assigning junior doctors to hospitals), scheduling problems (e.g., radiation therapy), logistics problems (e.g., visiting nurses), and many more. In many cases, these problems are also notoriously hard (often NP-hard, or even worse). Still, thanks to tremendous progress over the last decades, we now have access to sophisticated algorithms that can solve these problems in practice. Unfortunately, it turns out that, due to their immense complexity, these (solving) algorithms often contain subtle bugs. In this tutorial, we give an overview of the most successful approach to dealing with this issue, namely proof logging, meaning that solvers aren't allowed to just claim an answer to a problem: they're expected to also produce an independently verifiable proof that backs up this claim. In the field of Boolean Satisfiability, this has done wonders for solver reliability and has also helped with social acceptability of computer-generated mathematical results. In this talk, we will start by explaining what a proof really is, and what it means for an algorithm to certify the correctness of its answers by using proof logging. We will give a brief overview of the (extended) resolution and DRAT proof systems used in SAT proof logging. We will do all this through the lens of pseudo-Boolean proof logging, which has also been used for proof logging graph algorithms, constraint programming, symmetry breaking, and more; while these applications are not handled, the current talk provides the basis for understanding the proof logging methods used there.

# Speaker
[Bart Bogaerts is research professor in DTAI, KU
Leuven.](https://www.bartbogaerts.eu/index.php)

# Time and Place
Wednesday 26/02/2025 at 13:45pm in M.A.143

# Registration
Participation is free, but registration is compulsory.
Make sure to fill in ...

# References and Related Reading
This talk will overlap for a large part with the first sections of [this tutorial](https://www.bartbogaerts.eu/talks/veripb-tutorial-series/).
Reading material & concrete examples can be found there. 

[Here is a concrete pointer for suggested reading](https://lucris.lub.lu.se/ws/portalfiles/portal/117886509/thesis_final_pdf.pdf)
