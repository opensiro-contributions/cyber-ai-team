# Cyber AI Team — source-native S3* Observer construction contract

**Canonical storage:** opensiro-contributions/cyber-ai-team, opensiro/meta, .opensiro/issues/cyber-ai-team-s3star-observer-20261122/constructor-sufficiency.md.
**Level 1 / Human decision Issue:** [issue.md](issue.md).
**Canonical decision receipt:** [roadmap.md](roadmap.md) is the unique source of truth for accepted Index states, target, P0/P1/P2, verdict, research, pins and publication status.
**Stage:** PLAN_ONLY, HYPOTHESIS, proposal-stage GO, not implementation; **DRAFT — NOT PUBLISHED**.

## 1. Function-specific construction boundary and methodology checks

**Source and mode boundary:** Original 525401e40f34863cc7f4d3b053d437ce7709912f; the self-hosted product in [backend/src/cyber_team/operations/executive.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/executive.py) with packaged registered Observer, [backend/src/cyber_team/agents/manager.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/agents/manager.py) and recurring [backend/src/cyber_team/operations/autonomy_cycle.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/autonomy_cycle.py). First-party executive outcome review is in scope; third-party ERPNext, LLM/provider, OPA process internals, separate human company management and future unimplemented capabilities are out of scope.

**Target transition:** S3*=— -> S3*=C

**Six-function dependencies (S1/S2/S3/S3*/S4/S5):** Ongoing specialized domains (S1) produce proposals and run outcomes. Deterministic work routing (S2-adjacent) offers action identity and queues. Parent S3 domain active/paused/takeover and budget policy remain authoritative. S3* must be a separate reviewer, not the same proposer/threshold; it may veto only a specific supported executive action. Future-oriented S4 strategy may supply evidence but not transfer S4 authority to reviewer. S5 belongs to the owner; review cannot waive high-impact approval or permanent gates.

**Function witness:** HYPOTHETICAL evidence conflict (e.g. an executive company evidence claim contradicts the current primary ERPNext/company revision). Today _run_observer_review uses deterministic markers, confidence cutoffs, benchmark flags and resources, then stores ObserverReview and passes unresolved severe objection through observer_blocks. Proposed additional decisive owner is a developer-composed separately prompted and evidenced read-only reviewer, with accept/object/escalate typed return bound to run and action. The executor enforces a hold before an action and records later feedback to review and owner.

**Counterfactual owner test:** If the independent model reviewer is absent, current registered Observer metadata and deterministic checks still execute and may block threshold violations; they cannot make a new context-sensitive evidence judgment from distinct primary sources. A tool permission or separate model call without a returned action-binding verdict would also fail C.

**Possible methodological negative control:** Current deterministic fixed-rule Observer, even with a manifest named Observer Agent, is not an independent agentic evidence owner. A human-only owner approval is S3 parent mode, not S3*. The first party may purposely keep that mode; no feature is mandatory.

**Contributor / maintainer priorities:** NOT_STATED on an independent executive Observer. Original issue #1 (https://github.com/Hyper-AI-Lab/cyber-ai-team/issues/1) concerns rights-before-ingestion, not proof of this need; user proposal is internal OpenSiro research, not official maintainer interest.

## 2. Source-pinned baseline and parallel native Track A / on-top Track B

**Original native workflow:** [backend/src/cyber_team/operations/executive.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/executive.py) run_executive_cycle takes a source snapshot, proposes actions, calls _run_observer_review when enabled, computes observer_blocks from review.unresolved_objections, then calls _execute_action using _impact_gate before durable action record. _run_observer_review runs fixed checks, not AgentManager.invoke_agent. ObserverReview is persisted and referenced in operation graph. Policies are independently checked in [backend/src/cyber_team/operations/action_policy.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/action_policy.py).

**Closest existing solution:** Keep the deterministic Observer and require owner approval for unsafe/high-impact operations. This is already an operational source-native control, and adding further deterministic checks may be sufficient for many tasks without autonomous S3*.

**Relevant original Issues/PRs:** Original GitHub Issues list at 2026-11-22 showed only https://github.com/Hyper-AI-Lab/cyber-ai-team/issues/1 (source-rights evidence before content actions; ISSUE_ONLY). Original PR listing returned empty, so no conflicting PR HEAD exists in this bounded readback. No claim of maintainer endorsement. Existing first-party source is SHIPPED and is compared by exact immutable commit; no external PR effects performed.

