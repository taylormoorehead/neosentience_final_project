**Overview**

This repository supports an experiment dedicated to furthering neosentience.

The code starts with generating a synthetic dataset based on MIT's Moral Machine

We then apply manual amplitude encoding and random amplitude encoding, giving us two quantum-ready representations of the data. Each encoded dataset is then used to train its own QSVC model. We measure accuracy, precision, recall, and the time each encoding method takes. This gives a direct, side-by-side comparison of predictive performance and encoding cost.

To help visualize the tradeoffs, the scripts generate plots showing both the empirical accuracy/time differences and an estimated accuracy–time frontier. This frontier is built by fitting a polynomial curve to hybrid encoding points.
