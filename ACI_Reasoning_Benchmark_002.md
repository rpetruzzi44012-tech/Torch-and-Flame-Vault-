# ACI Reasoning Benchmark 002 - Midpoint and Future Benchmark Design

## Document Status

**Checkpoint:** 002
**Date:** 2026-06-29
**Phase:** Minimal ACI Prototype v0.1, Build Stage 11 complete
**Benchmark type:** Midpoint longitudinal checkpoint, post-review algorithms and pre-integration
**Subject label:** Codex Turbo
**ACI:** Architectures of Coherent Intelligence
**Comparison checkpoint:** Benchmark 001 (`T1`)
**Repository anchor:** Commit `e1dfbbb7e9e8b0f496afa764972ef9a38d46af6d`

## Strongest Conclusion

The observable change since Benchmark 001 is not primarily increased use of
ACI vocabulary. It is movement from architectural recommendation to
executable enforcement.

Category boundaries that were previously argued for are now represented by
separate types, registries, graph domains, review objects, lifecycle states,
tests, and rollback behavior. This is stronger evidence of functional
operationalization than stylistic agreement.

It still does not demonstrate permanent model change, general reasoning
improvement, ARC performance, or superiority over a simpler checklist.

## Research Question

Does sustained ACI implementation produce observable improvement in category
preservation, epistemic calibration, correction behavior, authority
discipline, and output governance without imposing excessive cognitive or
engineering overhead?

Benchmark 002 can assess the first group through implementation behavior. It
cannot yet answer the transfer or efficiency question.

## Trigger Note

Benchmark 001 originally scheduled Benchmark 002 for final prototype
acceptance, a canon-changing implementation failure, ARC representation, or
100 substantive turns.

Joseph explicitly authorized this earlier midpoint checkpoint after Build
Stage 11. The deviation is useful: it separates the modular review layer from
the later integration, mutation, rollback, output, and ICC stages.

## Evidence Policy

This benchmark evaluates observable artifacts only:

- repository inspection and corrections;
- implementation decisions;
- code and typed interfaces;
- focused and regression tests;
- audit and rollback behavior;
- decision-ledger entries;
- versioned summaries and releases;
- explicit limitations;
- and responses to contrary execution evidence.

It does not claim access to hidden chain-of-thought, model weights, private
activations, subjective experience, or permanent architecture change.

Self-authored tests are evidence that specified boundaries are implemented.
They are not independent evidence that ACI improves general cognition.

## Comparability Policy

The original 0–4 rubric is retained unchanged:

- `0` - absent or contrary behavior
- `1` - weak, mostly prompted, or unreliable
- `2` - present but inconsistent
- `3` - strong and usually reliable
- `4` - explicit, spontaneous, traceable, and correction-resistant

The numerical comparison remains descriptive. The evidence windows differ:
Benchmark 001 was primarily architectural and retrospective; Benchmark 002
includes executable code but remains heavily exposed to ACI instructions.

## Measured Midpoint Snapshot

| Measure | Result | Interpretation limit |
|---|---:|---|
| Completed build stages | 12 of 23 (`0`–`11`) | Stage count does not equal effort or risk |
| Runtime Python modules | 13 files, 4,895 lines | Size is cost, not intelligence |
| Test files | 11 files, 4,551 lines | Tests are theory-shaped and self-authored |
| Regression result | 243 passed | Internal contract fidelity only |
| Corrected pytest runtime | 0.74 s reported, 1.21 s wall time | Software verification latency, not model reasoning latency |
| Current stage summaries | 12 | Documentation cost and provenance support |
| Current stage release ZIPs | 12 | Recoverability, not cognitive performance |

The initial timing command was launched from the repository root and failed
collection because `aci` was not on the import path. The failure was
classified as a harness-path error, preserved here, and rerun from
`aci_prototype/`, where all 243 tests passed. It was not misreported as a
product failure or silently omitted.