| Required C link or outcome | Track A current coverage | Track B minimum missing native integration | Falsifier |
| --- | --- | --- | --- |
| Separate evidence-based judgment on executive action | [backend/src/cyber_team/operations/executive.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/executive.py) deterministic review, [backend/src/cyber_team/agents/manager.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/agents/manager.py) role invocation elsewhere | Optional independent read-only AgentManager invocation at review seam, immutable snapshot/action IDs, separately retrieved evidence, typed accept/object/escalate | Same AgentManager content simply repeats proposer self-claim or equivalent native independent reviewer already exists |
| Enforced objection and later recheck | ObserverReview persisted and unresolved_objections feeds observer_blocks before _execute_action | validate reviewer schema, authority and age; record evidence hashes; ensure opted-in enforce errors hold only scoped work; re-review corrected action in future cycle | Review says object but action executes; stale receipt releases a different action; caller can bypass review |
| Parent rights and baseline | ActionPolicy plus owner domain controls apply; deterministic Observer is default | reviewed decision may only further restrict within existing owner rights; default compatibility | Reviewer grants unauthorized spend or changes unconfigured default |

**On-top distinctness:** Not a new reviewer label or generic application of an LLM: the decisive owner must assess independent current evidence; backend validation ties the verdict to the exact pending executive action, and a negative finding must affect actual subsequent execution. Current code already supplies object persistence and hold so B should not recreate them.

**Source ambiguity / rights blockers:** Underlying primary evidence readers and customer data sensitivity require an executable access design; original tests have not run. Read-only evidence permissions and replay/freshness behavior have not been proved. These are NEEDS_EVIDENCE research work, not proof that the architecture is impossible. Parent original LICENSE/CONTRIBUTING permit lawful prototype research, not public original Issue/PR without OpenSiro consent.

## 3. Minimal complete S3* first-party C construction

**Required property:** In the supported first-party executive cycle, a developer can compose a distinct autonomous reviewer with scoped primary evidence, bounded lawful alternatives, binding correction/hold effect and feedback into later operation. A bare role manifest, model scoring, logging hook or human approval does not constitute the S3* constructor.

| Necessary native component or port | Existing file/API and evidence | Smallest proposed edit / integration | Legitimate owner, effect and return |
| --- | --- | --- | --- |
| Reviewer invocation with independent primary evidence | [backend/src/cyber_team/agents/manager.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/agents/manager.py) invoke_agent exists; [backend/src/cyber_team/operations/executive.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/executive.py) ensure_observer_agent configures read-only tools but _run_observer_review is fixed | Opt-in review adapter in _run_observer_review, supply exact snapshot/action/evidence bindings and separate read-only tool scope, validate structured verdict | Reviewer decides accept/object/escalate; cannot authorize side effects |
| Review-to-hold and re-evaluation binding | [backend/src/cyber_team/operations/executive.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/src/cyber_team/operations/executive.py) already has ObserverReview, observer_blocks, _impact_gate and next cycles | Map only validated current objection onto existing observer_blocks; stable provenance and scoped age/run IDs; enforce-mode failure cannot auto-accept; permit corrected evidence on later cycle | Executor enforces holds; owner review available; after correction subsequent authorized execution may proceed |

**Architectural C-sufficiency argument:** Compare option A (current fixed checks + owner approval), option B (model only annotates an ObserverReview: insufficient because no binding), option C (selected: separately evidence-grounded decision drives existing observer_blocks/operation graph and later recheck), and option D (external reviewer orchestration: requires unproven in-flight binding). C is a potentially complete first-party S3* path with minimal new ports because the executive already blocks on severe Observer objections, but it depends on source-verified independent evidence and reviewer-failure handling. Falsify C if no honest distinct observation, no secure decision association or no safe return to later work can be shown. This is an unimplemented design, not current C.

**Explicit non-goals:** No change to parent S5, no S3 automation of owner's pause/takeover, no default-on model mandate, no extra multiagent scheduler, no claims about safety certification or production reliability, and no externally published issue or PR.

**Implementation dependency graph:** P1 source/rights and exact action/evidence binding → P1 deterministic reviewer schema/permission/replay/timeout tests → optional P0 separate model-owned judgment integrated into existing executive hold and durable audit → native matched baseline and independent source review.

## 4. Priorities, optional alternative and stopping rules

