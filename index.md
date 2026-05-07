---
layout: homepage
---

# About Me

I'm an incoming Ph.D. student in Computer Science at the University of Virginia, advised by [Prof. Ferdinando Fioretto](https://nandofioretto.github.io/) as part of the **Responsible AI for Science and Engineering (RAISE)** group.

**I build mathematical foundations for generative AI systems that produce outputs which are provably feasible, safe, and reliable - embedding hard constraints directly into the generative process itself.**

I'm broadly interested in constrained optimization, AI safety, and the theoretical basis of trustworthy generative systems. I'm always happy to connect with others working on related problems.

---

## Research

My research addresses a fundamental gap in modern generative AI: current models are optimized to produce *plausible* outputs, but plausibility is  not the same property as feasibility - and in high-stakes settings, the difference is consequential.

Every serious deployment of generative AI nowadays operates under hard constraints: physical laws, safety boundaries, resource limits, legal requirements. Post-hoc filtering cannot guarantee these constraints are satisfied. Constrained decoding does not scale. The field currently lacks a principled basis that enables **constraint satisfaction as a structural property of the generative model itself**.

My work contributes to this effort from the ground up.

### Core Directions

**1. Constrained Generative Architectures**  
I develop architectures for diffusion models and autoregressive generators that maintain feasibility *throughout the generation trajectory* - not only at the terminal output. This draws on stochastic optimal control, constrained optimization, and score-based generative modeling to ensure every generated sample is provably feasible by construction.

**2. Provable Safety Guarantees**  
I establish finite-sample guarantees on constraint violation rates using conformal prediction and robust optimization - providing the distribution-free safety certificates for generative models in high-stakes deployment. These certificates are robust to distribution shift and require no assumptions on the underlying data distribution.

**3. Constrained Generative Model Design and Fine-Tuning**
I am open to applying the constrained generative architectures for broad applications across sciences, engineering, and decision-making.

### Why This Matters?

Operations research spent 80 years developing the mathematics of *finding the best solution subject to hard requirements*. Deep learning spent 30 years building systems of extraordinary expressive power with no native 
language for requirements. My work brings these two traditions together - embedding the rigor of constrained optimization into the architecture of modern generative models.

The goal is AI that is not only creative and expressive, but **verifiably trustworthy**: systems whose outputs can be certified safe before deployment, and whose behavior can be formally audited after.

---

## News

- **[Aug. 2026]** Starting my Ph.D. in Computer Science at the University of Virginia as part of the RAISE group!

---

## Publications

Please view my [Google Scholar](https://scholar.google.com/citations?user=v3_DrtcAAAAJ&hl=en) profile for the latest updates.
