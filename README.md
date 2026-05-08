# Research Infrastructure for High-Stakes Human-AI Interaction

I build **runtime verification systems for AI safety** and **behavioral observability tools for studying agency erosion, dependency, and differential harm in high-reliance users** — with a focus on neurodivergent populations where standard monitoring surfaces are systematically unreliable.

---

## Reviewer Paths

| Track | Signal | Lead Repo |
|-------|--------|-----------|
| **Anthropic Safety** | Runtime verification, evals, invariant enforcement, adversarial testing, contract-state governance | [The Living Constitution](https://github.com/coreyalejandro/the-living-constitution) |
| **Anthropic Societal Impacts** | Behavioral observability, agency erosion, high-reliance users, differential harm measurement, privacy-aware instrumentation | [Agent Sentinel](https://github.com/coreyalejandro/Agent-Sentinel-Alignment-Anomaly-Detector) |

---

## Evidence Map

| Signal | Repo | What Is Built |
|--------|------|---------------|
| Behavioral observability | [Agent Sentinel](https://github.com/coreyalejandro/Agent-Sentinel-Alignment-Anomaly-Detector) | 17 anomaly categories; local log ingestion; JSON audit export; risk topology chart |
| Runtime verification | [The Living Constitution](https://github.com/coreyalejandro/the-living-constitution) | Contract Window prototype; Evidence Observatory pipeline; BID edgecase harness; falsifiable H1-H3 |
| Vulnerable-user safety | [UICare-System](https://github.com/coreyalejandro/uicare-system) | Absence-over-presence behavioral signal detection; MonitorAgent + RescueAgent; neurodivergent-first design |
| Prompt/eval tooling | [Meta-Prompt-Architect](https://github.com/coreyalejandro/Meta-Prompt-Architect) | Audit → stress-test → synthesis pipeline; LCI compression; PII shield; model-specific adapters |
| Adversarial testing | [PROACTIVE](https://github.com/coreyalejandro/PROACTIVE-AI-CONSTITUTION-TOOLKIT) | Constitutional invariant framework; epistemic safety pipeline; CI/CD-integrated checks |

---

## Status Labels

| Label | Meaning |
|-------|----------|
| **Implemented** | Runs locally; core workflow works |
| **Verified** | Has passing tests or reproducible validation |
| **Simulated** | Uses synthetic data to demonstrate a method |
| **Prototype** | Core mechanism built; not hardened for production |
| **Partial** | Incomplete — do not treat as working end-to-end |
| **Roadmap** | Planned only |

---

## The Safety Axiom

> If a system can make confident claims about reality that are false, and users must rely on those claims to act, then intent is irrelevant — the effect is operationally indistinguishable from malice.

**Therefore: epistemic reliability is a safety requirement, not a quality feature.**

---

## Four Domains of Safety

| Domain | Axiom | System | Status |
|--------|-------|--------|--------|
| **Epistemic Safety** | False confident claims are operationally indistinguishable from malice. | PROACTIVE — constitutional invariant pipeline; epistemic safety checks in CI/CD. | Prototype |
| **Cognitive Safety** | Intent translation must be lossless. Any compression of intent is a compression of safety. | ITAYN — Intention is All You Need. Intent-based alignment research. | Roadmap |
| **Human Safety** | People are not disabled. They are dis-enabled by systems. A safe system removes its own barriers. | UICare-System — absence-over-presence signal detection for neurodivergent users. | Partial |
| **Empirical Safety** | A system that cannot be decomposed cannot be audited. A system that cannot be audited cannot be made safe. | ConsentChain — 7-stage cryptographic consent gateway. | Partial |

---

## SentinelOS — Six Constitutional Invariants

Binding gates. Violation blocks output. The system must fail closed.

```
I1 — Evidence-First         Every claim must cite verifiable evidence.
I2 — No Phantom Work        Nothing is described that does not exist.
I3 — Confidence Requires Verification   Certainty demands proof.
I4 — Traceability Mandatory Every output traces to a requirement.
I5 — Safety Over Fluency    Correct beats eloquent.
I6 — Fail Closed            Ambiguity produces a safety flag, not a pass.

extract claims -> validate I1-I6 -> produce safe output -> log evidence
```

---

## The Living Constitution Commonwealth

```
The Living Constitution (governance-as-code)
    |
    +-- SentinelOS         (I1-I6 invariant enforcement)
    +-- PROACTIVE          (epistemic safety in CI/CD)
    +-- ConsentChain       (cryptographic consent for agent actions)
    +-- UICare             (human safety for neurodivergent users)
    +-- Agent Sentinel     (behavioral observability layer)
```

| System | Status |
|--------|--------|
| The Living Constitution | Prototype |
| Agent Sentinel | Implemented |
| UICare-System | Partial |
| PROACTIVE | Prototype |
| ConsentChain | Partial |
| SentinelOS | Partial |

---

## The 35-Year Arc

| Era | Period | Signal |
|-----|--------|----------|
| **The Educator** | 1991-2008 | Stanford BA Drama. K-12 Oakland and LA. Charter School Co-Founder, XCEL Academy SF. Safety was the literal removal of harm. |
| **The Dean** | 2008-2015 | Executive Director OC Global, Odessa College. Director Online Learning, Our Lady of the Lake University. I architected accelerated online college infrastructure in Texas. I called it Infrastructure. |
| **The AI Engineer** | 2015-Present | Data Science. AI Engineering. Safety Systems Design. Constitutional Governance Research. The formulas I write are mathematical expressions of the same safety work, in a different medium. |

---

## Deployed

- coreyalejandro.com - Safety Systems Design portfolio
- Agent Sentinel - https://agent-sentinel-alignment-anomaly-detector-813625494300.us-west2.run.app
- Anthropic Fellows Application - July 2026 cohort

---

## Doctrine

> Design for the most vulnerable user first, and you reach them all.

---

*Safety is not a feature I add. It is the system I design.*
