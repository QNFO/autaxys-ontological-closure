# Autaxys Ontological Closure Paper — Project Plan

## §1 Charter
Write the source paper for the Autaxys Ontological Closure (OC) operational definition, which has existed as a draft KG node (`paper:autaxys-ontological-closure`) but has never been written as a full paper, published to Zenodo, or deployed to the core distribution stack.

## §1.2 Core Claim Lock (HARD GATE)
**Operational definition (locked from prior sessions):**
> "A quantity is physically real only if there exists a finite Turing-machine protocol that approximates it with a computable modulus of convergence, yielding measurement-distinguishable predictions."

This is NOT a metaphysical claim about what "exists" — it is an operational criterion for when a physical quantity qualifies as MEASURABLE in principle. The boundary is not between "real" and "unreal" but between "computable-approximable" and "uncomputable" — and the claim is that this boundary coincides with the boundary of physical measurability.

## §1.3 Project Goals
1. Write the paper source (`autaxys-ontological-closure.md`)
2. Build PDF via `build-paper.py`
3. Publish to Zenodo with DOI
4. Deploy to D1, R2, KG — fill the existing KG draft node
5. The paper must include the 11 sub-papers rationalization (the decomposition of the OC criterion into testable sub-claims across domains)

## §2 WBS
| Phase | Description | Deliverables |
|:------|:------------|:-------------|
| Phase 0 | Project init — repo, scaffold, core claim lock | Repo, scaffold files |
| Phase 5 | Publication — write paper, build PDF, Zenodo DOI | Paper, PDF, DOI |
| Phase 6-8 | Deployment + Distribution — D1, R2, KG, GitHub Release | Full core stack |

## §3 Deliverable Registry
| Deliverable | Path | Target |
|:------------|:-----|:-------|
| Paper | `autaxys-ontological-closure.md` | GitHub, Zenodo, D1 |
| PDF | `autaxys-ontological-closure.pdf` | GitHub, Zenodo, R2 |
| Provenance bundle | `PROVENANCE-BUNDLE.zip` | Zenodo |
| KG node | `paper:autaxys-ontological-closure` | graph-api.qnfo.org |

## §4 Success Criteria
1. OC criterion is stated in precise, operational terms with explicit falsifiability conditions.
2. Standard physical quantities (mass, charge, spin) are shown to pass the criterion.
3. Problematic quantities (uncomputable reals, non-measurable sets, continuum fields at arbitrarily small scales) are shown to fail — and this is argued to be a FEATURE, not a bug.
4. The 11 sub-papers rationalization is included as a structured decomposition.
5. Calibration register with dated, strength-weighted predictions is populated.
6. Full core distribution: GitHub, Zenodo DOI, D1, R2, KG.

## §5 Version History
| Version | Date | Description |
|:--------|:-----|:------------|
| v0.1-phase0 | 2026-08-01 | Project initialization |
| v1.0 | 2026-08-01 | Initial publication |
