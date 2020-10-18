# Analysis of Markov Jump Processes under Terminal Constraints

_Michael Backenköhler, Luca Bortolussi, Gerrit Großmann, Verena Wolf_

Many probabilistic inference problems such as stochastic filtering or the computation of rare event probabilities require model analysis under initial and terminal constraints. We propose a solution to this bridging problem for the widely used class of population-structured Markov jump processes. The method is based on a state-space lumping scheme that aggregates states in a grid structure. The resulting approximate bridging distribution is used to iteratively refine relevant and truncate irrelevant parts of the state-space. This way the algorithm learns a well-justified finite-state projection yielding guaranteed lower bounds for the system behavior under endpoint constraints. We demonstrate the method's applicability to a wide range of problems such as Bayesian inference and the analysis of rare events.
