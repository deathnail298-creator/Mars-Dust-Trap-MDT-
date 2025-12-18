# Phase 2 — Scaling Logic Snapshot

## Purpose
This section explains how multiple Mars Dust Trap (Windcatcher) units are expected to behave together at a system level. It is NOT execution authorization, performance guarantee, or deployment doctrine. It exists to prevent “hand-wave scaling” and show that scaling behavior is physically and operationally sane.

---

## What Scales and Why
The Mars Dust Trap reduces dust exposure through **passive interception**, not active capture. Scaling works because:

• each unit biases a portion of inbound windborne dust  
• effects are **local**, persistent, and cumulative over time  
• multiple localized reductions behave like perimeter conditioning  
• benefit accrues even if performance per-unit is modest  

This is environmental conditioning, not dust elimination.

---

## Single-Unit → Multi-Unit Transition Logic
Baseline evaluation correctly begins with a **single perimeter unit**.

Once validated:

1️⃣ Units are placed around the protected zone perimeter  
2️⃣ Each unit conditions “its slice” of approached dust flux  
3️⃣ Overlap between units is acceptable  
4️⃣ Loss of a unit simply removes its marginal contribution  

There is no cascading failure mode.

---

## Expected Scaling Behavior (Plain English)
• Early units provide the largest “perceived benefit”  
• Additional units continue to help but with diminishing returns  
• Performance does NOT require perfect geometry  
• A dirty or degraded unit still provides *some* benefit  
• System degradation = graceful fade, not mission collapse

---

## Practical Deployment Assumptions
These are not requirements — they are sanity anchors.

• Units placed on prevailing-wind-facing perimeter portions help most  
• Distributing units is better than clustering  
• “Every so many meters” is closer to right than “perfect CFD grid”  
• Missed placement is waste of efficiency, not failure  

No precision deployment robotics required.

---

## Order-Percent Framing Still Applies
Performance expectations remain conservative:

• Order-percent improvement per unit over operational timeframes  
• Stacking multiple units → order-percent *aggregate effect*  
• Upper-bound improvements require favorable terrain + wind + placement  

Nothing here contradicts Phase 0 / Phase 1 discipline.

---

## Why This Is Physically Sane
Not marketing — physics logic:

• wind energy is finite  
• dust entrainment is not uniform  
• turbulence, drag, inertia mismatches, and gravity create fallout opportunities  
• repeated encounters bias probability toward deposition  

More encounters → more bias → more cumulative benefit.

---

## Governance & Honesty Constraint
Phase 2 does not claim:
❌ total dust control  
❌ storm mitigation  
❌ deterministic regional effects  
❌ guaranteed percent savings  

It claims:
✔ predictable directional benefit  
✔ cumulative conditioning behavior  
✔ graceful failure characteristics  
✔ rational multi-unit scaling

That is the correct level of confidence for Phase 2.

