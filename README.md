# Simulated Method of Embeddings (SME)

This repository contains a preliminary presentation of the Simulated Method of Embeddings (SME), a contrastive learning-based approach to structural estimation in economics. The method does not require likelihood functions or moment conditions and builds on recent advances in representation learning.

This method builds directly on the Embed and Emulate (E&E) framework of Jiang, Lu, and Willett (2024), adapting their contrastive representation learning approach to structural econometric inference. I modify the loss structure, restrict the architecture to support efficient parameter recovery, and introduce SME as a consistent estimator tailored for simulation-based economic models.

This draft outlines:
- The SME estimator formulation
- InfoNCE-based contrastive loss
- Theoretical guarantees (KL divergence minimization, consistency)
- Simulation results comparing SME to standard estimators

**This is an early-stage draft intended for timestamping and authorship record. Do not cite or distribute without explicit permission.**


## (Edit) Related Work

This project is conceptually related to Kaji, Manresa, and Pouliot (2023), who propose an adversarial approach to structural estimation based on a minimax optimization between a simulator and a discriminator (akin to GANs). While both methods address simulation-based inference without likelihoods or moments, the Simulated Method of Embeddings (SME) introduced here is methodologically distinct.

In contrast to the adversarial framework of Kaji et al., SME leverages contrastive learning specifically a symmetric InfoNCE-style loss  and trains a fixed scoring function without a minimax loop. The estimation procedure is a direct M-estimation problem, not a game-theoretic saddle point. My method is an extension of the work done in the Embed and Emulate (E&E) framework of Jiang, Lu, and Willett (2024), but adapted and reinterpreted for structural parameter recovery in econometric models.

**Author**: Steven Otis  
**Date**: April 7, 2025

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15170934.svg)](https://doi.org/10.5281/zenodo.15170934)


