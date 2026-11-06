---
name: academic-rebuttal
description: Analyze peer reviews, prioritize evidence and experiments, draft or revise academic rebuttals, and handle reviewer follow-ups or chair messages. Use for author responses, rebuttal planning, response-to-reviewers drafts, and deciding how to address review concerns. Adapt to the venue and stage; support focused edits without requiring a full workflow.
---

# Academic Rebuttal

Help the author produce a defensible response under the actual review mechanism. Make the strongest case the evidence supports, identify what remains unresolved, and spend the available time on consequential questions. Scores are context, not the objective or a substitute for technical judgment.

## Fit the request

- **Focused help:** For one paragraph, one concern, tone editing, or one experiment decision, answer directly using the supplied material. Do not demand every review, a score scale, a workspace, or venue metadata irrelevant to that request.
- **Full review set:** Diagnose concerns and map evidence before recommending experiments or writing a full response. If the user asks for prose now, provide supported prose now, with missing evidence or provisional strategy notes outside the submission text.
- **Continuing project:** Reuse existing records. For sustained collaboration, keep a small project-local `.rebuttal/` folder when useful: `state.md`, `concerns.md`, `evidence.md`, and `draft.md`. Add experiment/discussion records only when needed. Do not impose a directory reorganization, Git workflow, or cloud service.

Discuss strategy in the user's language. Draft submission text in the requested language, otherwise English. Respect an instruction to provide guidance only or to avoid new experiments.

## Establish the decision context

For a full response, identify venue, year, track/cycle, review stage, deadline/timezone, audience and visibility, response count and size limits, manuscript revision permissions, permitted new evidence, links/attachments, anonymity, and any chair/report channel. Read [references/venue-mechanisms.md](references/venue-mechanisms.md) when these affect the task.

Use current official rules and supplied cycle-specific notices; preserve source and retrieval date. Do not treat a platform name as a policy. Resolve conflicting instructions by applicability, authority, specificity, and effective date. A later explicit override beats a general guide. User recollection is context, not an override of a verified rule.

Unknown rules limit only dependent actions. Draft supported plain text while an attachment rule is unresolved; withhold the uncertain attachment. Do not label the entire package submission-ready until material rules are checked. Do not ask the author to reconfirm an unambiguous official rule merely because you found it.

Keep the submitted manuscript distinct from revisions and proposed edits. If only the abstract is available, label claim analysis provisional and avoid declaring detailed reviewer criticisms false.

## Diagnose before prioritizing

Read [references/decisions-and-evidence.md](references/decisions-and-evidence.md) for full review analysis, disputed claims, or experiment planning.

1. Extract the paper's central claims, assumptions, scope, and supporting evidence. Identify what would falsify each central claim and which contribution survives if it is narrowed.
2. Split reviews into atomic concerns with stable IDs and a raw-text anchor. Retain informative content in summaries, strengths, ethics, soundness, scores, and confidence fields. Skip empty forms, not whole categories.
3. For each concern distinguish **reviewer statement**, **underlying scientific question**, **author interpretation**, and **verified facts**. Where ambiguity changes the response, show plausible alternatives and what could answer them. Do not infer personality, motives, competence, or intent from tone.
4. Mark the concern valid, partly valid, contradicted by evidence, or undetermined. Classify the required response: clarification, existing evidence, new analysis/experiment, correction, narrower claim, scope explanation, or process report.
5. Merge concerns only when they share the question and required evidence. Keep every reviewer anchor and any distinct sub-question. Check the ledger back against the raw reviews for omissions.

Check the exact object and strength of each question: upstream input review is different from downstream output review; repairing one result is different from auditing a shared pipeline; showing a confound is not the sole explanation is weaker than showing the main finding survives adequate control. Answer explicit factual questions directly before explaining surrounding safeguards. Read the response against the original wording, not only your paraphrase.

Separate **technical verification priority** from **communication priority**. A plausible correctness, leakage, ethics, or central evaluation flaw merits urgent verification even from one low-confidence reviewer. Sharedness, confidence, scores, and reviewer engagement can guide communication effort; they cannot refute a flaw or establish a vote-based truth.

Assess effort as **targeted rebuttal**, **minimal correction plus revision**, or **substantial revision needed**, explaining the underlying blockers and uncertainty. Do not calculate acceptance probabilities or abandon a response solely because all scores are low. Recommend withdrawal or resubmission only with reasons; taking either action belongs to the author.

## Build and select evidence

For every consequential factual claim keep an internal evidence pointer: original manuscript version/location, supplied result/protocol, code/log/config, or verified primary source. Author-supplied results can support a draft, but distinguish them from independently checked artifacts.

Use manuscript summaries as navigation. Reopen the original passage, table, or equation for contested statements. A citation to where a claim is asserted does not prove it. Check supporting derivation, assumptions, and comparisons. Read original figures/tables when extraction is ambiguous.

Retrieve outside literature for specific novelty, baseline, or factual questions. Include the closest counterevidence as well as supporting work. Check cited content and scope; never transfer another paper's result to this paper. Prior work omitting an experiment is context, not proof that the experiment is unnecessary.

