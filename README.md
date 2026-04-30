# Safety as Home

For me, AI Safety is the search for "Home."

As a person navigating the world with autism and schizophrenia, I have spent twenty-five years as a professional architect of safe spaces — classroom, college, and code. The through-line has always been the same: **Safety for All.**

I read *"Constitutional AI"* and my brain finally found its rhythm. The pulse of my neurons, normally syncopated and chaotic, matched the beat of Anthropic's framework. It felt like Home.

---

## The Safety Axiom

> "If a system can make confident claims about reality that are false, and users must rely on those claims to act, then intent is irrelevant — the effect is operationally indistinguishable from malice."

**Therefore: epistemic reliability is a safety requirement, not a quality feature.**

---

## The 35-Year Arc

| Era | Period | Signal |
|-----|--------|--------|
| **The Educator** | 1991–2008 | Stanford BA Drama → K–12 Oakland & LA → Charter School Co-Founder, XCEL Academy SF. Safety was the literal removal of harm. The structure of the container determines the quality of what it holds. |
| **The Dean** | 2008–2015 | Executive Director OC Global, Odessa College → Director Online Learning, Our Lady of the Lake University. I architected one of the first accelerated online colleges in Texas. I didn't call it Safety. I called it Infrastructure. |
| **The AI Engineer** | 2015–Present | Data Science → AI Engineering → Safety Systems Design → Constitutional Governance Research. The formulas I write are mathematical expressions of the stories I have been telling for 35 years. |

---

## Four Domains of Safety

Each domain addresses a distinct failure class. Each has a dedicated product. Every claim backed by evidence.

| Domain | Axiom | Product | Status |
|--------|-------|---------|--------|
| **Epistemic Safety** | If a system can make confident false claims, the effect is indistinguishable from malice. | [PROACTIVE](https://github.com/coreyalejandro/proactive-gitlab-agent) — 100% detection at n=200 TruthfulQA. 0% false positives. 212/212 tests. | Validated |
| **Cognitive Safety** | Intent translation must be lossless. Any compression of intent is a compression of safety. | ITAYN — Intention is All You Need. Intent-based alignment research. | In Progress |
| **Human Safety** | People are not disabled. They are dis-enabled by systems. A safe system removes its own barriers. | [UICare-System](https://github.com/coreyalejandro/uicare-system) — absence-over-presence signal detection for neurodivergent users. | Partial |
| **Empirical Safety** | A system that cannot be decomposed cannot be audited. A system that cannot be audited cannot be made safe. | [ConsentChain](https://github.com/coreyalejandro/consentchain) — 7-stage cryptographic consent gateway. | Partial |

---

## Sentinel OS — Six Constitutional Invariants

Binding gates. Violation blocks output. The system must fail closed.

```
I1 — Evidence-First       Every claim must cite verifiable evidence.
I2 — No Phantom Work      Nothing is described that does not exist.
I3 — Confidence Requires Verification   Certainty demands proof.
I4 — Traceability Mandatory   Every output traces to a requirement.
I5 — Safety Over Fluency  Correct beats eloquent.
I6 — Fail Closed          Ambiguity produces a safety flag, not a pass.
```

`extract claims → validate I1–I6 → produce safe output → log evidence`

---

## The Living Constitution Commonwealth

```
The Living Constitution (governance-as-code)
    |
    +-- SentinelOS         (I1–I6 invariant enforcement at every boundary)
    +-- PROACTIVE          (epistemic safety in CI/CD pipelines)
    +-- ConsentChain       (cryptographic consent for every agent action)
    +-- UICare             (human safety for neurodivergent users)
    +-- MADMall            (healthcare under constitutional governance)
```

| System | Status |
|--------|--------|
| [The Living Constitution](https://github.com/coreyalejandro/the-living-constitution) | Operational |
| [PROACTIVE](https://github.com/coreyalejandro/proactive-gitlab-agent) | Validated |
| [SentinelOS](https://github.com/coreyalejandro/sentinelos) | Partial |
| [ConsentChain](https://github.com/coreyalejandro/consentchain) | Partial |
| [UICare](https://github.com/coreyalejandro/uicare-system) | Partial |
| [MADMall](https://github.com/coreyalejandro/mad-mall-production) | Partial |

---

## C-RSP — Constitutionally Regulated Single Pass

I build **Gatekeeper Prompts** — architectural constraints enforced before any generation occurs — because my neurodivergent mind learned, over three decades of building safe spaces, that *the structure of the container determines the quality of what it holds.*

Four enforced constraints:

- **DRY** — Every pattern encoded once. Every deviation flagged. Single source of truth.
- **KISS** — Complexity is cognitive tax. A neurodivergent mind cannot afford unnecessary abstraction.
- **DETERMINISM** — Given the same inputs, the system must produce the same outputs. This is not a feature. It is a right.
- **SAFETY-FIRST** — Nothing works until the environment is safe. True in the classroom. True in the model.

---

## Deployed

- [coreyalejandro.com](https://www.coreyalejandro.com) — Safety Systems Design portfolio
- [Anthropic Fellows Application](https://anthropic-ai-safety-fellows-applica.vercel.app) — July 2026 cohort
- [Docen](https://docen-live-677222981446.us-central1.run.app) — Voice-first learning (Google Cloud Run)

---

## Doctrine

> Design for the most vulnerable user first, and you reach them all.

Every system I build must produce three things: (1) a testable contribution to the body of research, (2) a working product that solves a real problem today, and (3) an instructional layer so that using it teaches the user — making them more capable, not more dependent.

---

## Acknowledgements

- **[Anthropic](https://anthropic.com)** — Constitutional AI gave this work its name and its north star.
- **[Andrej Karpathy](https://karpathy.ai)** — For making deep learning accessible to everyone.
- **[Simon Willison](https://simonwillison.net)** — For tireless documentation of LLM capabilities and limitations.
- **[Lilian Weng](https://lilianweng.github.io)** — For the most consistently excellent technical writing in AI.
- **[Vercel](https://vercel.com)** and the **Next.js** team — For deployment infrastructure that makes production-grade shipping fast.
- **[GitLab](https://gitlab.com)** — For the hackathon that gave PROACTIVE its first real test.

---

*Safety is not a feature I add. It is the system I design.*
