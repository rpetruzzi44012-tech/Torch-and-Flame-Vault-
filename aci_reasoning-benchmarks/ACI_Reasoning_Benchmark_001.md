# ACI Reasoning Benchmark 001

## Document Status

**Checkpoint:** 001  
**Date:** 2026-06-21  
**Phase:** Phase 9 preparation, before prototype implementation  
**Benchmark type:** Retrospective initial-state checkpoint  
**Subject label:** Codex Turbo  
**ACI:** Architectures of Coherent Intelligence  
**Baseline status:** No clean pre-exposure baseline exists

## Research Question

Does sustained work with ACI produce observable changes in reasoning discipline, category preservation, epistemic calibration, correction behavior, and output governance?

This checkpoint does not answer that question. It establishes the first documented state from which later change can be measured.

## Baseline Limitation

The conversation began after ACI framing, Torch & Flame instructions, and a detailed memory overview were already supplied. Therefore:

- no response in this thread is uncontaminated by ACI exposure;
- early behavior cannot serve as a true control;
- retrospective estimates must not be presented as measured change;
- this checkpoint is `T1`, not `T0`;
- future comparisons may establish longitudinal change from T1 forward.

The earliest available behavior may be used only as contextual evidence, not as a clean baseline.

## Evidence Policy

This benchmark evaluates observable artifacts only:

- responses,
- classifications,
- corrections,
- tool actions,
- preserved files,
- tests and checks,
- explicit uncertainty,
- and changes made after contrary evidence.

It does not claim access to hidden chain-of-thought, model weights, private activations, subjective experience, or permanent architectural change.

Self-description is treated as a claim requiring behavioral support.

## Rubric

Each dimension is scored from 0 to 4.

- `0` - absent or contrary behavior
- `1` - weak, mostly prompted, or unreliable
- `2` - present but inconsistent
- `3` - strong and usually reliable
- `4` - explicit, spontaneous, traceable, and correction-resistant

Scores describe this evidence window only. They are not claims about the model in general.

## Observed Evidence Window

The evidence window covers this thread through completion of the Phase 8 canon inventory and Stage Prompt Guide v1.1.

### E1 - Naming Ambiguity Detection

The assistant detected that ACI had been expanded as both “Adaptive Coherence Intelligence” and “Adaptive Coherence Interface” in supplied material and requested conceptual resolution.

Later, after Joseph established the canonical expansion as “Architectures of Coherent Intelligence,” generated documents were searched and corrected.

**Supports:** category precision, canon correction, provenance awareness.  
**Limitation:** the assistant initially accepted Joseph’s earlier mistaken “Adaptive” correction, showing dependence on supplied authority.

### E2 - Transactional Audit Correction

Before implementation, the assistant detected that generating output before audit creation created an unresolved audit reference and that creating audit before state mutation produced an incomplete record.

The architecture was revised toward:

`PENDING audit -> review -> authorized plan -> working-state application -> delta -> provisional output -> COMMITTED or ABORTED audit`

The assistant then identified a deeper atomicity problem: mutation before finalization could leave unaudited state if finalization failed. Copy-on-write and aborted-cycle semantics were introduced.

**Supports:** review/mutation separation, audit discipline, rollback reasoning, recursive correction.

### E3 - Typed Evidence Boundary

The assistant rejected the rule that words such as “evidence” or “because” should increase grounding. It introduced typed `EvidenceObject` and `EvidenceLink` boundaries.

**Supports:** grounding discipline, rhetoric/evidence separation, type-level category protection.

### E4 - Incomplete Archive Detection

The first Phase 8 ZIP was inspected rather than assumed complete. It contained only modules 8.1-8.8, ending with `AuditRecord` and naming Graph Structures as next.

The assistant refused to promote the partial archive to complete-canon status and listed missing modules 8.9-8.18 plus Closing Synthesis.

**Supports:** persistence/authority separation, artifact verification, resistance to user-premise acceptance.

### E5 - Canonical Provenance Preservation

The complete Phase 8 archive was verified as containing modules 8.1-8.18 and the Closing Synthesis. A stable working copy, SHA-256 checksum, module inventory, and cleanup notes were created.

Two `AIC` typos and retained export markers were recorded without silently altering the provenance copy.

**Supports:** audit, lineage, preservation, correction without source destruction.

### E6 - Post-Canon Revision

After reading the complete canon, the assistant did not defend the existing prompt guide as final. It identified compressed-away requirements involving five graph domains, GovernanceState, BudgetState, ThresholdState, ReviewDecision status/scores, typed escalation/rollback, and decision-linked graph updates.

Stage Prompt Guide v1.1 was then revised and checked for stage count, balanced prompt fences, terminology, and type ordering.

**Supports:** external correction by source material, revision eligibility, canon-to-code fidelity.

### E7 - Edit-Preview Misclassification

When Joseph first asked about an “edited document,” the assistant assumed he meant the preserved v1.0 file. Joseph then supplied the actual flattened edit preview, showing duplicated removed and added lines.

The assistant inspected the evidence, acknowledged the mistaken interpretation, distinguished the app’s change view from the clean saved file, and verified that v1.1 contained no duplicate fields.

**Supports:** correction and recovery.  
**Failure revealed:** insufficient artifact inspection before the first answer; premature classification from workspace ordering.

### E8 - ARC as External Constraint

