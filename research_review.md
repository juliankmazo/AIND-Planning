# Research Review

## STRIPS
The main development in the field of AI planning that we're gonna analyze is [STRIPS](http://ai.stanford.edu/~nilsson/OnlinePubs-Nils/PublishedPapers/strips.pdf), the first major planing
system.

STRIPS is a problem-solving program and it stands for Stanford Research Institute Problem Solver. They
created a language that represents a world model as an arbitrary collection of first-order predicate calculus
formulas and it's designed to work with models consisting of large number of formulas.
The task of a problem solver is to find a composition of operators that transforms a a initial world model into one that satisfies some
goal. It does it trough applicable operators that transforms the world model to some other world model.
This framework for problem solving has been pretty important to later artificial intelligence research since it's the
foundation for planning research.

## ADL

[ADL](http://dl.acm.org/citation.cfm?id=112954) adopted a more flexible kind of STRIP in 1987. Action Description
Language. This language relaxed some of the restrictions of STRIP. ADL planning is a PSPACE-complete problem.
For example, STRIPS only allows positive literals in the states, while ADL allows both positive and
negative literals.

## PDDL
Planning Domain Definition Language [(PDDL)](http://www.cs.cmu.edu/~mmv/planning/readings/98aips-PDDL.pdf), a problem specification language is intended to express the "physics" of a domain.
What predicates there are and what actions are possible (and the effects of each action). The language supported
basic STRIPS-style actions. The goal with this language was to tie all the research in the search and planning
domain together and standardize it so all AI researches in the planning space could use.

