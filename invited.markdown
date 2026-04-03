---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<h4 id="tutorial-title">Strategic and Symbolic Methods for Real-Time Systems in Maude</h4>

<p>

Rewriting logic is a powerful and expressive semantic framework for
modeling distributed real-time systems. This talk presents our journey
toward developing sound and complete symbolic analysis methods for
such systems by integrating rewriting modulo SMT and Maude's strategy
language.  We begin by introducing an encoding of networks of
parametric timed automata, where symbolic "tick" rules capture all
possible time advances using SMT variables. We then extend these
techniques to parametric time Petri nets (PITPNs). However, the
encoding of tick rules may result in non-termination of the
analysis. Hence, we propose a folding procedure based on quantifier
elimination that guarantees termination for NPTAVs and PITPNs whenever
the corresponding state class graph is finite.  In addition to
reachability analysis, parameter synthesis, and model checking, we
support analysis under user-defined execution strategies. This yields
a timed strategy language that enables the specification of execution
scenarios and efficient time-sampling strategies that focus on
"interesting" time points.  Finally, by combining symbolic techniqui  es
with strategies, we address the verification of real-time multi-agent
systems using Strategic Timed CTL (STCTL). In this setting, we show
how Maude's strategy language can capture the continuous semantics of
STCTL, resulting in the first verifier that supports full STCTL with
practical performance.

<h5 id="tutorial-author">Speaker: Carlos Olarte</h5>
<h6 id="tutorial-authors">Joint work with Jaime Arias, Kyungmin Bae, Peter Csaba Ölveczky, Wojciech Penczek, Laure Petrucci, Teofil Sidoruk, and Fredrik Rømming</h6>

<hr>

<h4 id="tutorial-title">Automated Quantum Protocol Verification with Concurrent Dynamic Quantum Logic in Maude</h4>

<p>

While constructing practical quantum computers remains a challenge,
applications of quantum communication and cryptography have made
remarkable progress. Therefore, it is crucial to formally verify
quantum protocols before they can be trusted in safety- and
security-critical applications. Dynamic Quantum Logic (DQL), a quantum
counterpart of Dynamic Logic, has been proposed to handle quantum
effects such as unitary transformations and measurements in order to
verify quantum protocols through manual proofs. However, DQL lacks
both an automated approach to quantum protocol verification and a
parallel operator for modeling concurrency among participants in
quantum protocols. This talk presents our recent developments in
automated quantum protocol verification with Concurrent Dynamic
Quantum Logic (CDQL), an extension of DQL for handling communication
and concurrent behaviors among participants in quantum
protocols. Additionally, this talk shows how large interleavings
arising from concurrency in CDQL can be handled effectively using a
supporting tool implemented in Maude.

<h5 id="tutorial-author">Speaker: Canh Minh Do</h5>
