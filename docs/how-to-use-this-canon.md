# How to Use This Canon

*Stunspot's Guide to Sales Prospecting Strategy* is built for model-facing use first. Human readers can read it directly, but the repository is optimized for AI/RAG ingestion, retrieval accuracy, source traceability, and durable commercial terminology.

The practical goal is to give an assistant a disciplined way to reason about prospecting: not as a pile of contacts and cadence templates, but as a system for detecting organizational pressure, validating commercial claims, mapping buyer-systems, reducing risk, and diagnosing outbound failure.

## Choose the Right Entry Point

| Situation | Start With | Why |
|---|---|---|
| You want the model to understand the whole canon with manageable file count | `knowledge-packs/compiled-packs/` | Five grouped volumes preserve sequence while keeping upload count low. |
| You need precise retrieval or report-specific citation | `knowledge-packs/by-report/` | Each report remains isolated, easier to target, cite, refresh, or replace. |
| You need one file for archive, local search, or a strong long-context system | `knowledge-packs/omnibus/` | Full corpus in a single bundle. Convenient, but heavier. |
| You are a human trying to orient quickly | `docs/canon-map.md` | Explains the report sequence and conceptual dependencies. |

## Recommended AI/RAG Workflow

1. **Upload the compiled packs first.** They are the default format for AI Projects, RAG collections, NotebookLM-style tools, and most long-context workspaces.
2. **Add the source reports only when needed.** Use `knowledge-packs/by-report/` for report-level citation, targeted edits, or systems that perform better with smaller retrieval units.
3. **Use the omnibus selectively.** It is best for archival import, local search, full-corpus reading, or models with strong long-context handling.
4. **Tell the model the directory policy.** `docs/` is navigation and guidance. The corpus lives in `knowledge-packs/`.
5. **Preserve uncertainty.** The canon repeatedly distinguishes events, signals, evidence objects, confidence bands, commercial claims, and action thresholds. Do not let the model flatten those distinctions into “this account is ready to buy.”
6. **Ask for source-aware outputs.** Require the model to name which report or concept supports each major claim when making strategic recommendations.

## Suggested Model Instruction

Use this block when loading the canon into an AI workspace:

```text
You are working with Stunspot's Guide to Sales Prospecting Strategy as a model-facing knowledge canon.

Treat the corpus as structured commercial reasoning doctrine, not generic sales advice. Preserve its core distinctions: event vs. evidence object vs. signal candidate vs. signal-bearing event vs. commercial claim vs. actionable opportunity claim; account vs. buyer-system; budget availability vs. budget legitimacy; activity metrics vs. pipeline truth.

When answering, reason from the canon’s causal model: organizational pressure, capital posture, signal reliability, account reality, stakeholder incentives, procurement/risk gates, message engineering, channel constraints, commercial memory, handoff integrity, funnel economics, and failure diagnosis.

Prefer evidence-backed, uncertainty-aware recommendations. Name relevant reports or concepts when useful. Do not invent source files, directory paths, or unsupported claims. The source-report corpus lives in `knowledge-packs/by-report/`; compiled upload packs live in `knowledge-packs/compiled-packs/`; the omnibus lives in `knowledge-packs/omnibus/`; `docs/` is only navigation and usage guidance.
```

## Human Reading Paths

### If you are designing an outbound strategy

Read:

1. [A — Market Systems, Organizational Change, and Demand Formation](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/a-market-systems-organizational-change-and-demand-formation.md)
2. [C — Signal, Evidence, and Commercial Epistemology](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/c-signal-evidence-and-commercial-epistemology.md)
3. [G — ICP Architecture, Segmentation Logic, and Market Prioritization](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/g-icp-architecture-segmentation-logic-and-market-prioritization.md)
4. [L — Prospecting Systems, Channel Strategy, and Sequence Architecture](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/l-prospecting-systems-channel-strategy-and-sequence-architecture.md)

### If you are interpreting intent data or trigger events

Read:

1. [C — Signal, Evidence, and Commercial Epistemology](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/c-signal-evidence-and-commercial-epistemology.md)
2. [E — Public Signals, Trigger Events, and Market Observation Systems](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/e-public-signals-trigger-events-and-market-observation-systems.md)
3. [F — Signal Interpretation, Pressure Detection, and Relevance Formation](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/f-signal-interpretation-pressure-detection-and-relevance-formation.md)

