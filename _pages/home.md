---
title: ""
layout: splash
permalink: /
header:
   image: /assets/images/headerArial1.jpg
---
# About _**Jason**_

_**Jason**_ is an interpreter for an extended version of AgentSpeak. It implements the operational semantics of that language, and provides a platform for the development of multi-agent systems, with many user-customisable features. _**Jason**_ is available Open Source, and is distributed under GNU LGPL. 


## Download
Download the latest version of _**Jason**_ from [Github](https://github.com/jason-lang/jason/releases){:target="_blank"}. Older versions of _**Jason**_ are available on [SourceForge](https://sourceforge.net/projects/jason){:target="_blank"}.


## Resources
Check out the Documentation page for more details about _**Jason**_,
including examples and demos. Two particularly useful resources are
the [API documentation](/api/){:target="_blank"} and the [FAQ](/doc/faq){:target="_blank"}.


## Book
There is a separate site for the [Jason book](https://jason.sourceforge.net/jBook){:target="_blank"} published by Wiley.


## Authors
_**Jason**_ is developed by [Jomi F. Hübner](https://jomifred.github.io/){:target="_blank"} and [Rafael H. Bordini](https://www.inf.pucrs.br/r.bordini/){:target="_blank"}, based on previous work done with many colleagues, in particular Michael Fisher, Joyce Martins, Álvaro Moreira, Renata Vieira, Willem Visser, Mike Wooldridge, but also many others.

## _**Jason**_ Agent Language

One of the best known approaches to the development of cognitive
agents is the BDI (Beliefs-Desires-Intentions) architecture. In the
area of agent-oriented programming languages in particular, AgentSpeak
has been one of the most influential abstract languages based on the
BDI architecture. The type of agents programmed with AgentSpeak are
sometimes referred to as reactive planning systems. _**Jason**_ is a
fully-fledged interpreter for a much improved version of AgentSpeak,
including also speech-act based inter-agent communication. A
_**Jason**_ multi-agent system can be distributed over a network
effortlessly. Various ad hoc implementations of BDI systems exist, but
one important characteristic of AgentSpeak is its theoretical
foundation: it is an implementation of the operational semantics,
formally given to the AgentSpeak language and most of the extensions
available in _**Jason**_. Work on formal verification of AgentSpeak systems
also was quite important in the Agents literature. The language
interpreted by _**Jason**_ is an extension of the abstract programming
language called AgentSpeak(L), originally created by Anand Rao (see
the original paper
[here](https://link.springer.com/chapter/10.1007/BFb0031845)). Another
important characteristic of _**Jason**_ in comparison with other BDI agent
systems is that it is implemented in Java (thus multi-platform) and is
available Open Source, distributed under GNU LGPL.

Besides interpreting the original AgentSpeak language, _**Jason**_ also features:

* strong negation, so both closed-world assumption and open-world are available;
* handling of plan failures;
* speech-act based inter-agent communication (and belief annotations on information sources);
* annotations in beliefs used for meta-level information and annotations in plan labels that can be used by elaborate (e.g., decision-theoretic) selection functions;
* meta events, declarative goal annotations, higher order variables and treating plans as terms, imperative style commands in plan bodies, and various other language extensions;
* support for developing Environments (which are not normally to be programmed in AgentSpeak; in this case they are programmed in Java);
* support for MAS organisations and agents that reason about them,
using the Moise+ model, and environments using CArtAgO - see the
[JaCaMo website](https://jacamo-lang.github.io) for that;
* the possibility to run a multi-agent system distributed over a network (using [JADE](https://jade.tilab.com)); other distribution infrastructures can be added by the user;
* fully customisable (in Java) selection functions, trust functions, and overall agent architecture (perception, belief-revision, inter-agent communication, and acting);
* a library of essential “internal actions”;
* straightforward extensibility by user-defined internal actions, which are programmed in Java;
* various ways of developing and running code include IDEs and a “mind inspector” that helps debugging.
