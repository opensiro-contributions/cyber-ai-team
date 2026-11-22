# Cyber AI Team — optional independent Observer S3* evidence-to-hold construction (2026-11-22)

## Identity and pins

- Original repository: Hyper-AI-Lab/cyber-ai-team
- Original HEAD: 525401e40f34863cc7f4d3b053d437ce7709912f
- Observed at: 2026-11-22
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/a3fcf7c156ef4d1132680890bc11544681fd30c0/assessments/cy/cyber-ai-team.md
- Accepted assessment blob SHA: 98ea196e4ff3b74d782526e1a76ea9dc8cd2ef0c
- Accepted review ref: 525401e40f34863cc7f4d3b053d437ce7709912f
- Accepted reviewed at: 2026-10-20
- System in focus: The shipped self-hosted Cyber AI Team company operating OS with domain agents, durable work portfolio, executive/Observer, company intelligence, strategy, owner approvals and audit; external providers and the human organization excluded from credited agent control.
- Profile version: 0.2.4
- Assessment procedure version: 0.3.7
- Receipt contract: proposal-gate
- Result: NEEDS_EVIDENCE
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED
- Repository-wide source map: README, docs/architecture/autonomous-company-os.md, LICENSE, CONTRIBUTING, backend agent manager/LLM gateway, work_portfolio, autonomy_cycle, governor, executive Observer, action_policy, operating_model, company intelligence and strategy, API routes/domain controls, schemas and native backend/tests and CI. Read-only source/REST review, not a full-line code audit or live deployment.
- Priority rationale: S1 is already model-driven, S4 carries recurring future-oriented research/strategy, S3 parent domain control must remain authoritative, and S5 ultimate policy is legitimately owner-held. S2 has useful deterministic stabilizers but an autonomous cross-domain negotiated closure would be significantly broader. Existing executive Observer has the strongest immediately reachable S3* seam: read-only registered role, persistent review object, and native objection-to-action hold, yet current executive critique makes deterministic threshold decisions and does not invoke an independent evidence-based agent.
- Accepted VSM vector: S1=A · S2=— · S3=P · S3*=— · S4=A · S5=—
- Target transition: S3*=— -> S3*=C
- P1 dependencies: Verify accepted owner/deployment permissions, independent primary evidence access and provenance, checkpoint/run/action binding, replay/restart semantics, disputed evidence and reviewer failures, parent approval/OPA priority, and a bounded model-visible input/output contract; test with original backend/test_executive_company_os.py and test_supervisor_review.py.
- P2 optional: Deferred cross-domain S2 disturbance arbitration only as an independent future proposal if first-party reciprocal domain decision rights become source-grounded; no S2 implementation is requested by P0.
- Proposed C construction: Optional developer-composable autonomous Observer review at the existing ExecutiveCompanyOSService._run_observer_review seam. The configured read-only model role independently examines primary evidence pinned to run/snapshot/action ids, chooses accept/object/escalate with typed reasons and provenance, records an unforgeable scoped decision, and feeds a high-severity objection through existing observer_blocks and later re-evaluation; missing/stale reviewer in enforce mode cannot silently release work. Parent approval, impact and OPA authority remain binding. The default deterministic path remains available.
- C sufficiency falsifier: Existing source already calls a separate primary-evidence autonomous reviewer with discretionary objections that bind later action and rework at the same authority boundary; or source-supported evidence access is insufficient to make a genuinely independent choice; or source leaves an unsafe bypass/replay path; or owner-controlled baseline is altered without opt-in.
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Model stub with independent contradictory company evidence and reproducible snapshots. Verify objection blocks the exact action before side effects, re-run after repaired evidence, unrelated safe actions remain governed, missing/revoked/forged/stale evidence/reviewer fails closed only in opted-in enforce mode, baseline modes remain unchanged, owner permanent gates remain decisive, and evidence/audit survives restart. Compare against shipped deterministic Observer; all tests NOT_RUN.
- Validation state: NOT_RUN
- Proposal falsifier: No separate evidential discretion, no binding return-to-operation, or unsafe default/enforce fall-through.
- S1 disposition: A historical; AgentManager.invoke_agent and role work loops select domain-specific work with LLM and persistent feedback. Existing function, NO_TARGET.
- S2 disposition: — historical; WorkPortfolioService routing, idempotent leases and backlogs stabilize work deterministically but cross-domain reciprocal autonomous negotiation is not proven. DEFER rather than falsely convert to an S2=C claim.
- S3 disposition: P historical; authenticated owner can pause, resume or take over specific domains through persistent DomainControlRevision and the WorkPortfolio loop; preserve parent decision owner. NO_TARGET.
- S3* disposition: — historical; an Observer manifest and deterministic checks persist objection status and gate ExecutiveCompanyOSService actions, but a distinct first-party autonomous independent evidence reviewer is not called in the actual _run_observer_review path. P0 candidate C, no shipped-grade claim.
- S4 disposition: A historical; CompanyIntelligenceService acquisition, strategy, operating model and scheduled learning respond to external evidence; no P0 addition needed. NO_TARGET.
- S5 disposition: — historical; human owner holds company purpose, high-impact and permanent gates, with enforcement by ActionPolicy/approval. No legitimate autonomous ultimate-policy transfer requested. NO_TARGET.

## Rights and authority

