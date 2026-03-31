# Unsupervised Sequence Discovery via Directed Optimal Transport
This repository contains a preliminary prototype for the Markov-Transport Correlation Coefficient (MTCC).
## Abstract
While current representation learning frameworks (like OT-CPCC) excel at embedding symmetric hierarchies, sequential data exhibits strict directional asymmetry. This project proposes a novel information-geometric metric that correlates latent Wasserstein distances between contextual distributions with their empirical Markovian transition costs.
## Key Result
In testing on the undeciphered Indus script, the latent space of a standard LSTM exhibited a directed OT-correlation of 0.2211 with a highly significant p-value of 8.08e-06. This suggests that while networks implicitly learn grammatical flow, they require explicit OT regularization (e.g., FastFT) to maximize this alignment.
