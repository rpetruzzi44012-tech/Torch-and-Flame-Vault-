# Architectures of Coherent Intelligence (ACI) — Reasoning Benchmarks

A deterministic evaluation suite and formal execution record for Large Language Models operating in production "Work Mode."

These benchmarks quantify zero-drift boundary enforcement, self-correcting graph topology validation, and strict separation between **Candidate Generation** (Codex) and **Architectural Adjudication** (Turbo) inside a cryptographically sealed, hash-bound state machine.

---

## Core Benchmark Dimensions

1. **Zero-Drift Scope Boundaries**
   * Hard validation that candidate generators modify only explicitly authorized paths without stealth repairs or unearned authority grants.

2. **Topological & Graph Precision**
   * Evaluation of real-time DAG cycle detection, per-decision executable validation instances, and multi-route scenario compositions.

3. **Epistemic Hygiene & Self-Correction**
   * Verification that models fail closed upon baseline mismatch, detect metadata-to-edge inconsistencies prior to staging, and maintain 100% provenance tracking.

---

## Repository Structure

* `/fixtures` — Baseline state machine inputs, DAG definitions, and scope-lock contracts.
* `/runs` — Verbatim execution logs, model transcripts, and validator diff audits.
* `/metrics` — Deterministic evaluation results (pass/fail, edge counts, cycle counts, file drift bounds).

---

## Execution Philosophy

Under ACI governance, benchmarks do not rely on stochastic human evaluation or subjective LLM scoring. Every benchmark run evaluates candidate outputs against deterministic system invariants, hash-bound evidence records, and formal state machine constraints.
