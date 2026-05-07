---
layout: homepage
---

# About Me

I'm an incoming Ph.D. student in Computer Science at the University of Virginia, advised by [Prof. Ferdinando Fioretto](https://nandofioretto.github.io/) as part of the **Responsible AI for Science and Engineering (RAISE)** group. I am honored to be awarded the UVA CS Scholar fellowship to support my PhD studies. I earned my BSc in Mathematics from Beloit College.

**My research focuses on constrained generative models and their application to solving mathematical problems. I build architectures that embed hard mathematical constraints - such as boundary conditions, integrality, and conservation laws - directly into the generation process, so that every output is a structurally valid mathematical solution.**

I’m interested in the intersection of deep generative modeling, constrained optimization, and formal mathematical reasoning. I’m always happy to connect with others working on AI for mathematics or constrained generation.


# Research

Generative models have shown remarkable fluency in producing text, images, and code, but when applied to mathematical problem solving, fluency is not enough. A generated solution that *looks* correct but violates a boundary condition, an inequality constraint, or an equation is worthless. Mathematics demands absolute feasibility, not plausibility.

My research develops generative models that solve mathematical problems under hard constraints - guaranteeing that every generated candidate is a valid solution to the problem’s requirements. Instead of relying on post-hoc filtering or verification, I design architectures where constraint satisfaction is a structural property of the generative process itself. The goal is an AI that can be trusted to autonomously explore mathematical spaces and return only certified, correct results.

## Core Directions

**1. Constrained Generative Architectures for Mathematics**  
I develop diffusion‑based and autoregressive generative models that directly incorporate mathematical constraints (e.g., PDE boundary conditions, integer constraints, symmetry groups) into their sampling trajectories. Drawing on stochastic optimal control, score‑based modeling, and constraint‑embedding techniques, these architectures produce solutions that are feasible *by construction* – not just at the final step, but at every intermediate point.

**2. Correctness Guarantees for Generated Solutions**  
I establish finite‑sample guarantees on solution validity using tools from conformal prediction, robust optimization, and proof‑theoretic verification. These guarantees are distribution‑free, robust to distribution shift, and provide rigorous certificates that a generated mathematical object satisfies all specified constraints with high probability.

**3. Applications Across the Mathematical Sciences**  
I am driven by concrete mathematical problems: solving large‑scale combinatorial optimization, generating solutions to partial differential equations with complex boundary conditions, discovering proofs or counterexamples in discrete mathematics, and synthesizing mathematically valid molecular structures. The constrained generative framework I build is intended to be a general‑purpose tool for any domain where correctness is non‑negotiable.

## Why This Matters

Mathematics operates under the strictest constraints of any discipline: a single violated axiom breaks an entire argument. Generative AI, for all its creativity, currently lacks the native ability to respect such constraints. My work gives generative models the mathematical discipline they need to function as reliable scientific instruments - capable of exploring vast solution spaces while never stepping outside the boundaries of what is logically, physically, or practically allowed.

The result is AI that can be confidently deployed as an assistant for mathematicians, engineers, and scientists: a system that produces not just suggestions, but *certified solutions*.


# News

- **[Aug. 2026]** Starting my Ph.D. in Computer Science at the University of Virginia, focusing on constrained generative models for mathematical problem solving as part of the RAISE group!

## Publications

Please view my [Google Scholar](https://scholar.google.com/citations?user=v3_DrtcAAAAJ&hl=en) profile for the latest updates.