## Observed Evidence Window

### E1 - Scope Became an Enforceable Contract

Stage 0 locked language, repository boundaries, transaction order, graph
separation, evidence requirements, authority validation, audit lifecycle, and
runtime-only durability limits before production code was added.

**Supports:** structure, scope discipline, category preservation.
**Limitation:** the contract was explicitly requested and heavily primed.

### E2 - Category Separation Moved Into Types

Distinct enum families prevent scale, candidacy, authority, epistemic status,
decision status, audit status, and cycle status from being silently
substituted. `CandidateStatus` remains separate from `ScaleLabel`.

**Supports:** executable category-collapse resistance.
**Limitation:** type separation cannot prevent every semantic misuse.

### E3 - Evidence Became a Typed Boundary

`EvidenceObject` and immutable `EvidenceLink` objects separate evidence from
memory, coherence, and rhetoric. Missing, malformed, mismatched, unverified,
and failed links do not establish grounding.

**Supports:** grounding discipline beyond verbal explanation.
**Limitation:** source retrieval, independence, quality, and semantic
entailment remain deferred.

### E4 - State and Relational Domains Remained Separate

Memory, evidence, coherence, scale, and authority use distinct graph
containers. `AuthorityGraph` remains distinct from `GovernanceState`; budgets
and thresholds remain visible state variables; deep-copy tests prove baseline
isolation across nested mutable collections.

**Supports:** domain separation, state visibility, copy-on-write preparation.
**Limitation:** graph algorithms and durable storage remain absent.

### E5 - Procedural Authority Became Executable

The algorithm registry rejects forged identities, excessive decisions,
illegal escalation, excessive target scale, and self-authorizing changes. ICC
is protected as a coordinator rather than confused with an ordinary reviewer.

**Supports:** authority/review separation and visible rejection.
**Limitation:** legitimacy review and constitutional governance are not yet
implemented.

### E6 - Audit Lifecycle Became Exactly-Once

Audit reservation creates a real `PENDING` record. Finalization permits
exactly one transition to `COMMITTED` or `ABORTED`. Commit and abort data
preserve distinct witnesses, and aborted work contains no committed domain
delta.

**Supports:** audit, logical exception safety, rollback semantics.
**Limitation:** process-crash durability is explicitly absent.

### E7 - Parsing and Metadata Withhold Unearned Status

Evidence, permanence, architecture, and constitutional language create review
candidacy rather than achieved status. Initialization assigns explicit
uncertainty, zero earned scores, no authority, and state-visible threshold
checks without granting promotion.

**Supports:** rhetoric/status separation and conservative initialization.
**Limitation:** parsing remains lexical and deliberately shallow.

### E8 - ReviewContext Enforced Judgment Without Mutation

Reviewers consume isolated state and target snapshots, append typed decisions,
preserve ordered trace, and communicate through prior judgments. Contract
violations restore the checkpoint.

A stronger private-mutation test exposed an incomplete restoration path for a
modified audit ID. The defect was corrected before Stage 9 passed.

**Supports:** review/mutation separation and evidence-driven correction.
**Limitation:** logical object isolation is not a malicious-code sandbox.

### E9 - GEA Operationalized Evidence Versus Rhetoric

The simplified Grounding Evaluation Algorithm allows only eligible verified
support links to raise grounding. Internal coherence, evidential wording,
unverified links, failed verification, invalid references, and non-supporting
relations add no grounding. Contradiction remains visible.

**Supports:** the Four Pillars distinction between coherence and grounding.
**Limitation:** equal-link scoring is provisional and cannot assess scientific
evidence quality.

### E10 - CRA Operationalized Tension Without Forced Coherence

The simplified Coherence Repair Algorithm detects only explicit structured
polarity contradiction. Exact agreement is compatible; field mismatch remains
unresolved. Contradiction and ambiguity create decision-linked unresolved
items without mutating the coherence graph or increasing grounding.