[LICENSE](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/LICENSE) is MIT and [CONTRIBUTING.md](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/CONTRIBUTING.md) requests FOSS-first/self-hostable implementation, tests, owner-visible evidence, preserving high-impact gates, and no fabricated success. The matching fork has verified parent and writable main, but no metadata branch before this case; its first case will bootstrap a separate opensiro/meta branch using the current owner-directed issue #58 internal-research mandate. This owner grant is limited to metadata and research; no separate external publication, code execution, owner S5 rights, cross-project PR or original Issue is authorized. Original GitHub Issues REST showed only #1, a source-rights evidence discussion, and zero PRs at review time; these are bounded API readbacks, not permanent absence guarantees.

## Existing work / overlap

Track A (SHIPPED): [backend/src/cyber_team/operations/executive.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/executive.py) creates a read-only Observer agent and invokes _run_observer_review before actions; the method performs threshold, marker and resource checks deterministically, persists ObserverReview and returns unresolved_objections, used by run_executive_cycle and _execute_action observer_blocks. [backend/src/cyber_team/agents/manager.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/agents/manager.py) supports registered LLM agent invocation, not wired to this Observer verdict. [backend/src/cyber_team/operations/action_policy.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/action_policy.py) and [backend/src/cyber_team/operations/work_portfolio.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/work_portfolio.py) preserve owner permissions and durable operations. Original https://github.com/Hyper-AI-Lab/cyber-ai-team/issues/1 concerns externally sourced rights evidence, orthogonal to autonomous executive audit; original PR list returned zero, so no competing PR head/diff exists to compare at this observation. No source-specific maintainer request for this new capability was found; interest NOT_STATED.

Track B (INDEPENDENT PROPOSAL): retain existing ObserverReview and observer_blocks, add an optional configured AgentManager.invoke_agent-based reviewer with narrowly scoped primary read-only evidence, typed alternative decisions, freshness/identity checks and an enforce-mode no-release path. Do not replace action policy, add a generic parallel auditor platform, allow self-certification, or force a reviewer in the default mode.

## Function ownership

The decisive S3* reviewer judgment would be a separate developer-composed autonomous agent with a bounded evidential view; deterministic ExecutiveCompanyOSService enforces the result. If the configured reviewer is absent, the current deterministic checks still run but no extra independent interpretive judgment exists. The distinct owner is neither the action-proposing Chief Operating Agent nor the parent human owner. For authority, any enforce-mode reviewer can only object/hold/escalate within already authorized operation; it cannot authorize a prohibited high-impact action or override owner S3/S5 decisions. Closure returns an objection to action hold, human attention or corrected subsequent cycle.

## Capability priority

P0: optional, source-native S3* independent evidence-based executive review-to-hold/correction constructor. P1: evidence fidelity, scoped read-only access, validator, replay and failure gates, permission and native tests. P2: none for the selected transition; independent S2 idea deferred. Accepted vector unchanged; predicted user benefit and cost NOT_MEASURED.

## Implementation options

Track A simplest: keep deterministic Observer _run_observer_review and have owner inspect policy/benchmark failures; it is the lowest complexity path and may be enough. Alternative B1: add rule-based checks only (does not establish new autonomous S3*). B2 (selected): optional model-owned independent review in existing Observer path with a typed evidenced objection, current action hold, and durable recheck. B3: external reviewer agent connected through API (possible, but needs independently demonstrated safe binding to exact in-flight action and report), compare later. No permanent S5 or generic provider-specific service.

## Parallel contribution-on-top review

- Evaluation object: A developer-composed read-only Observer makes independent evidence-backed choice whether a concrete executive action may advance, and returns its objection to current executable flow and later corrected operations.
- Existing-work overlap: Shipped deterministic Observer risk rules, registered read-only Observer manifest, persisted ObserverReview, executive observer_blocks, ActionPolicy owner gates, and domain agents in one self-hosted product.
- Our on-top contribution: Optional model-driven independent reviewer decision against separate pinned primary evidence with exact action-binding, durable typed objection and fail-closed enforce-mode no-release, using existing Observer/ActionPolicy interfaces rather than creating a second governor.
- Incremental benefit: HYPOTHETICAL reduction of unchecked plausible-but-false executive evidence while retaining human authority; tests and cost NOT_MEASURED, reviewer evidence may fail.
- Decision scope: Proposal-stage GO / NEEDS_EVIDENCE for S3*=— -> S3*=C only; not current Index grade, adopted feature, source-specific maintainer instruction, or authority grant.

## Specification and domain alternatives

A genuine baseline counterexample that shows the existing Observer is already an independent discretionary evidence-based control should be routed separately to Index/Profile/Skills after source testing, not silently regraded here. No new reusable standard or independent domain fork is proposed.

## Cost experiment

NOT_MEASURED. Future matched experiment would compare current deterministic review and optional evidential review for action quality, false-blocks, correction latency, API/tool expense, integration and maintenance burden under the same company-state fixtures.

## Delivery and publication

PLAN_ONLY, GO / NEEDS_EVIDENCE, validation NOT_RUN, DRAFT — NOT PUBLISHED. The four case documents and owner event belong on the verified matching fork opensiro/meta, with both structural/template checks before and after commit. No original or public fork Issue/comment/PR, no product code, no new Index grade, and no external consent inferred. Status is reported via Upstream #58, with the initial reservation released only on committed verification.
