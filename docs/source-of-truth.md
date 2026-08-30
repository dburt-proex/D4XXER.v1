# Portfolio Source-of-Truth Governance

**Owner:** Drew Donald Burt  
**Effective:** July 19, 2026  
**Status:** Active  
**Public canonical URL:** https://drew-burt-portfolio.daxxer-os.chatgpt.site  
**Documentation repository:** https://github.com/dburt-proex/DDBPORTFOLIO.git.io

## Decision

The ChatGPT Sites portfolio is the canonical public-facing experience.

This repository is the canonical portfolio documentation and evidence-routing layer. It preserves the claim registry, maturity boundaries, public-route map, supporting briefs, reciprocal-link contract, and review history.

Each system's own repository remains authoritative for its code, tests, releases, validation artifacts, and implementation status.

The portfolio may summarize technical evidence; it must not outrank or broaden the underlying repository evidence.

## Authority matrix

| Information | Canonical source | Conflict rule |
| --- | --- | --- |
| Public headline, biography, navigation, calls to action, and page copy | ChatGPT Sites | The live Sites version governs public presentation. |
| Assessment and Governance Lab behavior | ChatGPT Sites deployment | The deployed interaction governs visitor behavior. |
| Portfolio claim registry, maturity boundaries, and evidence routing | This repository | Update through versioned Git history or pull request. |
| Project code, tests, releases, and validation status | Canonical project repository | Project evidence overrides portfolio summaries. |
| Résumé facts and direct contact information | Drew Burt | Owner-confirmed information overrides derived copy. |
| Historical public-site implementation | Git history in this repository | History is preserved but is not current public authority. |

## Public route registry

| Public route | Purpose | Evidence authority |
| --- | --- | --- |
| `/` | Positioning and assessment-to-enforcement operating model | This registry plus linked project repositories |
| `/assess` | Directional governance diagnostic | Operator Intelligence methodology and deployed assessment logic |
| `/agentic-readiness-audit` | Bounded Agentic Readiness Audit for one AI-enabled workflow | Owner-approved commercial scope and deployed Sites route |
| `/results` | Deterministic score, confidence, gaps, and next actions | Deployed scoring logic and documented assessment boundary |
| `/lab` | Simulated ALLOW, REVIEW, and HALT control paths | CASA and DiffWall repositories |
| `/systems` | Evidence index for public system claims | Canonical project repositories plus `docs/systems-evidence-index.md` |
| `/work-log` | Review-gated directives, receipts, decisions, and field notes | Published GitHub work-log issues and deployed Sites rendering |
| `/work-with-me` | Role, engagement, and partnership paths | Drew Burt's owner-confirmed availability and contact details |

## Systems evidence contract

The `/systems` page is an evidence index, not a marketing gallery.

Every featured system entry must expose five things:

1. **Control function** — the specific problem the system governs or evaluates.
2. **Safe public claim** — wording supported by current repository evidence.
3. **Proof surface** — code, tests, release record, case study, demo path, or other inspectable artifact.
4. **Maturity boundary** — what the evidence does not justify claiming yet.
5. **Canonical repository** — the source that governs technical status.

Every canonical project README should reciprocally link back to the portfolio Systems page or a system-specific portfolio proof page. This creates a two-way evidence path:

```text
Portfolio claim
  -> canonical repository
  -> implementation / test / release evidence
  -> portfolio evidence context
```

If the public portfolio hostname changes, update this registry and the portfolio documentation before propagating new direct links. Do not maintain competing canonical portfolio domains.

## Project evidence registry

