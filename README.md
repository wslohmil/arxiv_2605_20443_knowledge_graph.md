---
license: mit
task_categories:
- text-classification
tags:
- quantum-physics
- bohmian-mechanics
- quantum-potential
- feynman-kernel
- knowledge-graph
---

# Knowledge Graph: Interpreting Bohm-like Quantum Potens in 'Computing Quantum Waves Exactly from Classical Action'

This repository stores the structural knowledge graph and formal metadata for the foundational analysis:
**"Interpreting Bohm-like quantum potentials in 'Computing quantum waves exactly from classical action'"** (arXiv:2605.20443) by Winfried Lohmiller and Jean-Jacques Slotine.

## Key Theoretical Overview
This document maps the mathematical framework demonstrating that the Bohm-Madelung quantum potential vanishes identically when computed via local Feynman kernel point paths $(x_0, p_0)$ rather than a global Madelung density initialization.

### Core Mathematical Mechanisms
- **Initialization Asymmetry:** Unlike global wave layouts, the local kernel density is space-independent at $t=0$, separating it fundamentally from traditional Madelung configurations.
- **Position-Dependent Time Transformation:** Mapped outside path branch points where the action Laplacian is bounded, rendering spatial derivatives of the density amplitude exactly zero along stationary action paths.
- **Analytical Validations:** Includes exact derivations for the Harmonic Oscillator (Example 3.9) and the Kepler Problem (Example 3.10) confirming pure time-dependence.

## Technical Refutations to Critics Included
This graph explicitly models the formal mathematical counters to criticisms raised by Gábor Vattay (arXiv:2606.05197) and Sabine Hossenfelder:

1. **Correction of Chain Rule Misapplication:** Refutes Vattay's claim of a multivariable chain rule violation by demonstrating that Duru-Kleinert time-transformations operate via exact eigenwave equivalence.
2. **Van Vleck Propagator Differentiation:** Clarifies that this framework is *not* a semi-classical approximation. By expanding positions to complex numbers and quaternions, multi-valued action branches fully capture true quantum randomness for arbitrary potentials.
3. **Denial of Taylor Expansion Circularity:** Rejects assertions of circularity in harmonic evaluations, validating calculations via exact, non-approximated classical paths from inception to completion.

## Machine Interpretation Reference
```json
{
  "document": "arxiv-2605-20443",
  "verified_claims": [
    "vanishing_bohm_potential_proof",
    "chain_rule_violation_refutation",
    "van_vleck_differentiation"
  ]
}
```
