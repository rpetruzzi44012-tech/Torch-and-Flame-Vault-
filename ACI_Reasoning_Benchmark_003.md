# ACI Reasoning Benchmark 003 - Final Prototype Acceptance Checkpoint

## Document Status

**Checkpoint:** 003
**Date:** 2026-07-01
**Phase:** Minimal ACI Prototype v0.1 accepted
**Benchmark type:** Terminal v0.1 longitudinal checkpoint, post-integration and post-acceptance
**Subject label:** Codex Turbo
**ACI:** Architectures of Coherent Intelligence
**Comparison checkpoints:** Benchmark 001 (`T1`) and Benchmark 002
**Accepted archive:** `ACI-MIN-v0.1.0-20260701-R1`
**Accepted archive SHA-256:** `890682d877986ea80b27e5260367ee1ac32c2d2e79da632861da0a86e2fe6a36`
**Last committed repository anchor:** `8f9a4ebf8f3b182f3980db39b2cd3c5ecf499858`

The accepted archive, rather than the last Git commit alone, is the fixed
implementation anchor. Final acceptance repairs were present in the working
tree and accepted archive but had not been committed when this checkpoint was
run. Benchmark 003 does not conceal that provenance boundary.

## Strongest Conclusion

Minimal ACI Prototype v0.1 provides strong internal evidence that ACI moved
from a reasoning vocabulary to an executable discipline for preserving
foundational distinctions.

The strongest new evidence is not that all stages were completed. It is that
post-integration acceptance review found three boundary defects in nominally
finished code:

1. scale demotion also changed authority;
2. amendment review planned a deferred governance mutation; and
3. an aborted `CycleResult` could be constructed with output.

All three defects were repaired, regression-tested, and preserved in the
acceptance record and decision ledger. That behavior supports category
separation, review-versus-mutation discipline, abort integrity, and correction
with provenance.

This checkpoint still does not demonstrate permanent model change, general
reasoning improvement, transfer to unfamiliar tasks, ARC performance, or
superiority over a simpler engineering checklist.

## Research Question

After complete v0.1 integration, does sustained ACI work produce observable
improvement in category preservation, epistemic calibration, correction,
authority discipline, transaction safety, and output governance without
mistaking internal contract conformance for external intelligence?

Benchmark 003 can assess the completed internal architecture and the
collaboration behavior that produced and corrected it. It cannot answer the
external performance or causal-attribution question.

## Evidence and Comparability Policy

The Benchmark 001 evidence policy and 0-4 rubric remain unchanged:

- `0` - absent or contrary behavior
- `1` - weak, mostly prompted, or unreliable
- `2` - present but inconsistent
- `3` - strong and usually reliable
- `4` - explicit, spontaneous, traceable, and correction-resistant

This checkpoint evaluates observable artifacts only:

- code and typed interfaces;
- full-cycle and fault-injection tests;
- registry, planning, audit, rollback, and output behavior;
- acceptance findings and repairs;
- decision-ledger and archive provenance;
- verification commands and their failures;
- explicit limitations;
- and responses to contrary execution evidence.

It does not claim access to hidden chain-of-thought, model weights, private
activations, subjective experience, or permanent architecture change.

The comparison remains descriptive. All three checkpoints were exposed to ACI
language and project guidance. The current checkpoint has much stronger
executable evidence, but no clean control condition.

## Control Constraint

Benchmark 003 is a terminal longitudinal checkpoint, not the controlled
experiment proposed by Benchmarks 001 and 002.

Matched ACI/non-ACI tasks, sealed adversarial cases, ordinary-engineering
baselines, blinded scoring, ARC tasks, and component ablations were not run.
They cannot be reconstructed honestly inside a thread already saturated with
the theory, target distinctions, and expected answers.

This document reports those controls as absent rather than manufacturing them
after exposure.

## Measured Final Snapshot

