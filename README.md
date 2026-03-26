# Safety Systems Design

I design safety-critical systems where the governance is the architecture — not documentation bolted on after the fact. Constitutional enforcement, epistemic validation, neurodivergent-first design.

## The Living Constitution Commonwealth

```
The Living Constitution (governance-as-code)
    |
    +-- SentinelOS (invariant enforcement at every boundary)
    |
    +-- PROACTIVE (epistemic safety in CI/CD pipelines)
    +-- MADMall (healthcare product under constitutional governance)
    +-- ConsentChain (cryptographic consent for every agent action)
    +-- UICare (human safety monitoring for neurodivergent users)
```

## Core Systems

| System | What It Does | Status |
|--------|-------------|--------|
| [**The Living Constitution**](https://github.com/coreyalejandro/the-living-constitution) | Constitutional governance-as-code. Five articles, four safety domains, six-agent republic. The supreme law. | Operational |
| [**PROACTIVE**](https://github.com/coreyalejandro/proactive-gitlab-agent) | Catches epistemic failures in merge requests. 100% detection (n=19 violations), 0 false positives. 212/212 tests passing. | Validated |
| [**SentinelOS**](https://github.com/coreyalejandro/sentinelos) | TypeScript invariant enforcement. Hexagonal architecture. 6 invariants (I1-I6) as executable constraints. | Partial |
| [**MADMall**](https://github.com/coreyalejandro/mad-mall-production) | Virtual luxury mall & teaching clinic for Black women with Graves' disease. Primary TLC use case. | Partial |
| [**ConsentChain**](https://github.com/coreyalejandro/consentchain) | 7-stage action gateway. Every agent action consented, logged, and revocable. | Partial |
| [**UICare**](https://github.com/coreyalejandro/uicare-system) | Absence-over-presence signal detection. Developer safety for neurodivergent users. | Partial |

## Four Safety Domains

| Domain | What It Prevents | Primary System |
|--------|-----------------|----------------|
| **Epistemic Safety** | False claims, hallucinations, phantom completions | PROACTIVE |
| **Human Safety** | Cognitive overload, inaccessible design, harm to vulnerable users | UICare + MADMall |
| **Cognitive Safety** | False understanding, unsafe mental models in learning | Docen |
| **Empirical Safety** | Consent opacity, unmeasured safety, unauditable actions | ConsentChain |

## Evidence

- **PROACTIVE**: 100% detection rate across 8 controlled test cases (n=19 violations spanning 6 invariant types), 0 observed false positives (validation report VR-V-15C6, 2026-01-24). 212/212 tests passing. Submitted to [GitLab AI Hackathon](https://gitlab.com/gitlab-ai-hackathon/participants/28441830).
- **SentinelOS**: 1,037 LOC source + 994 LOC tests. 180+ Object.freeze calls. Zero cross-adapter dependencies. Hexagonal ports & adapters architecture.
- **MADMall**: 6 apps, 22 packages, ~152K LOC. Clerk auth, Stripe payments, Prisma/PostgreSQL, Python ML with CRISP-DM methodology. Healthcare for a real, underserved population.
- **ConsentChain**: 7-stage gateway curl-tested. Prisma schema with 5 models. 8 Turborepo packages.

## Deployed

- [coreyalejandro.com](https://www.coreyalejandro.com) — Portfolio
- [Docen](https://docen-live-677222981446.us-central1.run.app) — Voice-first learning (Google Cloud Run)

## Doctrine

> Design for the most vulnerable user first, and you reach them all.

Every system I build must produce three things: (1) a testable contribution to the body of research, (2) a working product that solves a real problem today, and (3) an instructional layer so that using it teaches the user — making them more capable, not more dependent.

## Background

Education, instructional design, and residential care before AI. The same doctrine — safety as a systems property, not a feature — applied to classrooms and care facilities before it applied to AI systems. Stanford BA. Built from lived experience as a neurodivergent person navigating systems that were never designed for safety.

## Acknowledgements

This work stands on the shoulders of extraordinary contributions to the field:

- **[Anthropic](https://anthropic.com)** and the entire Claude team — Constitutional AI gave this work its name and its north star. The model spec, the alignment research, the commitment to safety-by-design. Claude Code is the execution environment that made the Living Constitution possible.
- **[Andrej Karpathy](https://karpathy.ai)** — For making deep learning accessible to everyone. The neural network lecture series, minGPT, nanoGPT, and the philosophy that the best way to understand AI is to build it from scratch. His teaching shaped how I think about systems.
- **[Simon Willison](https://simonwillison.net)** — For tireless documentation of LLM capabilities and limitations. His work on prompt injection awareness and tool-use patterns directly influenced PROACTIVE's invariant design.
- **[Lilian Weng](https://lilianweng.github.io)** — For the most consistently excellent technical writing in AI. Her surveys on agent architectures and reasoning informed the Agent Republic design.
- **[Vercel](https://vercel.com)** and the **Next.js** team — next-forge, Turborepo, and the deployment infrastructure that makes production-grade shipping fast.
- **[GitLab](https://gitlab.com)** — For the AI Hackathon that gave PROACTIVE its first real test environment and the Duo integration framework.
- **[Google](https://cloud.google.com)** — For the Gemini Live API hackathon that produced Docen and proved voice-first accessibility is viable at production scale.
- The **open-source community** — Every dependency, every framework, every tool. Nothing is built alone.

---

*Safety is not a feature I add. It is the system I design.*
