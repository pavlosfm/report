---
grknumber: 1763

studentname: Pavlos Marantidis
studentemail: pavlos.marantidis@tu-dresden.de
studenttopic: Quantitative Variants of Language Equations and their Applications to Description Logics

advisor: Prof.~Dr.-Ing.~Franz~Baader


bib-file: grk1763_lastnamefirstname.bib
---


<!-- What is the thesis about-->
Write a text any way you like.
New lines here do not mean new lines in the final text document.

But if you use an empty line, you can create an new paragraph.
If you want to use references make sure to name a file in the configuration part above and than use [@RefkeyS1] to set a reference [@RefkeyS2] and[@BaNa01].

\emph{Description Logics} are a family of knowledge representation languages with a 
formal, logic-based semantics. Reasoning methods developed for Description Logics 
provide powerful mechanism to process the represented knowledge by deriving implicit
consequences of the explicitly represented knowledge. Often though, when creating
the formal representation of the relevant knowledge of an application domain
in a team of knowledge engineers, redundancies are introduced in the form of concepts 
that are intended to be the same, but have different (even non-equivalent) formal 
representations. This is due to the fact that different knowledge engineers may model
concepts with different levels of granularity.
\emph{Unification in Description Logics} was introduced as a method for discovering such 
redundancies, also suggesting possible ways to remedy them by providing a unifier
[@BaNa01][@BaMo10].
However, the existence of an exact unifier, which makes the concepts equivalent, is sometimes
too strong a requirement for finding redundancies. 
To overcome this problem, we introduce \emph{approximate unification}, which searches for 
concepts that can be made ``similar" (with respect to a cetrain measure) rather than equivalent.
%It is thus a more robust indicator of redundancies.

Unification was first considered for the description logic 
$\mathcal{FL}_0$ by Baader and Narendran.[@BaNa01]. They reduce testing for unifiability and computing unifiers
to the problem of solving certain language equations.[@OkKu16]
Motivated by this construction, we reduce the problem of approximate unification
to approximately solving language equations with respect to some distance measure between languages.
Currently, we have introduced two (relatively simple) such measures
w.r.t.\ which we are exploring approximate solvability of language equations.
To do this, we modify already known automata-based methods for solving language equations[@BaOk13]
by introducing weighted versions of them.
Our present results guarantee the existence of a ``best" solution (i.e., one with the least distance between left- and right-hand side)
in all cases. Here solutions are (possibly) infinite lanuages,
and we are able to compute best solutions that are regular.
From the Description Logics point of view, these results are relevant for unification in the 
Description Logic $\mathcal{FL}_{reg}$[@BaKu01].
However, for unification in $\mathcal{FL}_0$ finite solutions are what is needed.
Currently, we are trying to extend the results for infinite approximate solvability to finite approximate solvability.

Afterwards, we will consider other, possibly more involved distance measures
from the formal language literature, with an emphasis on those that have a meaningful translation to description logics.
It will be interesting to investigate whether and how these translations correspond to the
similarity measures introduced by Andreas Ecke (QuantLA doctoral student in the first generation) in his thesis.
Further work is scheduled to include approximate unification 
in other, more expressive description logics.
Prior to this, the investigation of matching (a special case of unification)
could provide some basic instructive results.[@BKBM99] 
Finally, the addition of terminological knowledge (TBoxes) 
could be another direction to be considered. 