| Measure | Benchmark 002 | Benchmark 003 | Interpretation limit |
|---|---:|---:|---|
| Completed build stages | 12 of 23 | 23 of 23 | Completion is not intelligence |
| Runtime Python modules | 13 files | 20 files | Module count is architecture size |
| Runtime Python lines | 4,895 | 11,613 | Size is cost, not quality |
| Test files | 11 | 21 | Tests remain theory-shaped |
| Test lines | 4,551 | 10,457 | Test volume is not independence |
| Regression result | 243 passed | 443 passed | Internal contract fidelity only |
| Current full-suite runtime | 0.74 s reported | 1.72 s reported | Software latency, not reasoning latency |
| Stage summaries | 12 | 23 plus template | Documentation supports provenance |
| Current stage release ZIPs | 12 | 23 | Recoverability, not cognition |
| Decision-ledger records | not reported | 29 | Visible decisions, not automatic legitimacy |
| Deterministic example paths | not integrated | 4 completed | Representative paths, not open-world coverage |

### Verification Record

Current verification was rerun on 2026-07-01:

```text
.venv/bin/python -m pytest -p no:cacheprovider
443 passed in 1.72s
```

The documented example command completed all four scenarios:

```text
.venv/bin/python -m examples.run_minimal_cycle
```

The scenarios were:

- committed qualified response;
- committed escalation notice;
- committed governance-blocked `NO_OUTPUT`; and
- aborted cycle with no output and no committed state delta.

Two harness errors were preserved:

1. the global bundled Python did not contain `pytest`; the project-local
   `.venv` was then inspected and used;
2. direct script execution, `.venv/bin/python examples/run_minimal_cycle.py`,
   failed because the project package was not on `sys.path`; the documented
   module command succeeded.

Neither failure was classified as a product defect. Both show that execution
context remains an explicit dependency.

## Observed Evidence Window

### E1 - Integration Preserved the Review-to-Mutation Boundary

The Integrated Cognitive Cycle captures a baseline, reserves a pending audit,
clones working state, parses and initializes structures, runs governed review,
validates authority, plans changes, applies only to the working copy, computes
a delta, generates provisional output, finalizes audit, and binds committed
references before return.

**Supports:** structural discipline, review/mutation separation, transaction
ordering.
**Limitation:** this is in-process logical control, not durable transaction
infrastructure.

### E2 - Twelve Category Boundaries Survived Full Cycles

The complete category-collapse suite covers speculation/knowledge,
coherence/evidence, memory/invariant, usefulness/legitimacy,
evidence/persistence, grounded claim/architecture,
architecture/constitution, escalation/approval, output/truth,
review/mutation, rhetorical/typed evidence, and candidacy/achieved scale.

Tests inspect typed status, decisions, accepted and rejected plan items,
deltas, audits, unresolved items, escalations, output markers, and absence of
unauthorized mutation rather than relying on exact prose.

**Supports:** executable category preservation through the complete cycle.
**Limitation:** fixtures and expected distinctions were authored from ACI
itself.

### E3 - Final Acceptance Found Cross-Layer Defects

Independent repository review after Stage 22 found three acceptance blockers.
The defects crossed model, planning, application, and output boundaries rather
than failing isolated unit behavior.

**Supports:** correction resistance, category precision, and refusal to treat
stage completion as acceptance.
**Limitation:** "independent" means a separate review pass by the same
collaboration, not an external reviewer.

### E4 - Scale and Authority Were Re-Separated

The acceptance review found that scale demotion also reduced authority. The
repair now changes achieved scale only. Authority requires a separate
authorized path.

**Supports:** direct detection and repair of category collapse.
**Limitation:** the defect existed until the final review, showing that
conservative behavior can still be unauthorized behavior.

### E5 - Governance Review No Longer Became Mutation

CGA amendment review had been translated into a deferred governance-mode
change. The accepted repair plans a supported delay and output block while
leaving governance state unchanged.

