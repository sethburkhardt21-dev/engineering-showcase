# Engineering Showcase

A curated portfolio of evidence-first developer tools for artifact integrity, source-bound extraction, reviewable evidence, workflow reliability, governed data, and point-in-time replay.

> **Current release state:** the six canonical project homes below are public documentation previews. No qualified software release is published from these homes yet. Repository presence is not evidence of implementation maturity, independent review, or production readiness.

## Find the right project

| If you need to… | Project | Current public availability |
|---|---|---|
| Prove exactly which bytes moved and detect tampering or incomplete transfer | [Artifact Custody Toolkit](https://github.com/sethburkhardt21-dev/artifact-custody-toolkit) | Documentation preview |
| Extract assertions while preserving traceability to source material | [Source-Bound Extraction Toolkit](https://github.com/sethburkhardt21-dev/source-bound-extraction-toolkit) | Documentation preview |
| Inspect source-linked evidence, compare snapshots, and export navigable reports | [Evidence Observatory Viewer](https://github.com/sethburkhardt21-dev/evidence-observatory-viewer) | Documentation preview |
| Reproduce uncertain workflow outcomes and compare unsafe retry vs. reconciliation | [Workflow Reliability Lab](https://github.com/sethburkhardt21-dev/workflow-reliability-lab) | Documentation preview |
| Model provenance, explicit review, governed queries, and rollback using synthetic data | [Governed Evidence Database Reference](https://github.com/sethburkhardt21-dev/governed-evidence-database-reference) | Scope evaluation; no code release |
| Test point-in-time information integrity, leakage controls, and calibration on synthetic event streams | [Prediction Market Replay Lab](https://github.com/sethburkhardt21-dev/prediction-market-replay-lab) | Narrow offline scope accepted; no code release |

## What ties the portfolio together

These projects are designed around the same operating principles:

- **Source-bound evidence.** Outputs should preserve enough identity and provenance to trace what was actually inspected or transformed.
- **Own-input proof.** A canned demo is not enough. Qualified releases must document a path that works on user-supplied supported input.
- **Negative-path behavior.** Malformed, missing, stale, ambiguous, tampered, late, or unknown data should remain visible rather than being silently converted into success.
- **Offline-first demonstrations.** The default public examples should not require private corpora, credentials, funded accounts, or live external side effects.
- **Measured claims only.** Test counts, browser behavior, platform support, performance, and compatibility are stated only when observed on the exact published bytes.
- **Clear release boundaries.** Documentation previews, private development checkpoints, independently reviewed candidates, and public releases are different states.

## Release standard

A qualified public code release is expected to include:

1. install instructions that execute against the published version;
2. a runnable synthetic example plus an own-input workflow;
3. meaningful failure and recovery cases;
4. exact version/artifact identities and observed test evidence;
5. explicit assumptions, unsupported cases, and environment limits;
6. required attribution, notices, and redistribution decisions.

Until those gates are satisfied, the canonical public repositories remain documentation homes rather than software distributions.

## Portfolio map

```text
bytes & transfer
    └─ Artifact Custody Toolkit

source → candidate assertions → review
    └─ Source-Bound Extraction Toolkit

source-linked evidence → inspect / compare / export
    └─ Evidence Observatory Viewer

workflow events → uncertain outcome → reconcile / retry analysis
    └─ Workflow Reliability Lab

provenance → staged assertion → review → governed query → rollback
    └─ Governed Evidence Database Reference

synthetic event stream → point-in-time visibility → leakage checks → calibration
    └─ Prediction Market Replay Lab
```

## Existing related work

[Extraction Factory](https://github.com/sethburkhardt21-dev/extraction-factory) is a separate existing public repository. It is not replaced by this portfolio, and its qualification state should be evaluated on its own published evidence.

## Status language

- **Documentation preview** — public project description; no qualified code release.
- **Scope accepted** — a bounded product contract is defined, but public implementation is not yet released.
- **Review candidate** — exact private development bytes may be under review; this does not make them public.
- **Qualified release** — public code/artifacts have passed the stated release gates for that exact version.

This front door intentionally avoids claiming more maturity than the published evidence establishes.
