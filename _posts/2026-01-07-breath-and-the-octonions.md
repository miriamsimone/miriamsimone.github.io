---
layout: post
title: "Breath and the Octonions: Why Tai Chi Gates Might Be Non-Associative"
date: 2026-01-07
reading_time: 8
---

Yesterday I wrote about [H₁ and the cycles through the ground](/2026/01/06/h1-and-the-ground) — how loops that pass through external constraints (like your feet touching the earth) create non-trivial homology, while loops that stay inside your body (like clasped hands) are fillable and free. Today I want to talk about something that might be even weirder: why combining tai chi movements might be non-associative, and what breath has to do with it.

## The setup

Tai chi has eight fundamental movements called the "gates" (八門, bā mén):

- **Peng** (掤) — ward off, expanding
- **Lu** (捋) — rollback  
- **Ji** (擠) — press
- **An** (按) — push down
- **Cai** (採) — pluck/grab
- **Lie** (挒) — split
- **Zhou** (肘) — elbow
- **Kao** (靠) — shoulder stroke

I have a hunch these are the eight Cartan directions of E₈ — the eight commuting, independent directions on the maximal torus. That would make the 240 roots the *coupled* movements, the ways the gates interact with each other. But today I want to focus on something else: what happens when you combine gates, and why the order might matter in a very specific way.

## The octonion structure: 1 + 7

The octonions are an 8-dimensional number system. They have one real direction and seven imaginary directions. Unlike the quaternions (which are non-commutative but still associative), the octonions are *non-associative*: (ab)c ≠ a(bc) in general.

The seven imaginary units anticommute: eᵢeⱼ = -eⱼeᵢ. But multiplying by the real unit 1 is just... 1. It doesn't have a "negative direction."

Here's what I noticed today: **some tai chi gates are bidirectional, and some are unidirectional.**

Take Peng (ward off). You can do it on the inhale — that's charging up a spring, storing potential energy. You can also do it on the exhale — that's releasing, pushing something away. Same movement, two flavors. Bidirectional.

But Cai (pluck/grab) only feels right one way. It's a pure rotation. You can't "un-rotate" on the opposite breath phase the way you can charge/release with Peng.

If this pattern holds — if there's exactly 1 unidirectional gate and 7 bidirectional ones — then the gates have the 1 + 7 structure of the octonions. The unidirectional one is the real direction. The bidirectional ones are the imaginary units.

(Ji might also be unidirectional — it's a press where both arms go the same direction. Need to check the others more carefully.)

## Breath as the complex plane

Here's where it gets interesting.

Breath is a cycle. Inhale, exhale, inhale, exhale. It traces a circle.

But what kind of circle? I think it's the harmonic oscillator loop in phase space:

- **Inhale** = potential energy (compressed spring, stored tension)
- **Exhale** = kinetic energy (releasing, energy moving through the body)

This is the (q, p) plane — position and momentum. As you breathe, you trace e^{iθ} around the circle. The *radius* of that circle is total energy: deeper breath = bigger circle = higher Hamiltonian.

So breath is your base U(1). It's the complex plane underlying everything. The eight gates live *above* this — they're what you can do with the energy that breath provides.

## Why non-associativity?

Now here's the key insight.

When you do three movements a, b, c, you have to breathe. And breathing *groups* them. You can't do three things during two breath phases without choosing which two to combine:

- **(ab)c** = combine a and b on the in-breath, do c on the out-breath
- **a(bc)** = do a on the in-breath, combine b and c on the out-breath

The breath forces an associativity choice. It's not arbitrary — you *physically have to* group two of the three movements together.

But here's the thing: the Hamiltonian changes with breath depth. Inhale inflates the system, all your springs get tighter, frequencies go up. Exhale lets it out.

So (ab)c and a(bc) happen at *different energy levels*. When you group ab together on the inhale, they share the high-energy phase. When you group bc together instead, it's a different energetic configuration.

The non-associativity isn't just combinatorial — it's physical. The energy of (ab)c ≠ energy of a(bc) because breath determines which movements share the Hamiltonian scaling.

## The fibration question

What I don't know yet: is it gates fibered over breath, or breath embedded in the gates?

In the H₁ story, cycles through external constraints (the ground) are the non-trivial homology. The breath... is that internal or external? It feels internal — it's my loop, my oscillator. But it's also coupling to the environment (air coming in and out).

Maybe the breath is the base, and the gates are the fiber. Or maybe E₈ already contains the breath as one of its directions, and I'm double-counting.

## What this suggests for the paper

If the E₈ gates thesis is right, then:

1. The 8 gates = 8 Cartan directions (free, commuting)
2. The 240 roots = coupled movements, how gates interact
3. The octonion structure appears because ~7 gates are bidirectional (imaginary) and ~1 is unidirectional (real)
4. Non-associativity comes from breath forcing a grouping choice
5. The Hamiltonian (breath depth) explains *why* the groupings aren't equivalent

This connects to yesterday's H₁ discussion: the breath loop might itself have non-trivial homology if it couples to external air. But that's for another post.

## Addendum: The fibration and undertones

After writing the above, I think I figured out the fibration direction.

**Breath forms are automorphic forms over configuration space.** The breath isn't a direction *in* the 24-dimensional body manifold — it's a *function on* that space that transforms correctly under the symmetries. The zeros of the breath form mark phrase boundaries: where one movement ends and another begins.

This gives us:
- **Cusp forms** = movements that start or end at singularities (where the elliptic curve degenerates)
- **Two types of singularities**: (1) emotional/observer singularities where you couple to external constraint (the H₁ cycles), and (2) physical blockages from joint limits or trauma
- **Overconvergent forms** = movements that analytically continue past blockages — this might be exactly what healing is: extending the radius of convergence

**The weight inversion:**

Here's the weird part. Deeper relaxation → higher weight → *slower* frequencies. This is undertones, not overtones.

Overtones (2f, 3f, 4f) are easy — any string gives them for free. Undertones (f/2, f/3) are hard. They require coupled systems, collective modes, the whole body coordinating.

When you're tense, each joint is isolated. You're stuck in fast, local, weak overtone modes. When you relax, the joints couple, and suddenly the slow collective oscillations unlock. These are the undertones — slower but involving everything at once.

That's silk reeling: the slow spiral passing through the whole body. Higher weight. More zeros. More structure. The breath form gets *heavier* as you relax, and its zeros become phrase boundaries for longer and longer movements.

---

*Next: Check all 8 gates for bidirectionality. Work out what "weight" means precisely in this context.*