**P0 and P1:** P0 is the smallest complete opt-in S3* decision-to-hold/recheck path. P1 establishes that primary evidence is available independently and lawfully, reviewer identity differs from proposer, evidence is fresh and action scoped, parent approval wins, enforce-mode failures hold, and simple baseline behavior is preserved.

**P2:** NONE for this experiment. S2 cross-domain mutual adjustment is separately deferred after whole-repository screening; not a second S3* requirement.

**Alternative path:** Current rule-based checks plus owner takeover may be preferred when disputed evidence is too sensitive or model judgment adds false blocks, latency or extra costs; preserving parent governance is valid.

**Stop:** A first-party independent corrective audit already shipped with exact same authority and later-operation return; reviewer cannot obtain distinct evidence; action can escape hold; parent rights or evidence access prohibit the proposal; or negative tests disprove the construction. Lack of a maintainer request or unmeasured ROI alone is not an architectural veto.

## 5. Future source-native acceptance — derive tests, do not copy a matrix

**Native test commands and entry points:** [CONTRIBUTING.md](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/CONTRIBUTING.md) recommends cd backend && pip install -e ".[dev]" && pytest; relevant pinned test files: [backend/tests/test_executive_company_os.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/tests/test_executive_company_os.py), [backend/tests/test_supervisor_review.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/tests/test_supervisor_review.py), [backend/tests/test_action_policy_and_workflow_compiler.py](https://github.com/Hyper-AI-Lab/cyber-ai-team/blob/525401e40f34863cc7f4d3b053d437ce7709912f/backend/tests/test_action_policy_and_workflow_compiler.py). NOT_RUN for this proposal, no test success reported.

**Positive functional closure:** Given a frozen executive action and conflicting independent company record, an opt-in read-only reviewer returns evidenced object, the executive persists review and blocks that action before effect, an owner can inspect proof, and subsequent corrected evidence is re-reviewed before a later authorized action. Show role really selected alternative, not fixed regex.

**Independent alternative (where applicable):** The same proposer output with independently corroborating primary evidence yields accept and proceeds within ordinary impact policy; alternative choice must come from reviewer discretion, not a threshold hardcode.

**Negative authority and compatibility (where applicable):** Unconfigured default continues fixed checks. Enforce mode: reviewer missing, stale, malformed, unauthorized, forged or timed out yields no autonomous approval; scope/replay mismatches cannot unblock unrelated action; parent permanent gate remains impossible to override. Review failure is visible and does not fabricate success.

**Matched native alternative:** Run identical fixtures against current deterministic reviewer and proposed opted-in reviewer, compare erroneous action release, false holds, turnaround after correction, replay mistakes, model/tool expense; benefit/cost NOT_MEASURED.

| Proposed native case (NOT_RUN) | Source-supported setup | Expected effect and return | Stop |
| --- | --- | --- | --- |
| Evidence contradiction | Executive test fixture with separately scoped read-only evidence and fixed action | Object + durable exact hold + later corrected recheck | Action executed before hold, reviewer read only self-report |
| Evidence corroboration | Same action with verified primary evidence | Accept but still obey impact/owner gates | Auto-authorization of restricted action |
| Missing/stale reviewer | Explicit enforce mode + invalid evidence hash, timeout or absent identity | Durable no-release and clear escalation; default mode unchanged | Silent acceptance or irreversible side effects |

## 6. Proposal verdict, falsification, evidence ownership and handoff

**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE
**Primary falsifier:** Existing equivalent autonomy, no separable evidence, wrong identity, ineffective objection, stale release, irreversible action before review or owner gate bypass.
**Validation state:** NOT_RUN for native tests, schema and external deployment; local receipt/template checks only establish document structure.

**Ownership of truth:** Profile defines VSM; Skills defines states; Index owns historic acceptance and any future reassessment; original maintainers control implementation and product priorities; [roadmap.md](roadmap.md) owns proposal/priority/pins; [issue.md](issue.md) is the human-readable derived decision.

**Cost status:** NOT_MEASURED. Proposed engineering benefit is unvalidated.
**Next permitted action:** Prepare independent evidence-contract tests within same original under proper permissions, no product implementation or third-party publication without separate approval; Human backlink [issue.md](issue.md); canonical [roadmap.md](roadmap.md).

No original Issue/comment/PR, public fork Issue/PR, product code, autonomous policy grant or Index grade is authorized. **AI disclosure:** Prepared with AI assistance and without running original native tests.

**Human backlink:** [issue.md](issue.md).
**case receipt:** [roadmap.md](roadmap.md).