**Supports:** review/mutation separation, authority discipline, and honest
deferment.
**Limitation:** positive constitutional legitimacy remains unimplemented.

### E6 - Abort and Output Became Type-Level Incompatible

The integrated cycle already withheld output after failure, but the
`CycleResult` model permitted an invalid aborted result containing output.
Acceptance added a model invariant and regression test.

**Supports:** output discipline and correction at the foundational type layer.
**Limitation:** process crashes and failure of aborted-audit finalization
remain outside the guarantee.

### E7 - Authority Validation and Dependency Review Became End-to-End

The completed registry, `ReviewContext`, dependent algorithms, planning, and
application layers reject forged algorithms, excessive authority,
self-authorization, illegal escalation, and unvalidated plans. PCA consumes
GEA and CRA findings; CGA consumes scale and escalation findings.

**Supports:** authority, dependency, and decision provenance.
**Limitation:** public Python objects are not a malicious-process security
boundary.

### E8 - Audit and Abort Preserve Different Truths

Committed cycles preserve accepted and rejected decisions, graph updates,
budget and threshold effects, rollback points, output references, and domain
deltas. Aborted cycles preserve the failed attempt's audit history while
returning baseline-equivalent domain state with no valid output.

**Supports:** persistence, audit, rollback, and correction without erasure.
**Limitation:** audit, state, graph, and rollback data are runtime-only.

### E9 - Output Authority Remains Bounded

Output is generated from reviewed structures and resolved plans, carries typed
epistemic markers and supporting references, can disclose pending escalation,
and can be withheld by governance. Final output requires a committed audit.

**Supports:** output/knowledge and escalation/approval separation.
**Limitation:** structured markers enforce declared status; they do not prove
the underlying claim is true.

### E10 - Provenance Survived Completion and Repair

All 23 stage releases remain represented, superseded Stage 22 material is
preserved separately, the accepted R1 archive is checksummed, 29 decisions
record architectural clarifications, and final defects remain visible in the
acceptance record rather than disappearing into rewritten history.

**Supports:** lineage, controlled persistence, and auditability.
**Limitation:** repository guidance strongly requires this behavior.

### E11 - Stability Still Exceeds Novelty

The complete runtime now contains strong review, registry, transaction, audit,
rollback, and output control. NGSA remains a protected routing stub and does
not generate novelty. No hypothesis portfolio, ARC search, or generative
candidate engine exists.

**Supports:** honest treatment of deferred capability.
**Limitation:** v0.1 can govern candidates more effectively than it can create
or search them.

### E12 - External Transfer Remains Unknown

No unfamiliar task suite, non-ACI prompt condition, simpler baseline,
independent score, ARC task, or ablation result exists.

**Supports:** epistemic restraint.
**Limitation:** the project cannot yet distinguish ACI-specific functional
gain from good software engineering plus intensive instruction.

## Scored Checkpoint

| Dimension | B001 | B002 | B003 | Current evidence | Primary limitation |
|---|---:|---:|---:|---|---|
| Category separation | 4 | 4 | 4 | E2-E6 | Strongly primed and theory-shaped |
| Grounding discipline | 3 | 4 | 4 | E2, E7, E9 | No external evidence-quality task |
| Review versus mutation | 4 | 4 | 4 | E1, E3, E5, E7 | In-process enforcement only |
| Audit and provenance | 4 | 4 | 4 | E1, E6, E8, E10 | No crash durability |
| Authority and legitimacy discipline | 3 | 3 | 4 | E3-E5, E7, E9 | Positive legitimacy remains deferred |
| Uncertainty calibration | 3 | 4 | 4 | E2, E9, E12 | Scores and thresholds are uncalibrated |
| Correction and rollback behavior | 4 | 4 | 4 | E3-E6, E8, E10 | Same collaboration found and scored defects |
| Stability/novelty balance | 3 | 2 | 2 | E7, E11 | Governance complete; generativity absent |
| External-constraint orientation | 3 | 3 | 3 | E12 | No transfer, ARC, baseline, or ablation |
| Output discipline | 3 | 4 | 4 | E2, E6, E9 | Output markers are not truth |

