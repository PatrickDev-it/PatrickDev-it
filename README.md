# Patrick Dev — Product & Systems Engineer

I design software around explicit invariants, failure behavior and measurable evidence. My strongest work
sits at the boundary between applied AI, product engineering, security and operable systems—not around
framework count or feature volume.

[Engineering portfolio](https://patrickdev-it.github.io) ·
[Flagship release](https://github.com/PatrickDev-it/cowork-prompt-enhancer/releases/tag/v1.0.0) ·
[LinkedIn](https://www.linkedin.com/in/patrickdev-it/) ·
[Email](mailto:jobs@patrickdev.it)

## Flagship: Cowork Prompt Enhancer

[Cowork Prompt Enhancer](https://github.com/PatrickDev-it/cowork-prompt-enhancer) is a local-first
intent-to-specification compiler for executing AI systems. It treats model output as an unreliable
dependency and makes provider behavior, fallback, resource use and evaluation observable.

| Engineering concern | Implemented evidence |
|---|---|
| Provider independence | deterministic mock, supervised local inference and OpenAI-compatible adapters behind one typed contract |
| Protocol security | versioned WebSocket schemas, loopback default, single-use HMAC challenge for remote exposure and bounded frames |
| Failure containment | queue limits, per-session concurrency, cancellation, reconnect without duplicate execution and deterministic fallback |
| Capability safety | advertised file operations plus canonical confinement beneath the session root |
| Evaluation | versioned 64-case corpus, raw records, environment metadata and reproducible baseline/compiler comparisons |
| Release engineering | immutable `v1.0.0`, SBOM, dependency inventory, checksums, provenance and benchmark evidence |

On the published eight-case local subset, structural validity moved from **0.333 to 0.792** and the
executability rubric from **0.725 to 0.975**. Explicit-requirement recall moved from **1.000 to 0.917**;
that trade-off and the lexical methodology are published rather than hidden. The complete release gate
passes **53 Bun tests, 79 pytest tests and 9 integration tests** with zero known dependency findings.

[Read the architecture](https://github.com/PatrickDev-it/cowork-prompt-enhancer/blob/main/docs/architecture.md) ·
[Inspect evaluation evidence](https://github.com/PatrickDev-it/cowork-prompt-enhancer/tree/main/evaluation/results) ·
[Run the three-minute mock path](https://github.com/PatrickDev-it/cowork-prompt-enhancer#three-minute-mock-quickstart)

## Product engineering: AutoBlog CMS 2.0

[AutoBlog CMS](https://github.com/PatrickDev-it/AutoBlog-CMS) is a full-stack editorial release candidate
built around one durable application core: database sessions, workspace-scoped RBAC, immutable revisions,
optimistic concurrency, review transitions, leased publication jobs, bounded media and explicit AI suggestions.

The candidate records **19 unit, 25 integration, 10 E2E, 6 accessibility, 5 visual, 2 direct performance
tests and 6 Lighthouse runs**. Measured lab budgets include 0 CLS, 138.6/216.2 KiB initial JavaScript for
marketing/workspace, and Lighthouse accessibility/SEO medians of 1.00.

It is intentionally not presented as released: historical provider credentials require owner rotation,
and the public runtime still needs durable libSQL, scheduling and anonymous demo access. Source evidence is
available in [PR #3](https://github.com/PatrickDev-it/AutoBlog-CMS/pull/3); pinning follows a green protected
merge and verified `v2.0.0`, not implementation intent.

## Engineering judgment I want reviewed

- **Architecture:** application policy and domain invariants precede database, cloud and AI adapters.
- **Reliability:** retries require idempotency; asynchronous work owns leases, recovery and duplicate delivery.
- **Security:** identity, capability and workspace context are enforced at server boundaries, including negative tests.
- **Evaluation:** every metric carries workload, environment, method, limitations and a reproduction command.
- **Operations:** releases promote immutable artifacts and document health, rollback, provenance and residual risk.
- **Scope:** a modular monolith is the default until measured constraints justify distribution.

## Additional systems

- [Authenticated Privacy Proxy Stack](https://github.com/PatrickDev-it/VPN): containerized network policy,
  host automation, infrastructure-as-code and reproducible smoke testing.
- [Product Image Classifier](https://github.com/PatrickDev-it/Product-image-categorizer): scientific ML work
  being hardened around data lineage, calibration, error slices and portable inference.
- [Multi-tenant Loyalty Platform](https://github.com/PatrickDev-it/Electronic-Invoice-Management): backend
  modernization focused on tenant isolation, idempotency, durable jobs, auditability and recovery.

## Technical discussion

The best interview starting points are failure semantics in the Prompt Enhancer protocol, evaluation bias
in generative systems, or AutoBlog's revision/concurrency model. I am based in Rome, Italy and available for
product, systems and platform engineering roles.

[Schedule the conversation by email](mailto:jobs@patrickdev.it) or
[connect on LinkedIn](https://www.linkedin.com/in/patrickdev-it/).

This profile uses no activity widgets, tracking pixels or generated contribution claims.
