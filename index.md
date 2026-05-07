---
layout: homepage
---

# About Me

I'm an incoming Ph.D. student in Computer Science at the University of Virginia, advised by [Prof. Ferdinando Fioretto](https://nandofioretto.github.io/) as part of the **Responsible AI for Science and Engineering (RAISE)** group. I am honored to be awarded the UVA CS Scholar fellowship to support my PhD studies. I earned my BSc in Mathematics from Beloit College.

**My research focuses on constrained generative models and their application to challenging operations research problems. I build architectures that embed hard operational constraints – such as capacity limits, staffing regulations, service-level agreements, and resource budgets – directly into the generative process, so that every output is a provably feasible and actionable decision.**

I’m interested in the intersection of deep generative modeling, constrained optimization, and prescriptive analytics. I’m always happy to connect with others working on AI for operations, data‑driven decision‑making under constraints, or trustworthy machine learning.


# Research

Generative models have achieved tremendous fluency in producing text, images, and code, but when deployed for operational decision‑making, fluency is not enough. A generated shift schedule that violates labor laws, a supply‑chain scenario that ignores warehouse capacities, or a pricing policy that breaks anti‑discrimination rules is worthless. Real‑world operations demand feasibility, not just plausibility.

My research develops generative models that solve operations research problems **under hard constraints** – guaranteeing that every generated candidate is a valid, implementable decision with respect to all operational requirements. Instead of relying on post‑hoc filtering or verification, I design architectures where constraint satisfaction is a structural property of the generative process itself. The goal is AI that operations managers, supply chain directors, and healthcare administrators can trust to return only certified, feasible solutions.

## Core Directions

**1. Constrained Generative Architectures for Operations**  
I develop diffusion‑based and autoregressive generative models that directly incorporate operational constraints (e.g., capacity ceilings, fairness bounds, regulatory mandates) into their sampling trajectories. Drawing on stochastic optimal control, score‑based modeling, and constraint‑embedding techniques, these architectures produce decisions that are feasible *by construction* – not just at the terminal output, but throughout the entire generation trajectory.

**2. Correctness and Feasibility Guarantees for Generated Decisions**  
I establish finite‑sample guarantees on constraint violation rates using tools from conformal prediction, robust optimization, and distribution‑free verification. These guarantees provide rigorous certificates that a generated operational plan satisfies all hard constraints with high probability, even under distribution shift and without requiring unrealistic assumptions on the underlying data distribution.

**3. Applications Across Challenging Operations Research Domains**  
I am driven by concrete operations research problems: **healthcare scheduling** (e.g., nurse rostering with skill‑mix ratios and labor regulations), **supply chain resilience** (e.g., disruption‑scenario generation under network topology constraints), **revenue management** (e.g., dynamic pricing with fairness and anti‑gouging rules), and **platform operations** (e.g., gig‑worker task assignment with wage‑floor guarantees). The constrained generative framework I build is intended as a general‑purpose tool for any domain where operational feasibility is non‑negotiable.

## Why This Matters

Operations research has spent decades developing the mathematics of optimal decision‑making under constraints. Generative AI, for all its expressivity, still lacks a native ability to respect those constraints. My work bridges these two traditions: embedding the rigor of constrained optimization directly into the architecture of modern generative models. The result is AI that operations leaders can deploy with confidence – systems whose outputs are not merely suggestive, but *certifiably executable*.


# News

- **[Aug. 2026]** Starting my Ph.D. in Computer Science at the University of Virginia, focusing on constrained generative models for operations research problems as part of the RAISE group!

## Publications

Please view my [Google Scholar](https://scholar.google.com/citations?user=v3_DrtcAAAAJ&hl=en) profile for the latest updates.