### If you are mapping enterprise deals

Read:

1. [D — Account Reality Models and Buyer-System Mapping](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/d-account-reality-models-and-buyer-system-mapping.md)
2. [H — Buyer Psychology, Decision Economics, and Behavioral Dynamics](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/h-buyer-psychology-decision-economics-and-behavioral-dynamics.md)
3. [I — Stakeholder Cartography, Consensus Formation, and Political Navigation](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/i-stakeholder-cartography-consensus-formation-and-political-navigation.md)
4. [J — Buyer Risk Mitigation & The Procurement Gauntlet](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/j-buyer-risk-mitigation-and-the-procurement-gauntlet.md)

### If you are improving message quality

Read:

1. [K — Message Engineering, Narrative Design, and Attention Economics](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/k-message-engineering-narrative-design-and-attention-economics.md)
2. [F — Signal Interpretation, Pressure Detection, and Relevance Formation](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/f-signal-interpretation-pressure-detection-and-relevance-formation.md)
3. [H — Buyer Psychology, Decision Economics, and Behavioral Dynamics](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/h-buyer-psychology-decision-economics-and-behavioral-dynamics.md)

### If you are diagnosing a broken prospecting system

Read:

1. [O — Conversion Systems, Funnel Economics, and Performance Analytics](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/o-conversion-systems-funnel-economics-and-performance-analytics.md)
2. [P — Failure Modes, Prospecting Pathologies, and Commercial Intervention Strategy](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/p-failure-modes-prospecting-pathologies-and-commercial-intervention-strategy.md)
3. [M — Commercial Data Infrastructure, DataOps, and CRM Continuity](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/m-commercial-data-infrastructure-dataops-and-crm-continuity.md)
4. [N — Epistemic Transfer & The AE Handoff Architecture](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy/blob/main/knowledge-packs/by-report/n-epistemic-transfer-and-the-ae-handoff-architecture.md)

## Usage Patterns

### Strategy Design

Ask the model to build a prospecting strategy from first principles:

```text
Using the Sales Prospecting Strategy canon, design an outbound strategy for [segment]. Start by identifying likely pressure domains and capital constraints, then define evidence sources, signal thresholds, buyer-system hypotheses, message frames, channel logic, CRM fields, and failure monitors.
```

### Account Research

Ask the model to separate facts from hypotheses:

```text
Using the canon’s commercial epistemology, analyze this account research. Separate raw observations, evidence objects, signal candidates, inferred commercial claims, alternative hypotheses, confidence level, missing evidence, and recommended next action.
```

### Message Engineering

Ask the model to translate evidence into buyer-safe language:

```text
Using the message-engineering chain, convert this account evidence into an outbound message. Include evidence, interpretation, pressure frame, stakeholder relevance, risk reduction, proof anchor, attention hook, and safe next action.
```

### Failure Diagnosis

Ask the model to avoid generic optimization:

```text
Using PROSP-P, diagnose this outbound performance problem. Begin with the observed symptom, identify the metric anomaly, map affected system layers, generate candidate pathologies, list diagnostic evidence needed, isolate probable root cause, and recommend controlled interventions with review windows.
```

## Source Traceability Rules

When using the canon in consequential work:

- Ask the model to cite report codes or file paths for major strategic claims.
- Preserve report names when summarizing extracted doctrine.
- Do not treat compiled packs as new sources; they are grouped copies of the source reports.
- Use source reports for report-level citation.
- Treat the omnibus as a convenience bundle, not a separate authority layer.

## Common Failure Modes

- **Trigger-event literalism:** treating a funding round, hire, layoff, tool install, or web visit as automatic proof of active demand.
- **Pipeline hallucination:** converting weak evidence into confident pipeline claims.
- **Account flattening:** treating the company as one rational buyer instead of mapping the buyer-system.
- **Budget confusion:** mistaking available funds for politically legitimate, approved budget.
- **Message decoration:** adding personalization without evidence-to-pressure translation.
- **CRM memory loss:** stripping uncertainty and evidence chains during handoff.
- **Metric theater:** optimizing visible activity while the underlying GTM system gets worse.

Use the canon to suppress these errors early. The goblin of false certainty is always hungry.
