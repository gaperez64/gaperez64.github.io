---
layout: post
title:  "Advanced Topics in Complex Event Recognition"
date:   2026-04-22
categories: jekyll update
---

Complex event recognition (CER) requires both expressive pattern languages and efficient evaluation over high-throughput streams. This talk presents a unified formal foundation for CER based on a declarative language with precise, compositional semantics and a principled treatment of selection strategies. Queries are compiled into an automata-based model that enables efficient processing with constant-time updates per event and output-linear delay for enumerating matches, providing strong theoretical guarantees while clarifying the design space of event pattern languages.

Building on this foundation, the talk introduces an execution engine that realizes these ideas in practice through a compact automaton representation that avoids the explosion of intermediate matches. The system supports expressive features such as time windows and partition-based correlation while maintaining the desired efficiency properties. Experimental results demonstrate substantial performance improvements over prior approaches, illustrating that CER can be both expressive and scalable in real-world streaming settings.

# Speaker
Stijn Vansummeren is [professor at UHasselt](https://www.uhasselt.be/en/who-is-who/stijn-vansummeren).

# Time and Place
Wednesday 22/04/2026 at 13:45pm in M.G.006.

# Registration
Participation is free, but [registration is compulsory](https://forms.gle/t13kWN2Rzg25Dy7s7). 

# References and Related Reading
You may be interested in the papers the content for this talk covers:
* A Formal Framework for Complex Event Recognition ACM TODS 46(4), 2021
* CORE: a Complex Event Recognition Engine VLDB 2022
* https://dl.acm.org/doi/pdf/10.1145/3093742.3095106 (short paper by Stijn, from a long time ago, covering some basic ideas)
* https://link.springer.com/article/10.1007/s00778-019-00557-w  (very long survey,  but sections 1 and 2 may provide some introduction)

