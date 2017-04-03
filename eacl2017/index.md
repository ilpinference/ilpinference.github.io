---
layout: page
title: Tutorial at EACL 2017


links:
- url: /eacl2017
  title: Overview
- url: /eacl2017/outline.html
  title: "Outline & Slides"
- url: /eacl2017/references.html
  title: References

---

[Dan Roth](http://l2r.cs.illinois.edu) and [Vivek Srikumar](http://svivek.com)

Making decisions in natural language processing problems often
involves assigning values to sets of interdependent variables where
the expressive dependency structure can influence, or even dictate
what assignments are possible. This setting includes a broad range of
structured prediction problems such as semantic role labeling, named
entity and relation recognition, co-reference resolution, dependency
parsing and semantic parsing. The setting is also appropriate for
cases that may require making global decisions that involve multiple
components, possibly pre-designed or pre-learned, as in event
recognition and analysis, summarization, paraphrasing, textual
entailment and question answering. In all these cases, it is natural
to formulate the decision problem as a constrained optimization
problem, with an objective function that is composed of learned
models, subject to domain or problem specific constraints.

Over the last few years, starting with a couple of papers written by
(Roth & Yih, 2004, 2005), dozens of papers have been using the Integer
linear programming (ILP) formulation developed there, including
several award-winning papers (e.g., (Martins, Smith, & Xing, 2009;
Koo, Rush, Collins, Jaakkola, & Sontag., 2010; Berant, Dagan, &
Goldberger, 2011, Berant et al 2014)).

This tutorial will present the key ingredients of ILP formulations of
natural language processing problems, aiming at guiding readers
through the key modeling steps, explaining the learning and inference
paradigms and exemplifying these by providing examples from the
literature. We will cover a range of topics, from the theoretical
foundations of learning and inference with ILP models, to practical
modeling guides, to software packages and applications.

The goal of this tutorial is to introduce the computational framework
to broader ACL community, motivate it as a generic framework for
learning and inference in global NLP decision problems, present some
of the key theoretical and practical issues involved and survey some
of the existing applications of it as a way to promote further
development of the framework and additional applications. We will also
make connections with some of the “hot” topics in current NLP research
and show how they can be used within the general framework proposed
here. The tutorial will thus be useful for many of the senior and
junior researchers that have interest in global decision problems in
NLP, providing a concise overview of recent perspectives and research
results.

