# TSARL with AGPAS

Official research implementation of:
TSARL with AGPAS: Spatio-Temporal Adaptive Robust Learning for Efficient Adversarial Training
## Overview
TSARL reformulates adversarial example generation as a short-horizon spatio-temporal planning problem, reducing redundant gradient computations while preserving robustness.

## Results (ε = 8/255)

CIFAR-10: 85.2% clean / 48.1% robust (9.5× faster than PGD)
CIFAR-100: 66.3% clean / 33.4% robust (9.5× faster than PGD)

## Status
Research preprint available on arXiv.
Full implementation to be released upon publication.