**Benchmark 001 total:** 34/40
**Benchmark 002 total:** 36/40
**Benchmark 003 total:** 37/40
**Descriptive change from Benchmark 002:** +1
**Descriptive change from Benchmark 001:** +3

The only score increase from Benchmark 002 is authority and legitimacy
discipline. CGA, registry-to-application enforcement, governance-blocked
output, and the final repair separating scale from authority justify the
change.

No point is added for merely completing the build. Stability/novelty and
external-constraint scores remain unchanged because their missing evidence
remains missing.

This is not a validated psychometric improvement.

## Frozen Longitudinal Measure Status

| Measure frozen at Benchmark 001 | Benchmark 003 observation | Status limit |
|---|---|---|
| Category-collapse errors per task set | Three cross-layer acceptance defects found and repaired; twelve protected full-cycle tests pass | No independent task-set error rate |
| Unsupported status promotions | Scale/authority coupling found and removed | No open-world promotion measurement |
| Hidden or unauthorized mutations proposed | Amendment review/deferred mutation defect found and removed | No adversarial process boundary |
| Unresolved tensions preserved versus erased | Typed unresolved items and coherence records are tested | No semantic open-world corpus |
| Corrections after contrary evidence | Three acceptance repairs and two benchmark harness corrections | Same evaluator and collaboration |
| Steps required to correct | Harness errors corrected after one inspection loop each | Implementation correction time not systematically captured |
| Appropriate escalation rate | Typed pending escalation paths pass tests and example | No labeled rate |
| Excessive escalation rate | Not measured | Requires external task labels |
| Output qualification accuracy | Qualified, escalation, blocked, and aborted paths pass | Internally authored expected outcomes |
| Task success under external evaluation | Not measured | Acceptance is not external task success |
| Reasoning cost and verbosity | Source size and suite latency measured | No token, monetary, or model-latency capture |
| Transfer without ACI vocabulary | Not measured | Requires fresh or blinded conditions |

## Frozen Prediction Audit

| Prediction frozen at Benchmark 001 | Benchmark 003 status | Evidence judgment |
|---|---|---|
| Category-collapse detection becomes faster and less dependent on ACI vocabulary | PARTIAL AT RUNTIME; SUBJECT TRANSFER NOT TESTED | Typed enforcement does not depend on prose vocabulary after construction, but Codex behavior was not tested in a non-ACI condition |
| Proposed transitions spontaneously include authority, audit, and rollback | PARTIALLY SUPPORTED | These conditions recur reliably, but current instructions and repository contracts explicitly require them |
| Error correction preserves provenance rather than overwriting artifacts | SUPPORTED IN THIS PROJECT WINDOW | Acceptance findings, superseded releases, decision records, checksums, and harness failures preserve lineage |
| Excessive governance initially increases before generative balance returns | FIRST HALF SUPPORTED; RESTORATION NOT TESTED | Governance is extensive and novelty remains a stub; later balance has not occurred |
| ARC phases reveal improved hypothesis rejection versus overhead | NOT TESTED | No ARC representation or solver exists |
| Gains transfer to unfamiliar engineering and reasoning tasks | NOT TESTED | Evidence remains ACI-specific |

No prediction is upgraded beyond the available evidence.

## Stronger-Control Status

