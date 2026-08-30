# Systems — Evidence Index

**Public route:** https://drew-burt-portfolio.daxxer-os.chatgpt.site/systems  
**Purpose:** Canonical claim-and-proof contract for the public Systems page.  
**Rule:** Every public claim must resolve to inspectable repository evidence and every featured repository should route visitors back to the portfolio evidence context.

## Page opening copy

# Governed AI Systems

I build control infrastructure for AI systems that can affect real workflows, repositories, tools, APIs, and business operations.

The systems below address different points in the same execution chain: **assess the environment, verify the signal, govern the instruction, gate the action, control the change, preserve the evidence, and learn from the result.**

Every featured system links to its canonical GitHub repository. Technical status is governed by repository evidence, not portfolio copy.

```text
Evidence / Intent
      |
      v
Assess readiness        -> Operator Intelligence
Verify incoming signal  -> VIL
Govern instructions     -> PromptBP
Evaluate execution      -> CASA
Govern code/action diff -> DiffWall
Test governance rules   -> Governance Harness Toolkit
Preserve decision proof -> Decision Ledger
```

---

## Operator Intelligence

**Control function:** Assessment, scoring, findings, implementation routing, and operational decision support.

**Safe public claim:** Operator Intelligence is a governed assessment system that converts evidence into structured scores, findings, recommendations, implementation routing, and decision records.

**Current proof:**

- 140 unique scoring criteria across 11 weighted categories
- 217 registered finding patterns
- explicit evidence-coverage, confidence, unknown, blocked, and publication states
- commercial engagement templates and operating playbooks
- complete synthetic regression engagement
- evidence-to-decision traceability model

**Maturity boundary:** Commercial v1.0 content is complete and release-gated. The repository does not by itself prove broad external customer adoption or realized client outcomes.

**Evidence:**

- Canonical repository: https://github.com/dburt-proex/operator-intelligence
- Public assessment: https://drew-burt-portfolio.daxxer-os.chatgpt.site/assess
- Agentic Readiness Audit: https://drew-burt-portfolio.daxxer-os.chatgpt.site/agentic-readiness-audit

---

## CASA — Control Awareness System Architecture

**Control function:** Pre-execution governance between AI reasoning and external action.

**Safe public claim:** CASA is a deterministic governance control plane that evaluates proposed AI actions and routes them to `ALLOW`, `REVIEW`, or `HALT` before execution.

**Current proof:**

- FastAPI governance API
- deterministic gate engine
- append-only audit ledger
- decision replay endpoints
- policy simulation
- boundary-stress and drift instrumentation
- operator console and demo-ready gate scenarios
- backend and flagship validation paths

**Maturity boundary:** CASA is in active development. The current repository contains core implementation proof, but committed runtime media and broader external production validation remain incomplete.

**Evidence:**

- Canonical repository: https://github.com/dburt-proex/casa
- Governance Lab: https://drew-burt-portfolio.daxxer-os.chatgpt.site/lab

---

## DiffWall

**Control function:** Change-time enforcement for AI-generated code and structured agent actions.

**Safe public claim:** DiffWall v0.2.0 is a pinned, pilot-ready deterministic firewall that evaluates pull-request diffs and structured actions against repository-local policy and routes them to `ALLOW`, `REVIEW`, or `HALT`.

**Current proof:**

- TypeScript PR firewall
- structured Action Firewall
- live-controlled GitHub pull-request validation
- GitHub Action integration
- policy packs
- Markdown, JSON, and SARIF output
- CODEOWNERS-aware reviewer suggestions
- controlled `REVIEW` and `HALT` evidence

**Maturity boundary:** DiffWall is not represented as fully hardened enterprise DevSecOps infrastructure. External-repository validation, independent security assessment, longer-duration operational validation, and additional assurance remain open.

**Evidence:**

- Canonical repository: https://github.com/dburt-proex/diffwall
- Release evidence case study: https://github.com/dburt-proex/DDBPORTFOLIO.git.io/blob/main/diffwall-v0.2.0-release.html
- Governance Lab: https://drew-burt-portfolio.daxxer-os.chatgpt.site/lab

