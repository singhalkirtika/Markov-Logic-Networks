# Markov-Logic-Network
## An Interface Layer for Artificial Intelligence
###### An Application of MLN


Markov logic is a language that combines first-order logic and Markov networks. A knowledge base (KB) in Markov logic is a set of first-order formulas with weights. Given a set of constants representing objects in the domain of interest, it defines a probability distribution over possible worlds, each world being an assignment of truth values to all possible ground atoms. In first-order logic, formulas are hard constraints: a world that violates even a single formula is impossible. In Markov logic, formulas are soft constraints: a world that violates a formula is less probable than one that satisfies it, other things being equal, but not impossible. The weight of a
formula represents its strength as a constraint.

This project proposes a simple approach to combine first-order logic and probabilistic graphical models in a single representation. Markov logic network (MLN) accomplishes this by attaching weights to first-order logic formulas (or clauses). Using the concept of MLN, Personalized PageRank is implemented on the dataset describing the Roman city of Pompeii. Inspired by “Google Sets” and Bayesian sets, the problem considered is of retrieving complex objects and relations among them, given a query consisting of a few atoms from that concept. This problem is formulated as a within-network relational learning problem using few labels only and describe an algorithm that ranks atoms using a score based on random walks with restart(RWR). The features used re-personalize the original RWR and finally compute the set completion, based on Label Propagation

[Reference](http://www.first-mm.eu/files/neumann11aaai.pdf)