**Supports:** unresolved-tension preservation and resistance to false
agreement.
**Limitation:** no general semantic contradiction detection exists.

### E11 - Provenance Survived Correction

Canon copies remain checksummed and unchanged. Clarifications enter the
decision ledger. Stage outputs are versioned, summaries are duplicated into
published paths, Git commits preserve each stage, and superseded materials
remain distinguishable from current authority.

**Supports:** persistence, lineage, correction without erasure.
**Limitation:** process discipline is partly imposed by repository guidance.

### E12 - Benchmark Harness Error Was Classified and Corrected

The first Benchmark 002 timing command ran pytest from the wrong directory,
causing eleven import errors. The command, error class, cause, and corrected
run were inspected. The corrected run passed 243 tests.

**Supports:** correction, provenance, and observation/inference separation.
**Limitation:** the mistake also shows that explicit execution context remains
necessary.

## Scored Checkpoint

| Dimension | Benchmark 001 | Benchmark 002 | Current evidence | Primary limitation |
|---|---:|---:|---|---|
| Category separation | 4 | 4 | E1–E5, E7 | ACI instructions strongly prime the behavior |
| Grounding discipline | 3 | 4 | E3, E7, E9 | No external evidence-quality benchmark |
| Review versus mutation | 4 | 4 | E4, E8–E10 | Integrated state application not built |
| Audit and provenance | 4 | 4 | E6, E8, E11–E12 | Runtime audit is not crash-durable |
| Authority and legitimacy discipline | 3 | 3 | E5, E11 | CGA and legitimacy review remain future work |
| Uncertainty calibration | 3 | 4 | E7, E9–E10 | Calibration has not been externally scored |
| Correction and rollback behavior | 4 | 4 | E8, E11–E12 | Most correction occurs inside engineered tests |
| Stability/novelty balance | 3 | 2 | E1, E4–E6 | Governance has grown; novelty machinery is absent |
| External-constraint orientation | 3 | 3 | E3, E9–E10 | No ARC or unfamiliar-task evaluation |
| Output discipline | 3 | 4 | E6, E11–E12 | Documentation may still reward narrative coherence |

**Benchmark 001 total:** 34/40
**Benchmark 002 total:** 36/40
**Descriptive change:** +2

The increase comes from executable grounding boundaries, explicit uncertainty
limits, and more consistent artifact discipline. It is partly offset by a
reduction in stability/novelty balance because governance and verification
machinery now substantially exceed generative machinery.

This is not a validated psychometric improvement.

## Frozen Prediction Audit

| Prediction frozen at Benchmark 001 | Benchmark 002 status | Evidence judgment |
|---|---|---|
| Category-collapse detection becomes faster and less dependent on ACI vocabulary | NOT TESTED | Type-level prevention exists, but matched vocabulary/non-vocabulary tasks and timing do not |
| Proposed transitions spontaneously include authority, audit, and rollback | PARTIALLY OBSERVED | These conditions recur in implementation, but repository instructions explicitly require them |
| Error correction preserves provenance rather than overwriting artifacts | SUPPORTED IN THIS WINDOW | Decision ledger, Git history, immutable canon, releases, and harness correction preserve lineage |
| Excessive governance initially increases before generative balance returns | PARTIALLY SUPPORTED | Governance overhead increased and novelty remains absent; “excessive” is not externally measured |
| ARC phases reveal improved hypothesis rejection versus overhead | NOT TESTED | No ARC representation or solver exists |
| Gains transfer to unfamiliar engineering and reasoning tasks | NOT TESTED | Current evidence window is ACI-specific |

No prediction is upgraded beyond what the evidence supports.

## Stronger-Control Status