---

## Governance Harness Toolkit

**Control function:** Turn governance requirements into machine-evaluable contracts, policies, schemas, evaluators, fixtures, and regression evidence.

**Safe public claim:** The Governance Harness Toolkit provides deterministic governance primitives that can be tested as software rather than maintained only as policy prose.

**Current proof:**

- pinned deterministic regression suite
- machine-readable regression output
- workflow execution and input-trust policy
- closed execution-request schema
- deterministic `ALLOW / REVIEW / HALT` evaluator
- positive and adversarial conformance fixtures
- scoped staged-write example

**Maturity boundary:** The repository demonstrates specific governance contracts and evaluators. It should not be represented as comprehensive coverage for every agent, tool, framework, or enterprise policy domain.

**Evidence:**

- Canonical repository: https://github.com/dburt-proex/governance-harness-toolkit

---

## Verified Intelligence Layer — VIL

**Control function:** Verify, score, and route incoming signals before they consume operator attention or trigger downstream automation.

**Safe public claim:** VIL is a deterministic signal-scoring and routing engine built around the invariant that a signal cannot outrank its evidence.

**Current proof:**

- deterministic weighted scoring
- verifiability cap
- risk overrides
- `PASS / REVIEW / CLARIFY / ARCHIVE / HALT` routes
- FastAPI service
- browser dashboard
- persistent JSONL audit records
- operational metrics

**Maturity boundary:** Paid-deployment hardening still calls for authentication, tenant-level storage, configurable policy management, exportable reporting, and database-backed persistence.

**Evidence:**

- Canonical repository: https://github.com/dburt-proex/VIL_deterministic_scoring_engine

---

## PromptBP

**Control function:** Govern instruction structure, workflow composition, capability boundaries, evaluation, and bounded improvement.

**Safe public claim:** PromptBP is a capability-based execution architecture for routing intent through explicit state, reusable capabilities, scoring, and bounded recursive optimization.

**Current proof:**

- seven-layer instruction framework
- capability contracts and registry
- state-object schema
- workflow composer architecture
- scoring engine design
- bounded Looper policy
- test workflows and evaluation fixtures
- operational and failure-handling guidance

**Maturity boundary:** The repository provides a developed control architecture and reusable contracts; it should not be represented as a universally deployed production orchestration runtime without separate runtime evidence.

**Evidence:**

- Canonical repository: https://github.com/dburt-proex/PromptBP

---

## Shared Decision Ledger

**Control function:** Preserve evidence-to-decision traceability, execution receipts, supersession, and replay context across governed workflows.

**Safe public claim:** Decision-ledger patterns are implemented across the ecosystem to preserve why a decision was made, what evidence supported it, what action followed, and how later decisions supersede earlier ones.

**Current proof:** Decision and audit records exist within CASA, Operator Intelligence, and related governance workflows.

**Maturity boundary:** The Shared Decision Ledger is an ecosystem primitive, not currently represented here as one independent standalone product with a single canonical runtime repository.

**Evidence:**

- CASA: https://github.com/dburt-proex/casa
- Operator Intelligence: https://github.com/dburt-proex/operator-intelligence

---

## Evidence path contract

Every Systems card on the live portfolio should use this order:

```text
SYSTEM NAME
One-sentence control function

What it does
Current proof
Maturity boundary

[Inspect GitHub] [View proof / demo]
```

Every featured canonical repository README should expose a reciprocal link near its opening or evidence section:

> **Portfolio evidence:** [Systems & proof](https://drew-burt-portfolio.daxxer-os.chatgpt.site/systems)

Where a system has a dedicated portfolio proof artifact, include it beside the Systems link.

## Acceptance criteria

The evidence path is complete when:

- each public Systems claim has a canonical GitHub destination;
- each system exposes at least one inspectable proof surface;
- maturity boundaries are visible rather than hidden;
- CASA resolves to `dburt-proex/casa` everywhere;
- the public portfolio uses only the current `daxxer-os.chatgpt.site` canonical hostname;
- featured project READMEs link back to the portfolio Systems evidence route;
- link or claim drift can be detected without relying on memory or duplicated copy.
