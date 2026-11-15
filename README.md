# Christa Diaz

**Founder, Orienne** · Boston, MA · [orienne.com](https://orienne.com) · christacarmen@gmail.com · ORCID [0009-0001-1445-5554](https://orcid.org/0009-0001-1445-5554)

I design psychological measurement systems and build models of how people develop over time. My work combines adult developmental psychology with statistics and machine learning, with a focus on testing whether a model's claims actually hold up before trusting them.

> Most of this work is in private repositories while patents and papers are in progress. Walkthroughs and code are available on request.

## Selected Work

**Orienne: psychological measurement platform** (2026)
A production platform that scores written narrative responses against established adult developmental frameworks and checks how well those frameworks agree. It turns 2 to 4 hours of trained-practitioner scoring into minutes, with every step logged. Python and TypeScript, deployed with Docker.

**Unified scoring engine** (2026)
The scoring pipeline behind the platform: responses to 13 narrative prompts, scored across 8 developmental features and combined into one profile. Python backend with a React + TypeScript dashboard. Being moved to deterministic scoring so the same input always produces the same result.

**Per-person developmental model** (2026)
A model that follows each person across sessions and keeps a running estimate of where they are developmentally, using Bayesian (Kalman-style) filtering. Its confidence grows with each session, and it shows nothing until a person has 10 or more scored sessions, a rule set before any real data existed.

**Simulation lab for testing the model** (2026)
A generator of 100,000 simulated people with known development, used to test every analysis method before it touches real data. Key finding: a cluster where people seem to settle is not proof of a stable state. Snapshots alone cannot tell the difference; you have to see how the system responds after a disturbance. Includes null tests, bootstrap confidence intervals, and a reproducibility record for every result.

**Knowledge graph of developmental and consciousness theory** (2026)
A structured map of 127 concepts from consciousness research, 44 described inner states, developmental stage bands, and 48 concepts from contemplative traditions. Every entry must cite its grounding before it can be added. Machine learning components (ordinal regression, graph neural networks) are designed but locked in code until there are 500+ held-out scored examples per feature to train them on.

## Research and Writing

- *World Models: Lineage, Formalism, Current State, and a Blueprint for a Developmental World Model*, 2026. Manuscript.
- Ten-paper preprint series in preparation for PsyArXiv, written as single-person (N-of-1) instrument studies with limitations stated. Early results: blind rescoring reliability ICC(2,1) = 0.786; one component explains 77% of the variance across all 8 features; state measured above structure in 96% of 73 paired sessions; a lasting developmental shift detected at +88 days.
- Provisional patents pending, sole inventor.

## Skills

**Modeling:** Bayesian filtering (Kalman), ordinal regression, graph neural networks, knowledge graphs, manifold learning, attractor analysis
**Evaluation:** pre-registration, held-out testing, permutation and null tests, bootstrap confidence intervals, ablation, blind rescoring, reproducibility
**Engineering:** Python (numpy, scikit-learn, pandas), FastAPI, React + TypeScript, Docker, Postgres/Supabase + pgvector, LLM fine-tuning and self-hosting
**Domain:** adult developmental psychology

## Education

M.A., East-West Psychology, California Institute of Integral Studies (in progress, 2026-2028) · Applied AI and Data Science, MIT Professional Education (2026) · B.A., Auburn University · Training in the STAGES developmental framework with Terri O'Fallon, PhD · Six years of contemplative training in the Indo-Tibetan lineage
