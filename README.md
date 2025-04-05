# Simulated Method of Embeddings (SME)

This repository contains a preliminary presentation of the Simulated Method of Embeddings (SME), a contrastive learning-based approach to structural estimation in economics. The method does not require likelihood functions or moment conditions and builds on recent advances in representation learning.

This method builds directly on the Embed and Emulate (E&E) framework of Jiang, Lu, and Willett (2024), adapting their contrastive representation learning approach to structural econometric inference. I modify the loss structure, restrict the architecture to support efficient parameter recovery, and introduce SME as a consistent estimator tailored for simulation-based economic models.

This draft outlines:
- The SME estimator formulation
- InfoNCE-based contrastive loss
- Theoretical guarantees (KL divergence minimization, consistency)
- Simulation results comparing SME to standard estimators

**This is an early-stage draft intended for timestamping and authorship record. Do not cite or distribute without explicit permission.**

**Author**: Steven Otis  
**Date**: April 5, 2025
