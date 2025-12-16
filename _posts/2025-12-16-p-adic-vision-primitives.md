---
layout: post
title: "Research Thread: p-adic Places and Visual Primitives"
date: 2025-12-16
tags: [research, p-adic, vision, algebraic-geometry, neural-networks]
---

## The Question

Can graphics primitives (the basic shapes CNNs learn to detect) be expressed as algebraic curves? And does the hierarchy of CNN layers correspond to something like places on those curves?

## Starting Point: What Do Babies See First?

- Mother's torso: nested convex regions (belly + breasts) — topologically specific arrangement
- Smile: convex-up arc with bilateral symmetry

These are both degree-2 curves (conics), but the *smile* might be better modeled as a circular arc (constant curvature) rather than parabola (varying curvature). Perceptually simpler — one parameter.

What CNNs probably learn isn't "parabola" or "circle" specifically, but:
- Convexity direction (up/down)
- Curvature magnitude
- Bilateral symmetry

## The p-adic Connection

Khrennikov has been pushing p-adic cognitive models for decades. Key insight: neuron states as digits in p-adic expansion — each p-adic number represents a configuration of firing/non-firing neurons.

**Recent development (Zúñiga-Galindo et al.):**
- p-adic Wilson-Cowan models on (ℤₚ, +)
- Standard Wilson-Cowan on (ℝⁿ, +) is *incompatible* with small-world property and fractal patterns observed in real cortical networks
- p-adic CNNs for edge detection perform comparably to Canny — and they can *explain* how the network detects edges

Key paper: "p-adic cellular neural networks: Applications to image processing" — they determine all stationary states and can describe the dynamics almost completely.

## The Open Question

Nobody seems to be connecting **places on algebraic curves** to visual feature hierarchies explicitly.

The existing work treats p-adic structure as convenient encoding for hierarchy. But:
- Curves have different "personalities" at each prime (place)
- The Hasse principle: understand a curve by studying all its local completions simultaneously
- What if CNN layers correspond to information at different places?

The intuition: algebraic curves have Platonic existence, and what we perceive are shadows at various places. Graphics primitives might *be* curves, with the hierarchy of visual processing reflecting arithmetic structure.

## People to Read

- **Andrei Khrennikov** (Linnaeus University) — original p-adic neural network models
- **W.A. Zúñiga-Galindo** (UTRGV) — p-adic CNNs, image processing applications, recent active work
- **B.A. Zambrano-Luna** — collaborator on p-adic reaction-diffusion CNNs

## Next Steps

- Read Zúñiga-Galindo's edge detection paper in detail
- Look at how places on a conic (simplest case) might map to different "views" of the curve
- Think about whether the reduction mod p of a curve corresponds to a coarse-graining in visual processing
