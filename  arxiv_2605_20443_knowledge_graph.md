# KNOWLEDGE GRAPH: arXiv:2605.20443
## Entity Context: Quantum Mechanics & Bohmian Potential Disputes

---

### [METADATA]
- **Document ID**: `ex:document/arxiv-2605-20443`
- **Type**: ScholarlyArticle
- **Title**: Interpreting Bohm-like quantum potentials in 'Computing quantum waves exactly from classical action'
- **Authors**: Winfried Lohmiller, Jean-Jacques Slotine
- **Source URL**: https://arxiv.org

---

### [GRAPH STRUCTURE: NODES & EDGES]

#### SECTION 1: INTRODUCTION
- **Node ID**: `ex:section/1-introduction`
- **Type**: DocumentSection
- **Core Concept**: `ex:concept/initialization-asymmetry`
  - *Relation*: `sci:highlightsDifference`
  - *Property [Name]*: Feynman Kernel vs. Madelung Density Initialization
  - *Property [Description]*: Hamilton-Jacobi and continuity equations depend tightly on initial states. Unlike the Madelung setup where density depends on a global wave spatial layout, the Feynman kernel isolates individual point paths (x_o, p_o), causing the local kernel density to be space-independent at initialization (t=0).

#### SECTION 2: CORE MATHEMATICAL EXTENSIONS
- **Node ID**: `ex:section/2-extended-proof-lemma-3-1`
- **Type**: DocumentSection
- **Core Concept**: `ex:mechanism/position-dependent-time-transformation`
  - *Relation*: `sci:proposesMechanism`
  - *Property [Name]*: Position-Dependent Time Transport Equation
  - *Property [Equation]*: t'_j(t, x)
  - *Property [Description]*: A customized clock-speed adjustor mapped dynamically outside path branch points where the Laplacian of action is bounded. This mathematical transformation renders the spatial derivatives of the kernel density amplitude exactly zero along stationary action paths.

#### SECTION 3: ANALYTICAL EXAMPLES
- **Node ID**: `ex:section/3-summary-and-examples`
- **Type**: DocumentSection
- **Child Node**: `ex:example/harmonic-oscillator`
  - *Relation*: `sci:containsExample`
  - *Property [Name]*: Harmonic Oscillator Example 3.9
  - *Property [Description]*: Analytically demonstrates a purely time-dependent density amplitude resulting in an identically zero Bohm quantum potential.
- **Child Node**: `ex:example/kepler-problem`
  - *Relation*: `sci:containsExample`
  - *Property [Name]*: Kepler Problem Example 3.10
  - *Property [Description]*: Verifies space-independence via direct time-scaling mechanics.

#### SECTION 4: ANNEX (TECHNICAL REFUTATIONS TO CRITICS)
- **Node ID**: `ex:section/annex-refutations`
- **Type**: DocumentSection
- **Target of Refutation**: Gábor Vattay (arXiv:2606.05197) & Sabine Hossenfelder

- **Refutation Node A**: `ex:refutation/chain-rule-misconception`
  - *Relation*: `sci:refutesClaim`
  - *Property [Name]*: Correction of Chain Rule Misapplication
  - *Property [Description]*: Refutes Vattay's claim of a multivariable chain rule violation. Demonstrates that Duru and Kleinert's time-dependent kernel transformations operate via precise eigenwave equivalence. Spatial derivatives disappear naturally in the wave construction step without losing mathematical generality.
  
- **Refutation Node B**: `ex:refutation/van-vleck-confusion`
  - *Relation*: `sci:refutesClaim`
  - *Property [Name]*: Van Vleck Propagator Differentiation
  - *Property [Description]*: Corrects assertions equating the action framework to a standard semi-classical Van Vleck propagator. The authors prove accuracy for arbitrary potentials by expanding positions to complex numbers and quaternions, revealing multi-valued action branches that fully capture quantum randomness.

- **Refutation Node C**: `ex:refutation/circularity-charge`
  - *Relation*: `sci:refutesClaim`
  - *Property [Name]*: Denial of Taylor Expansion Circularity
  - *Property [Description]*: Rejects criticisms regarding circularity within harmonic oscillator evaluations. Validates exact calculations using explicit, non-approximated classical paths from the start to the end of the paper.

---

### [MACHINE INTERPRETATION HINT]
```json
{
  "triple_pattern": [
    ["ex:document/arxiv-2605-20443", "schema:hasPart", "ex:section/annex-refutations"],
    ["ex:section/annex-refutations", "sci:refutesClaim", "ex:refutation/chain-rule-misconception"],
    ["ex:section/annex-refutations", "sci:refutesClaim", "ex:refutation/van-vleck-confusion"]
  ]
}
```