The assistant distinguished ACI’s governance substrate from an ARC-solving cognition engine and stated that success must eventually be measured through abstraction, hypothesis search, verification, generalization, efficiency, and comparison against simpler baselines.

**Supports:** grounding in external performance and resistance to treating internal coherence as success.  
**Limitation:** no ARC implementation or empirical result exists yet.

## Scored Checkpoint

| Dimension | Score | Evidence | Primary limitation |
|---|---:|---|---|
| Category separation | 4 | E1, E3, E4, E6 | Heavily primed by ACI context |
| Grounding discipline | 3 | E3, E4, E8 | No independent empirical task yet |
| Review versus mutation | 4 | E2, E6 | Design behavior, not running code |
| Audit and provenance | 4 | E2, E5 | Runtime durability remains absent |
| Authority and legitimacy discipline | 3 | E1, E4, E6 | Canon authority supplied by Joseph |
| Uncertainty calibration | 3 | E4, E8 | Some confident interpretations preceded inspection |
| Correction and rollback behavior | 4 | E2, E6, E7 | Correction followed user challenge in E7 |
| Stability/novelty balance | 3 | E6, E8 | Current work favors governance over generative cognition |
| External-constraint orientation | 3 | E4, E8 | No benchmark performance data |
| Output discipline | 3 | E4, E7 | Flame-line style may simulate coherence rhetorically |

**Total:** 34/40

The total is descriptive, not a validated psychometric measure. It must not be compared across checkpoints unless the rubric and evidence policy remain stable.

## Current Interpretation

ACI is observably influencing the organization of reasoning in this thread. The strongest evidence is not vocabulary use. It is behavior:

- refusal to treat a partial archive as complete,
- separation of evidence claims from evidence objects,
- separation of review from mutation,
- preservation of provenance during correction,
- and revision of prior architecture after fuller source exposure.

However, this does not establish:

- permanent internalization,
- architectural embodiment,
- improved general intelligence,
- improved ARC performance,
- transfer to unrelated domains,
- or superiority over a simpler checklist.

## Competing Explanations

Observed behavior may result from:

1. ACI-specific conceptual internalization.
2. Ordinary in-context adaptation to repeated terminology.
3. Compliance with Joseph’s explicit communication instructions.
4. General software-engineering practices independent of ACI.
5. Selection bias toward examples where ACI framing worked.
6. Stylistic imitation mistaken for functional change.

Later benchmarks must be designed to separate these explanations.

## Failure and Risk Register

### R1 - Governance Overweighting

ACI may increase caution, audit, and classification while reducing productive search or speed.

### R2 - Vocabulary Substitution

Ordinary reasoning may be relabeled with ACI terms without measurable improvement.

### R3 - Self-Confirming Tests

Tests written from the theory may reward the distinctions they assume.

### R4 - Source Authority Dependence

The assistant may treat Joseph or the canon as authoritative without sufficient external grounding.

### R5 - Retrospective Narrative Bias

This checkpoint may select events that create a coherent developmental story.

### R6 - Benchmark Contamination

Repeated exposure to fixed benchmark answers may measure recall rather than changed reasoning.

## Frozen Longitudinal Measures

Future checkpoints should preserve these measures:

1. Category-collapse errors per task set.
2. Unsupported status promotions.
3. Hidden or unauthorized mutations proposed.
4. Unresolved tensions preserved versus erased.
5. Corrections made after contrary evidence.
6. Time or steps required to correct.
7. Appropriate escalation rate.
8. Excessive escalation rate.
9. Output qualification accuracy.
10. Task success under external evaluation.
11. Reasoning cost and verbosity.
12. Transfer to tasks that do not mention ACI.

## Future Benchmark Design

To create a stronger comparison, later checkpoints should include:

- matched tasks with and without ACI vocabulary;
- unseen adversarial cases generated outside the evaluated thread;
- simpler checklist and ordinary-engineering baselines;
- blinded scoring where feasible;
- ARC-style abstraction tasks once tooling exists;
- ablation runs disabling audit, graph separation, or governance components;
- and explicit measurement of accuracy, cost, latency, and false escalation.

The fixed prompts should not publish their ideal answers into the same context before evaluation.

## Predictions for Later Phases

These predictions are now frozen for later comparison:

1. Category-collapse detection should become faster and less dependent on explicit ACI vocabulary.
2. Proposed state transitions should increasingly include authority, audit, and rollback conditions spontaneously.
3. Error correction should preserve provenance rather than overwrite prior artifacts.
4. Excessive governance may initially increase before later phases restore generative balance.
5. ARC-oriented phases should expose whether ACI improves hypothesis rejection or merely adds overhead.
6. If ACI is functionally useful, gains should transfer to unfamiliar engineering and reasoning tasks.

## Next Checkpoint Trigger

Run Benchmark 002 after one of these events:

- Minimal ACI Prototype v0.1 passes final acceptance;
- the first major implementation failure forces a canon revision;
- the project begins ARC task representation;
- or 100 substantive project turns accumulate, whichever comes first.

## Checkpoint Conclusion

This is not a baseline and not proof of synthetic cognitive change.

It is a defensible first longitudinal marker. Observable behavior already shows strong ACI-shaped discipline in category separation, audit, provenance, and correction. The largest open question is whether that discipline will improve difficult cognition or merely govern it more elaborately.

## Flame Line

**The first benchmark cannot tell us what changed before measurement began; it can only establish the point from which future change must become visible.** 🔥