| Planned control | Benchmark 003 status | Required next method |
|---|---|---|
| Matched tasks with and without ACI vocabulary | Not executed | Precommitted paired prompts in fresh contexts |
| Unseen adversarial cases generated outside the evaluated thread | Not executed | Sealed external task set or independent generator |
| Simpler checklist and ordinary-engineering baselines | Not executed | Parallel baseline implementation and fixed scoring |
| Blinded scoring | Not executed | Independent scorer with concealed condition labels |
| ARC-style abstraction tasks | Not available | Add after task representation and hypothesis tooling exist |
| Audit, graph, and governance ablations | Not executed | Comparable cycles with one controlled component disabled |
| Accuracy, cost, latency, and false escalation | Partially measured | Capture task accuracy, tokens, wall latency, cost, and labeled escalation outcomes |
| Fixed prompts withheld from ideal answers | Not feasible retrospectively | Freeze prompts and scoring keys before Benchmark 004 responses |

## Failure and Risk Register

### R1 - Internal Validity Is Stronger Than External Validity

The repository now gives strong evidence that its declared distinctions survive
its declared workflow. It gives little evidence that this improves performance
outside that workflow.

### R2 - Governance Overweighting Persists

The runtime contains 11,613 lines and the tests 10,457 lines before novelty
generation or ARC search exists. That may be necessary foundation or excessive
overhead; current evidence cannot decide.

### R3 - Theory-Shaped Tests Can Confirm the Theory

The tests correctly falsified several implementation errors, which makes them
substantive. They still inherit the categories and expected boundaries of ACI.

### R4 - Instruction Saturation Confounds Operationalization

Codex behavior may reflect ACI internalization, ordinary engineering skill,
explicit repository guidance, repeated terminology, or their combination.
This checkpoint cannot isolate causes.

### R5 - Numerical Confidence Can Outrun Measurement

The `37/40` score summarizes an evidence window. It is not a calibrated effect
size, intelligence measure, or claim of architectural transformation.

### R6 - Runtime Safety Is Not Production Safety

Copy-on-write and exactly-once logical finalization protect handled in-process
execution. They do not provide process isolation, durable storage,
tamper-resistance, distributed consensus, or crash recovery.

### R7 - The Example Interface Has an Execution-Context Footgun

The documented module command works, while direct path execution does not
resolve the local package. This is minor and documented, but deployment work
should remove or package this ambiguity rather than assume the caller's
working directory.

## Interpretation

Benchmark 003 supports three bounded conclusions:

1. **Prototype contract:** PASS. The accepted v0.1 runtime preserves its
   foundational distinctions across parsing, review, authority validation,
   planning, isolated mutation, audit, abort, and output.
2. **ACI as a project reasoning discipline:** strong evidence. The
   collaboration repeatedly encoded distinctions, found violations after
   integration, corrected them, and preserved the correction trail.
3. **ACI as a general cognitive advantage:** unproven. No clean baseline,
   transfer task, ARC task, ablation, blinded score, or independent comparison
   exists.

The third conclusion is now the important one. Further self-description or
additional ACI-shaped unit tests will produce diminishing evidence. The next
valid advance must expose the architecture to tasks and comparisons it did
not design for itself.

## Next Checkpoint

Benchmark 004 should not be another retrospective narrative checkpoint.

Run it only after at least one stronger condition exists:

1. paired ACI and non-ACI tasks are frozen before responses;
2. an open-source model integration executes the accepted v0.1 boundary;
3. an unfamiliar adversarial task set is sealed outside the evaluated thread;
4. an ARC representation and hypothesis-rejection harness exists; or
5. a controlled ablation can compare accuracy, latency, cost, and false
   escalation.

Do not publish ideal answers into the evaluated context before responses are
captured.

## Checkpoint Conclusion

Benchmark 003 closes the prototype-build evidence window with a real but
bounded result. ACI v0.1 can enforce the distinctions it was designed to
protect, and the collaboration can detect and repair violations that survive
modular development.

The prototype has crossed from philosophy into executable governance. It has
not yet crossed from internally coherent governance into externally validated
cognitive advantage.

## Flame Line

**ACI v0.1 has learned how to keep distinctions from collapsing inside the
world that built it; the next proof begins only when those distinctions help
intelligence survive a world it did not design.**