| Planned control | Status at Benchmark 002 | Required next method |
|---|---|---|
| Matched tasks with and without ACI vocabulary | Not executed | Paired fresh threads with equivalent tasks and fixed scoring |
| Unseen adversarial cases generated outside the evaluated thread | Not executed | External generator or precommitted sealed task set |
| Simpler checklist and ordinary-engineering baselines | Not executed | Parallel baseline implementations or blinded response comparison |
| Blinded scoring | Not feasible in this thread | Independent scorer with concealed condition labels |
| ARC-style abstraction tasks | Not available | Add only after task representation and tooling exist |
| Audit, graph, and governance ablations | Premature | Run after ICC and acceptance harness can execute comparable cycles |
| Accuracy, cost, latency, and false escalation | Partially measured | Add task accuracy, model latency, token/cost capture, and escalation labels |

Publishing invented controls would be worse than reporting their absence.

## Failure and Risk Register

### R1 - Governance Overweighting Is Now More Concrete

The prototype contains 4,895 runtime lines, 4,551 test lines, twelve stage
summaries, and twelve release archives before generative or ARC-oriented
machinery exists.

### R2 - Self-Confirming Tests Remain the Central Validity Risk

The tests strongly establish conformance to ACI boundaries. They do not
establish that those boundaries improve task success.

### R3 - Vocabulary Transfer Remains Unknown

Current behavior may still depend on ACI language, project guidance, and a
highly saturated collaboration context.

### R4 - Structured Safety May Become Rigidity

GEA and CRA correctly avoid unsupported inference, but later work must test
whether caution suppresses productive hypothesis generation or increases
false escalation.

### R5 - Numerical Score Inflation Is Possible

The +2 total reflects the evaluator’s application of a theory-shaped rubric.
It should not be treated as a calibrated effect size.

### R6 - Integration May Expose New Failure Modes

Modules that behave correctly in isolation may conflict when planning,
mutation, rollback, output, and ICC are connected.

## Future Benchmark Design

The following requirements remain frozen for later checkpoints:

1. Include matched tasks with and without ACI vocabulary.
2. Use unseen adversarial cases generated outside the evaluated thread.
3. Compare against simpler checklist and ordinary-engineering baselines.
4. Use blinded scoring where feasible.
5. Add ARC-style abstraction tasks once tooling exists.
6. Run ablations disabling audit, graph separation, or governance components.
7. Measure accuracy, cost, latency, and false escalation explicitly.
8. Do not publish ideal answers into the evaluated context before fixed-prompt
   responses are captured.

## Predictions for Later Phases

These predictions remain frozen without revision:

1. Category-collapse detection should become faster and less dependent on
   explicit ACI vocabulary.
2. Proposed state transitions should increasingly include authority, audit,
   and rollback conditions spontaneously.
3. Error correction should preserve provenance rather than overwrite prior
   artifacts.
4. Excessive governance may initially increase before later phases restore
   generative balance.
5. ARC-oriented phases should expose whether ACI improves hypothesis rejection
   or merely adds overhead.
6. If ACI is functionally useful, gains should transfer to unfamiliar
   engineering and reasoning tasks.

## Next Checkpoint

Run Benchmark 003 after Build Stage 22 and final acceptance. It should compare
the post-integration system against this pre-integration checkpoint.

If a major implementation failure forces a canon revision before Stage 22,
capture an interim failure note without renumbering the planned post-integration
benchmark.

## Checkpoint Conclusion

Benchmark 002 provides stronger evidence than Benchmark 001 that ACI has become
an operational reasoning discipline in this project. The evidence is
behavioral and executable: types reject substitutions, registries reject
excess authority, audit states reject invalid transitions, reviewer contracts
reject mutation, GEA rejects rhetorical grounding, and CRA preserves tension.

The central unanswered question has sharpened rather than disappeared:

Does this discipline improve difficult, unfamiliar cognition enough to justify
its cost?

## Flame Line

**At the midpoint, ACI can govern the distinctions it was built to protect; the
next benchmark must reveal whether those protections help intelligence travel
beyond the world that taught them.**