| System | Portfolio role | Canonical evidence | Public proof route |
| --- | --- | --- | --- |
| Operator Intelligence | Assess and prioritize readiness and operating gaps | https://github.com/dburt-proex/operator-intelligence | `/systems`, `/assess`, `/agentic-readiness-audit` |
| CASA | Govern runtime execution before external action | https://github.com/dburt-proex/casa | `/systems`, `/lab` |
| DiffWall | Govern AI-authored code changes and structured actions | https://github.com/dburt-proex/diffwall | `/systems`, `/lab` |
| Governance Harness Toolkit | Convert governance requirements into testable contracts and evaluators | https://github.com/dburt-proex/governance-harness-toolkit | `/systems` |
| PromptBP | Govern instruction structure, workflow composition, and output validation | https://github.com/dburt-proex/PromptBP | `/systems` |
| Verified Intelligence Layer | Verify, score, and route incoming signals before downstream work | https://github.com/dburt-proex/VIL_deterministic_scoring_engine | `/systems` |
| Shared Decision Ledger | Preserve decision evidence and replay context across governed workflows | Evidence implementations in CASA, Operator Intelligence, and related repositories | `/systems` |

The detailed claim-and-proof matrix is maintained in [`systems-evidence-index.md`](systems-evidence-index.md).

## Publishing workflow

### Technical or maturity change

1. Verify the new state in the system's canonical repository.
2. Update the evidence registry or supporting brief in this repository.
3. Review the wording for evidence strength, maturity, and unsupported inference.
4. Update the corresponding public Sites content.
5. Confirm the public claim links to the correct repository or proof artifact.
6. Confirm the project README links back to the portfolio evidence route.

### Public copy or experience change

1. Update and validate the Sites build.
2. Check whether the change affects a documented claim, evidence link, or maturity boundary.
3. If it does, update this repository in the same work cycle.
4. Confirm reciprocal README links still resolve correctly.
5. Record the final public URL and relevant GitHub change in the change log.

### Work Log entry

1. Submit the structured GitHub Work Log issue form.
2. Verify completed-work claims, evidence links, dates, and project attribution.
3. Remove secrets, personal data, private client information, and unsupported claims.
4. Keep the GitHub issue open while the entry remains a draft.
5. Close the issue only after review.
6. Preserve the GitHub issue as the versioned source record for the public entry.

### Conflict resolution

1. Project-level technical evidence wins for implementation status.
2. GitHub portfolio documentation wins for claim boundaries and evidence mapping.
3. ChatGPT Sites wins for current public wording and visitor behavior.
4. Owner-confirmed personal information wins over derived summaries.
5. When sources disagree, narrow the public claim until the discrepancy is resolved.

## Synchronization policy

No automatic two-way content synchronization is authorized.

Automation may be used for read-only parity checks, broken-link detection, claim-drift detection, change reminders, and scheduled draft creation. It must not silently publish broader claims than the project evidence supports.

## GitHub Pages role

The GitHub Pages root is a bridge to the canonical Sites portfolio. It should not operate as a second competing portfolio homepage.

Existing technical briefs and case studies remain supporting evidence:

- [AI Governance for Developer Tooling](../governance-developer-tooling.html)
- [Source brief and maturity appendix](ai-governance-developer-tooling.md)
- [Agentic SDLC governance case study](../agentic-sdlc-governance.html)
- [DiffWall v0.2.0 release evidence](../diffwall-v0.2.0-release.html)

## Change log

| Date | Change | GitHub record | Public deployment |
| --- | --- | --- | --- |
| 2026-08-30 | Tightened the Systems evidence contract, corrected CASA canonical ownership, and standardized the current portfolio hostname. | Current repository history | https://drew-burt-portfolio.daxxer-os.chatgpt.site/systems |
| 2026-08-29 | Updated the current canonical public portfolio target to `daxxer-os.chatgpt.site`. | Commit `577c94712fa9424828b5c063eb86028d2a86e5d3` | https://drew-burt-portfolio.daxxer-os.chatgpt.site |
| 2026-08-12 | Published the Agentic Readiness Audit founding-pilot route. | PR #17 | Agentic Readiness Audit route |
| 2026-07-19 | Established Sites as public authority and GitHub as versioned documentation authority. | PR #9 | ChatGPT Sites portfolio |