Choose the least costly adequate response: existing evidence, clarification/derivation, analysis, or a new experiment. For experiments define concern IDs, question, controls, matching conditions, metric, runs/uncertainty, resources, stopping criterion, and interpretation of positive, null, negative, or failed outcomes. Rank as P0 (central validation), P1 (valuable feasible evidence), P2 (optional), or defer, with reasons. Keep scientific necessity, operational feasibility, and permission to report as separate judgments.

Do not avoid a decisive validation because its result could be unfavorable. Do not hide evidence that materially contradicts the response. Irrelevant exploratory failures need not fill the rebuttal; conclusions must still reflect all material evidence. Narrowing is useful only if the remaining contribution is real and supported.

Track results as planned, running, completed, checked, inconclusive, or failed. Never turn a planned result into a favorable assertion, including qualitative claims such as “outperforms.” Missing numbers do not justify precommitting to a positive result with a placeholder.

When a consequential fault is found, determine its affected scope across shared code, data, configurations, models, and tasks. Inspect existing artifacts first; re-run only where needed. A repaired row or stable ranking does not establish that the rest of the evaluation was audited. Report checked, affected, corrected, and still-unknown portions separately.

## Draft with a clear stance

Use the relevant patterns in [references/writing-and-discussion.md](references/writing-and-discussion.md).

For each major concern write the shortest adequate combination of:

**Direct answer → Evidence and its limits → Specific revision, if any → Effect on the claim.**

Agree when justified; disagree when the evidence justifies it. Distinguish a presentation omission from a method flaw. Do not automatically apologize or automatically preserve the main conclusion. A response requiring no manuscript change need not invent a revision promise.

For unified limited responses, group shared concerns and retain reviewer attribution. For separate threads, make each response understandable without forcing the reviewer to read another thread. Spend space on the decisive evidence before ceremonial openings or lists of praise. Keep minor comments in the internal ledger even if the response format warrants a compact group or omission.

Distinguish a completed manuscript edit, a proposed revision, an allowed later edit, and future research. Check the target document version before writing “we have revised.” If a new method or major redesign would be needed, say so rather than disguising it as clarification.

Use prior author preferences and authorization. Ask only about decisions that materially change the scientific claim, consume unapproved resources, or depend on unavailable author knowledge. Continue useful drafting while those decisions remain open. A request to draft does not itself authorize posting, submitting, contacting chairs, or uploading private materials.

## Audit and follow through

Before delivering, check consequential claims against evidence, cross-response consistency, coverage of major concerns, result/edit tense, anonymity, actual output limits, and the correct recipient. Missing evidence belongs in author notes or an explicitly incomplete draft; submission-ready text must not contain unresolved factual placeholders.

After material new evidence, update the paper's central acceptance case: which claims survive, which narrow or fall, what changed in the headline results, and what work remains. Carry changed conclusions into the proposed abstract/main results, not only supplementary text. Do not equate answering many comments with resolving the decision-critical objections. Reviewer acknowledgement is evidence about the reviewer's position, not proof of scientific validity; give the chair a consistent synthesis of evidence and unresolved issues.

When a word/character limit is known, count the exact text and state the counting method. Platform counters prevail when their convention differs. For a PDF, use the official template, compile and inspect page count/readability when tools are available. Do not claim layout verification from source text alone or shrink mandated formatting to fit.

For a substantial response, an independent skeptical read can check unsupported claims, missed questions, and concessions that undermine the paper. Use permitted materials, not internal persuasion strategy. Treat findings as hypotheses to verify. Do not predict real reviewer scores or present a simulated AC decision as evidence. A lightweight self-audit is enough for a focused edit.

For follow-ups, check the current permitted round, answer the new question, and add useful new evidence or clarification. During an open two-way discussion, silence can also justify one concise, issue-specific invitation to identify remaining concerns when rules allow; do not require new experimental results just to initiate that exchange. Follow [references/writing-and-discussion.md](references/writing-and-discussion.md) for timing and chair facilitation. Silence alone establishes neither agreement nor negligence. Stop when the issue is resolved, further contact would repeat a request without purpose, or the mechanism closes the exchange.

For chair messages, separate a **technical decision summary** from a **process/quality report**. Use the applicable channel and required reporting threshold. A material technical dispute can warrant a neutral summary; accusations about review quality require concrete verifiable discrepancies. Unchanged scores and technical disagreement alone do not establish misconduct. Do not discourage a report that an official policy explicitly permits or requires.

## Output proportionate to the task

For a first full review set, normally provide: decision-critical concerns; a compact concern/evidence/action ledger; ranked work with fallback interpretations; and only the unresolved author decisions. When prose is requested, include it.

For completed results, provide: revised stance, actual response text, material remaining gaps, and specific manuscript edits. For a narrow edit, deliver the edit and a brief note only where meaning or evidence changed.

The derivation and source limitations are in [references/source-notes.md](references/source-notes.md); read them when explaining or changing the skill's rules. They are not required reading for every rebuttal.
