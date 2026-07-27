---
title: "Hybrid Privacy via Dirichlet Process Mixture Models: Differentially Private Weights and Diffusion-Based Centroid Protection"
collection: publications
category: manuscripts
permalink: /publication/2026-hybrid-privacy-ddpmm
excerpt: "We develop a hybrid privacy framework for Dirichlet process mixture models by combining differential privacy for mixture weights with diffusion-based protection of cluster centroids."
date: 2026-01-01
venue: ""
paperurl: ""
---

## Abstract

Mixture models are widely used to capture cluster-based structure in data across modern machine learning systems. They are particularly relevant in time-varying settings such as smart grids and interacting large language models. However, under repeated data release, cluster centroids can leak sensitive group information, as their temporal trajectories enable reconstruction of underlying group behavior over time. Static perturbation methods are insufficient, as applying the same structured noise across time allows it to be filtered out.
This work introduces a time-varying privacy framework for mixture models. A dynamic Dirichlet process (DirP) mixture model is proposed in which centroids evolve via a diffusion process, injecting structured randomness that prevents trajectory reconstruction while preserving utility. A Dirichlet mechanism ensures differential privacy for both population centroids and mixture weights, providing a principled separation between dynamic and static protection.
The approach is supported by theory and experiments. It demonstrates improved robustness to filtering-based reconstruction and stronger utility-privacy trade-offs compared to static methods.
## Status

**Current status:** Manuscript in preparation for submission.
