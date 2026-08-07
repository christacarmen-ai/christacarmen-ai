# Christa Diaz

**Founder and Chief Scientist, Orienne · builder of a developmental world model**

Boston, Massachusetts · christacarmen@gmail.com · ORCID [0009-0001-1445-5554](https://orcid.org/0009-0001-1445-5554)

I design, build, and evaluate world models of a domain where ground truth is genuinely hard: human psychological development. Over eighteen months I built an end-to-end research program as a solo scientist and co-founded: a production measurement platform, a typed graph substrate with ordinal heads and training gates enforced in code, a recursive Bayesian per-person state estimator, and a synthetic-dynamics laboratory whose job is to establish what the model is allowed to claim.

The defining commitment is evaluation discipline: pre-registered gates, held-out-only findings, permutation and structure-free nulls, and reproducibility manifests (config, seed, git SHA) on every result. The working habit underneath all of it: design the falsifier before the finding, and gate architecture behind data volume rather than shipping on promise.

> Most of this work lives in private repositories while patent filings and preprints are in flight. Detailed walkthroughs, code, preprints, and filings are available on request.

## Selected Systems

**Per-person world model + developmental-state inference layer** (2026)
Recursive Bayesian (Kalman-style) trajectory filter over 8 latent developmental features, measurement noise scaled inversely to per-observation confidence. Assembles a per-person state: baseline, dual-channel structure/state estimate, calibrated belief, lifecycle phase, atlas localization. Activation gate pre-registered before any cohort data existed (readout stays dark until 10+ scored sessions). Subject of a patent disclosure, inventor, filed July 2026.

**Substrate + Topology laboratory: world-model evaluation on known ground truth** (2026)
A 100,000-record synthetic-cohort generator with fully known dynamics, used to validate every observational instrument before it touches real data: learned manifold, Waddington-style landscape, geometry-only pseudotime, single-snapshot developmental velocity (a port of the RNA-velocity move from single-cell genomics). Key negative result: a density well is not an attractor. Passive snapshots and flow fields cannot separate attractor dynamics from a static mixture, because regression to the mean fabricates fixed points; only a perturbation with a restoring response earns the label. Implemented as a competing-worlds arena with Sussillo-Barak fixed-point classification, plus falsification rooms (permutation nulls, structure-free null worlds, bootstrap CIs, ablation, reproduce/export manifests).

**Intelligence-layer network: gated architecture over a typed substrate** (2026)
Typed, grounding-tagged semantic core: a 127-node consciousness-theory knowledge graph, 44 phenomenological state objects, multiple features, stage bands, 48 contemplative-tradition nodes. CORAL/CORN ordinal regression heads and R-GCN / heterogeneous GraphSAGE components designed, then gated in code: training raises `GateClosed` until 500+ held-out scored exemplars per feature exist, and promotion is blocked until a membership-inference privacy audit passes. Every node requires a grounding register at construction; ungrounded claims cannot enter the model.

**Tessera/Orienne (Co-Founded): production measurement platform** (2026)
~140,000 LOC Python + TypeScript, 8,000+ commits, 11-service Docker deployment with self-hosted observability. Narrative assessment, AI feature extraction, then fully deterministic server-side scoring across developmental frameworks with convergence analysis and report generation; reduces 2-4 hours of trained-practitioner scoring to minutes, every step audited. The third-party frontier model was removed from the measurement loop: a fine-tuned, self-hosted Qwen model performs enum-guided JSON logprob extraction, making the single AI step in scoring reproducible and pinnable to a revision.

**Unified scoring engine v4.1** (2026)
31,500 LOC Python, React + TypeScript dashboard. Deterministic pipeline from 13 narrative stems across multiple features to a multi-layered convergence engine. 

**Meta Mind Model: epistemic world model with a global-workspace surface** (2026)
A psychology-anchored world model of the research estate itself, with a construction-time-enforced workspace schema and a maximal world-state contract with write-back rules; positioned against four verified literature anchors, claiming the meta-cognition and motivation layer the survey literature names as the field's open problem.

## Research and Writing

- *World Models: Lineage, Formalism, Current State, and a Blueprint for a Developmental World Model*, 2026. Manuscript.
- Ten-paper preprint portfolio in preparation (PsyArXiv-targeted), reported as N-of-1 instrument demonstrations with limitations disclosed in the papers themselves. Headline instrument results: blind-rescore reliability ICC(2,1) = 0.786; a single principal component carrying 77% of variance with all 8 features loading positive; state measured above structure in 96% of 73 paired sessions; a persistent forward-only change-point alarm at +88 days, undetectable at 6-day sampling gaps.
- Four patent disclosures filed, inventor.

## Methods and Tools

**Modeling:** state-space and Bayesian filtering (Kalman), ordinal regression (CORAL/CORN), graph neural network design (R-GCN, GraphSAGE), knowledge graphs, manifold learning, pseudotime and velocity estimation, fixed-point/attractor analysis.
**Evaluation:** pre-registration, held-out gating, permutation and structure-free nulls, bootstrap CIs, ablation, blind rescoring, reproducibility manifests, membership-inference privacy audits.
**Engineering:** Python (numpy, scikit-learn, pandas), FastAPI/Flask, React + TypeScript, Docker, Supabase/Postgres + pgvector, Railway/Northflank, LLM fine-tuning and self-hosted deployment (Qwen), uv/ruff toolchain.
**Domain:** adult developmental psychology as the world being modeled.

## Education

M.A., East-West Psychology, California Institute of Integral Studies (in progress, 2026-2028) · Applied AI and Data Science, MIT Professional Education (2026) · B.A., Auburn University · Apprenticeship in the STAGES developmental framework with Terri O'Fallon, PhD · Six years of contemplative training in the Indo-Tibetan lineage.
