# Drew Burt Portfolio

**Canonical public portfolio:** [drew-burt-portfolio.daxxer-os.chatgpt.site](https://drew-burt-portfolio.daxxer-os.chatgpt.site)

This repository is the versioned documentation and evidence-routing layer for Drew Burt's public portfolio. It records claims, proof links, maturity boundaries, public routes, and publishing rules behind the visitor-facing experience.

## Source-of-truth model

| Scope | Canonical authority | Purpose |
| --- | --- | --- |
| Public positioning, navigation, assessment, lab, systems, and contact paths | [ChatGPT Sites portfolio](https://drew-burt-portfolio.daxxer-os.chatgpt.site) | Current visitor-facing experience |
| Portfolio evidence map, maturity boundaries, reciprocal links, and change history | This repository | Versioned claim and proof governance |
| Code, tests, releases, and project-specific status | Each project's canonical repository | Technical implementation evidence |

The public site and GitHub evidence layer are complementary, not competing portfolios.

Read the complete governance record: [docs/source-of-truth.md](docs/source-of-truth.md).

## Public route map

- [Home](https://drew-burt-portfolio.daxxer-os.chatgpt.site/) — positioning and assessment-to-enforcement model
- [Assessment](https://drew-burt-portfolio.daxxer-os.chatgpt.site/assess) — governance diagnostic
- [Agentic Readiness Audit](https://drew-burt-portfolio.daxxer-os.chatgpt.site/agentic-readiness-audit) — bounded assessment for one AI-enabled workflow
- [Governance Lab](https://drew-burt-portfolio.daxxer-os.chatgpt.site/lab) — simulated execution-control scenarios
- [Systems](https://drew-burt-portfolio.daxxer-os.chatgpt.site/systems) — claim-to-proof index for public systems
- [Work Log](https://drew-burt-portfolio.daxxer-os.chatgpt.site/work-log) — read-only, owner-published execution receipts, decisions, and field evidence
- [Work with Drew](https://drew-burt-portfolio.daxxer-os.chatgpt.site/work-with-me) — roles, scoped work, and partnerships

## Systems evidence index

The Systems page follows a reciprocal evidence contract:

```text
Portfolio claim
  -> canonical repository
  -> implementation / tests / release evidence
  -> portfolio evidence context
```

The canonical claim-and-proof matrix is maintained in [docs/systems-evidence-index.md](docs/systems-evidence-index.md).

| System | Control function | Canonical evidence |
| --- | --- | --- |
| [Operator Intelligence](https://github.com/dburt-proex/operator-intelligence) | Assessment, scoring, findings, implementation routing | Repository methodology, scoring, templates, playbooks, examples |
| [CASA](https://github.com/dburt-proex/casa) | Pre-execution governance and runtime action gating | Governance API, deterministic gate engine, audit ledger, replay, tests |
| [DiffWall](https://github.com/dburt-proex/diffwall) | Change-time enforcement for AI-generated code and structured actions | v0.2.0 release, live-controlled PR validation, policy packs, tests |
| [Governance Harness Toolkit](https://github.com/dburt-proex/governance-harness-toolkit) | Machine-evaluable governance contracts and regression controls | Policies, schemas, deterministic evaluator, adversarial fixtures |
| [PromptBP](https://github.com/dburt-proex/PromptBP) | Instruction and capability governance | Schemas, capability registry, workflow composer, scoring and loop controls |
| [Verified Intelligence Layer](https://github.com/dburt-proex/VIL_deterministic_scoring_engine) | Evidence-capped signal scoring and routing | Scoring engine, API, dashboard, routes, audit records |

## Supporting evidence

- [Systems evidence index](docs/systems-evidence-index.md) — canonical public claim, proof, and maturity matrix
- [Agentic Readiness Audit](https://drew-burt-portfolio.daxxer-os.chatgpt.site/agentic-readiness-audit) — scope, delivery package, and assessment boundary
- [AI Governance for Developer Tooling](docs/ai-governance-developer-tooling.md) — source brief and maturity appendix
- [Rendered capability brief](governance-developer-tooling.html) — browser-readable evidence map
- [Agentic SDLC governance case study](agentic-sdlc-governance.html) — developer-control evidence
- [DiffWall v0.2.0 release evidence case study](diffwall-v0.2.0-release.html) — governed release, validation, maturity, and residual-risk evidence

## Publishing rule

1. Verify a technical claim in the relevant project repository.
2. Update the evidence index when the claim, proof path, or maturity boundary changes.
3. Update the public Sites wording only within the verified evidence boundary.
4. Confirm the public Systems entry links to the canonical repository.
5. Confirm the featured repository README links back to the portfolio Systems or dedicated proof route.
6. Record the change through Git history or a pull request.

There is no automatic two-way publishing. That is intentional: evidence must be reviewed before it becomes a public claim.

## Work Log evidence policy

The public Work Log is a **read-only evidence surface**. It exists to show reviewed execution receipts, decisions, build evidence, and field notes authored or approved by Drew Burt.

Visitor submission is not part of the portfolio workflow. Public pages and repository documentation must not present a Work Log intake form or invite visitors to create entries. Draft authoring and review occur through an owner-controlled workflow; only reviewed records may enter the public evidence feed.

Existing published records remain evidence. Publication or withdrawal remains an owner-controlled action.

## Contact

- Email: [drewburt4@gmail.com](mailto:drewburt4@gmail.com)
- LinkedIn: [burtdrew0047](https://www.linkedin.com/in/burtdrew0047)
- GitHub: [dburt-proex](https://github.com/dburt-proex)

## Evidence boundary

Repository documentation and linked validation artifacts govern technical status. No project should be interpreted as enterprise production-ready, independently certified, broadly deployed, or endorsed by a third party unless separate evidence explicitly establishes that claim.
