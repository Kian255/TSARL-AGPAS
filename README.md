# TSARL with AGPAS

Spatio-Temporal Adaptive Robust Learning for Efficient Adversarial Training

## Overview

TSARL with AGPAS reformulates adversarial example generation as a short-horizon spatio-temporal planning problem. 
The method reduces redundant gradient computations while preserving strong adversarial robustness.

## Key Results (ε = 8/255)

CIFAR-10:
- Clean Accuracy: 85.2%
- Robust Accuracy: 48.1%
- 9.5× faster training compared to PGD-50

CIFAR-100:
- Clean Accuracy: 66.3%
- Robust Accuracy: 33.4%
- 9.5× faster training compared to PGD-50

## Motivation

Multi-step PGD-based adversarial training is computationally expensive. 
TSARL introduces structured spatial allocation, adaptive gradient pruning (AGPAS), 
and temporal step scheduling to improve training efficiency.

## Repository Structure

- attacks/        Adversarial methods (PGD, TSARL variants)
- models/         Neural network architectures
- training/       Training pipeline
- configs/        Experiment configurations
- utils/          Helper functions

## Status

Research preprint available on arXiv.
Full implementation will be released upon publication.

## Citation

Will be updated after publication.
