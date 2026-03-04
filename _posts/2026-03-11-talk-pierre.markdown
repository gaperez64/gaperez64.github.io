---
layout: post
title:  "From PAs to POMDPs: Making Optimal Decisions Under Uncertainty"
date:   2026-03-11
categories: jekyll update
---

Stochasticity is essential in computer systems, both to make certain computations more efficient and to provide additional modelling power. In this talk, we discuss two prominent computational models that rely on stochasticity: probabilistic automata (PAs) and partially observable Markov decision processes (POMDPs).

Introduced in 1963 by Rabin, PAs were designed to give additional modelling power to standard (non)deterministic automata. Rabin demonstrated that while adding stochasticity makes automata strictly more expressive, it comes with a tradeoff: computational problems become vastly more difficult, many being undecidable. We will review the landscape of (un)decidability results for PAs.

PAs were initially studied as a theoretical model. Yet, they saw a resurgence of interest through the more general model of POMDPs, used in AI since the 1990s. POMDPs model stochastic environments where an agent must make sequential decisions. Building on the mechanics of PAs, the agent in a POMDP also receives some partial information about the current state at every time step (hence the "partially observable" in the name). This model has applications in fields such as robotics: robots must make decisions in stochastic environments using sensors that give them only partial information about their surroundings (e.g., they cannot see around a corner). We will discuss a few challenges in designing algorithms to synthesize optimal strategies in POMDPs.

# Speaker
[Pierre Vandenhove is research associate at UMONS.](https://pierre-vandenhove.github.io/)

# Time and Place
Wednesday 11/03/2026 at 13:45pm in M.G.006.

# Registration
Participation is free, but [registration is compulsory](https://forms.gle/iLJbZXatnmnHBHFu5). 

# References and Related Reading
* Foundational reference on probabilistic automata: Michael O. Rabin. "Probabilistic Automata". Information and Control 6(3): 230-245 (1963).
* Survey on PA undecidability, with concise and elegant proofs: Nathanaël Fijalkow. "Undecidability results for probabilistic automata". ACM SIGLOG News 4(4): 10-17 (2017).
* Introduction to POMDPs: Leslie Pack Kaelbling, Michael L. Littman, Anthony R. Cassandra. "Planning and Acting in Partially Observable Stochastic Domains". Artificial Intelligence 101(1-2): 99-134 (1998).
* Example of a recent algorithmic development (involving the speaker and Prof. Guillermo A. Pérez): Marius Belly, Nathanaël Fijalkow, Hugo Gimbert, Florian Horn, Guillermo A. Pérez, Pierre Vandenhove. "Revelations: A Decidable Class of POMDPs with Omega-Regular Objectives". AAAI 2025: 26454-26462.
