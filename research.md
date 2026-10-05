---
layout: page
title: Research
number: 1.2
---

In 2027, I will begin a PhD program at [ALGO](https://algo.unige.ch/) at [DINFO](https://www.unige.ch/dinfo/en),
the computer science department of [UNIGE](https://www.unige.ch/en/),
under the supervision of [Arnaud Casteigts](https://arnaudcasteigts.net/).
Our group works on algorithm design and analysis. Some of the topics of research that interest us are as follows.

- **Computational complexity:** *How long does an algorithm that solves a specific problem take to run? Can problems where we can verify the solution quickly also be solved quickly?*
- **Temporal graphs:** *Take a graph and add a (discrete) dimension of time: now the edges appear and disappear. How does this affect our standard graph-theoretic notions like connectivity or acyclicity? What does a connected subgraph look like and when can we find a small one?*
- **Distributed algorithms:** *How can we design efficient algorithms when we have multiple processors available to us? How can we parallelize certain tasks?*
- **Quantum computing:** *If we were able to create a quantum computer, which problems can it outperform classical computers for?*

My studies are focused on Boolean satisfiability (SAT) and the inversion of Boolean circuits, viewed through the lens of parameterized complexity. Both problems are NP-complete in general, but modern SAT solvers routinely handle large industrial instances, which suggests that real-world instances carry hidden structure. I am interested in making this precise: representing formulas and circuits as graphs, identifying the structural parameters that govern their difficulty, and designing algorithms that exploit them. A motivating application is the cryptanalysis of block ciphers such as AES and Speck, where encryption circuits give rise to highly structured, yet hard, satisfiability instances. My mathematical background is in graph theory and combinatorics, and I am particularly drawn to the discrete mathematics underlying these questions.


### Publications

Coming soon!

<figure>
    <img src="assets/images/reading.jpg">
    <figcaption>Figure 3: Deep in research</figcaption>
</figure>

### Talks

Coming soon!

### Early research projects

*For a list of the handouts I've created as a teaching assistant and olympiad teacher, please check my [teaching page](/teaching.html).*

1. **Some topics in Ergodic Ramsey theory** (2024)\
Master's Thesis, ETH Zürich [[pdf]](/downloads/Master_Thesis.pdf)\
-----------------------------------------------------\
**Kurzgesagt:** *A survey on a number of concepts in ergodic Ramsey theory, including but not limited to sets of recurrence, sets of strong recurrence and van der Corput sets.*

2. **Vertex-critical graphs that are not edge-critical** (2023)\
Semester project, ETH Zürich [[pdf]](/downloads/VertexCriticalGraphs.pdf)\
-----------------------------------------------------\
**Kurzgesagt:** *A survey on a problem posed by Dirac on whether we can have $k$-vertex-colourable graphs where vertices are critical (removing a vertex and its adjacent edges makes the graph $k-1$-vertex colourable) but edges are not (removing an edge leaves the graph $k$-vertex-colourable).*

3. **Ramsey, size-Ramsey and induced size-Ramsey numbers** (2023)\
Semester project, ETH Zürich [[pdf]](/downloads/RamseyNumbersSurvey.pdf)\
-----------------------------------------------------\
**Kurzgesagt:** *A survey of notable results in graph theory concerning size-Ramsey and induced size-Ramsey numbers of certain graphs.*

4. **Applications of Van der Waerden’s Theorem in the ring of polynomials over $F_p$** (2022)\
Semester project, EPF Lausanne [[pdf]](/downloads/Bachelor_Thesis.pdf)\
-----------------------------------------------------\
**Kurzgesagt:** *A proof that van der Waerden's theorem, as well as a [result of Moreira](https://arxiv.org/abs/1605.01469) hold more generally in the ring of polynomials over $F_p$.*

The state-of-the-art results for the problem discussed in 2. (as of September 2026) can be found [here](https://arxiv.org/abs/2508.08703) and [here](https://arxiv.org/abs/2310.12891). 

### Other Research Interests

- Ramsey theory (Take a structure and colour it with finitely many colours. Which monochromatic structures are guaranteed to show up? For instance, on sufficiently large graphs we can find monochromatic cliques; on the integers, we can find sets closed under addition. Can we leverage probabilistic techniques to prove the existence of these structures without knowing where they actually are?) 
- Percolation (If we take a large, possibly infinite underlying graph - such as a lattice - and small, local structures exist randomly - such as edges - then what do we observe about the resultant graph? When is it connected, and at which probabilities do we observe a phase transition?)

### On Generative Artificial Intelligence

I am not completely opposed to the usage of large language models in mathematics, as I believe they can be valuable tools when used responsibly. In my own work, I use models for three main purposes:

- Literature search: AI is great for finding relevant papers and reading material for the topics and problems I am interested in.
- Testing my conjectures: although I try to find counterexamples to my own hypotheses by myself, as it is valuable for my own intuition, sometimes it is just practical to use AI to stress-test a lot of cases. 
- Help with coding: whilst I can usually design all the code I need, I am slow at writing code and not always familiar with the best techniques for implementation. 

That being said, I am opposed to using AI to replace the creative process. I believe the intrinsic value of mathematics is in building a shared pool of knowledge that humans can easily transmit to one other, and one thing we have been very good at and that I have yet to see AI reproduce is coming up with beautiful, truly original proofs. I have yet to read a proof produced by a model which is as satisfying to read as any of the gems in my favourite mathematical work, [Proofs from THE BOOK](https://en.wikipedia.org/wiki/Proofs_from_THE_BOOK). 

Whilst I believe there is in theory a context for ethical AI usage, it is less clear whether this is feasible in practice. Humans should be cautious about using LLMs (especially as they learn from our prompting) until we have more transparency on the business practices and decision-making at major AI firms, and until we are assured that appropriate safeguards are in place.  
