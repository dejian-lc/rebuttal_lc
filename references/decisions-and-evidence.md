# Conditional decisions and evidence

## When sources disagree

Use this order: scientific validity and accurate reporting; applicable venue rules; adequacy of evidence for the claim; resource constraints; concise communication. Tone or perceived persuasiveness cannot override the first three. Rules constrain what may be submitted, not whether a scientific concern is true.

### Requested experiment versus justified disagreement

Ask which claim the requested experiment tests. If it is central and the current evidence is insufficient, validate it when feasible. If the baseline assumes privileged inputs or a different task, explain the mismatch and propose a controlled comparable test. If the manuscript overclaimed across that mismatch, correct the claim too. If the experiment is redundant, show the existing evidence. If it is informative but infeasible, admit the residual uncertainty; infeasibility does not resolve the concern.

Do not accept every experiment request or reject it solely as out of scope. A reviewer can reveal a missing control without proposing a practical protocol. “Orthogonal” alone does not establish that a comparison is irrelevant. Existing code does not guarantee a baseline can be reproduced fairly before the deadline.

### All scores low versus investing in rebuttal

Read the semantic scale and each rationale. Distinguish a common factual error from independent objections to validity, novelty, and significance. Correct a cheap, material error even in a weak review set. When evidence requires major redesign, prioritize a concise accurate response and a revision plan. A positive reviewer is useful communication context, not a necessary condition for making a response worthwhile.

Keep technical urgency independent of popularity: three positive reviews do not offset a reproducible leakage flaw. No numerical viability score is justified without a calibrated model and applicable data; qualitative scenarios are usually more useful.

### Reviewer versus decision-maker

Each reviewer needs an answer to their specific question. The chair needs a compact account of which decision-relevant claims remain supported and which objections remain open. Design both views from the same facts. Do not make contradictory commitments in separate threads. At rolling review, distinguish review quality and meta-review from the later venue commitment decision.

### Concession versus contribution

Write the scope before and after the correction. Identify what evidence supports the residual contribution and why it still matters. If nothing central survives, recommend substantive revision rather than reassuring language. A new model, assumption, or evaluation protocol cannot silently replace the submitted one.

### Other reviewers versus evidence

Positive reviewer comments establish only that someone expressed that view. Use accurate attribution to orient a summary where helpful; resolve disagreement with definitions, comparisons, results, or derivations. Avoid interpreting unrelated compliments as consensus. Preserve qualifications in paraphrases.

### Historical success rates versus this review

Observed writing features can guide readability: an equation question needs a derivation, an under-specified realism objection needs clarification. Do not label a person “dismissive” or “easy to persuade.” Historical correlations between tactics and outcomes may reflect initial paper quality, initial scores, selection into discussion, venue differences, and outcome definitions. Without provenance and validation, neither cluster rates nor effect sizes estimate this paper's probability or a tactic's causal effect. Successful example replies can teach organization, not supply this paper's facts.

## Minimal concern record

Use a compact list or table as appropriate. Each consequential record needs:

- ID and reviewer/source anchor;
- literal concern and scientific question;
- affected claim;
- validity status and uncertainty/alternative reading;
- technical severity and communication priority, explained separately;
- existing evidence and missing evidence;
- chosen response and intended scope;
- current state and dependencies.

“Resolved by author analysis” and “acknowledged resolved by reviewer” are different states. Do not overwrite original concerns after follow-ups.

## Question-to-answer alignment

Preserve the requested object, stage, population, and strength of conclusion. For example, evidence about final-output inspection does not answer whether intermediate inputs were reviewed; a single-system repair does not answer whether a shared evaluation path is reliable across systems. Start a yes/no procedural question with the established yes/no/unknown answer, then explain supporting procedures. Do not call an issue merely documentation-related before establishing the underlying procedure exists.

For a confound, distinguish evidence that rules out one exclusive explanation from evidence supporting the intended construct. Above-chance performance or matching one nuisance factor may leave other shortcuts. Compare like-for-like populations and metrics; changing the test set can change difficulty as well as the confound. Rank stability establishes comparative stability, not measurement validity. Label which stronger claims remain untested.

## Fault scope and claim updates

For a material discovered fault, trace shared dependencies and identify the full plausible exposure. Prefer an audit of existing outputs, logs, configurations, and sampled manual checks before assuming full re-execution is necessary. Define validity checks in a task-appropriate way; distinguish parseability, instruction compliance, and semantic correctness. Record audit coverage and unresolved portions. A passed syntax check is not a correctness guarantee.

Maintain a compact claim-change record after consequential evidence: original claim; new result; supported revised claim; changed headline/table/abstract; remaining uncertainty; reviewer position if explicitly stated. Reassess whether the residual contribution warrants the requested publication claim. New work is not intrinsically disqualifying, but corrections can expose missing validation that requires substantial revision. Neither bury changed conclusions nor claim every additional analysis must have been required in the original submission.

## Evidence and experimental protocol

For evidence preserve artifact/version/location, what it supports, and what it does not establish. For a result record dataset/split, metric direction, controls, data/backbone/training/tuning/selection budget, hardware when material, seed or sample count, and uncertainty actually reported. Do not require invented runs or a universal number of seeds.

An experiment candidate should say:

```
Question and concern IDs:
Minimum adequate protocol and controls:
Assets, owner, estimated resource/time range:
Stopping criterion independent of a favorable outcome:
Positive / null / negative / invalid-run interpretations:
Reportability under current rules:
Fallback if incomplete:
```

Don't optimize many seeds/configurations and report only a favorable subset as confirmatory evidence. Identify exploratory selection, tuning on test data, unequal budgets, and failed reproductions. A failed baseline run is not evidence that the baseline is inferior. A small gain with overlapping uncertainty is not automatically significant or insignificant; use a suitable analysis and describe limits.

External citations must be checked against the source; retrieved abstracts only support abstract-level statements. A compressed manuscript or generated literature summary is an index, not a primary source. In novelty disputes record the actual delta in assumptions, formulation, guarantees, capability, or evidence and why it matters; different names and combinations do not by themselves establish novelty.

## Time allocation and stopping

Rank validation of central claims first; then work that can resolve major questions with reliable evidence before the deadline; then optional polish. Reserve time to analyze and write. Do not prescribe a fixed five-day window or fixed percentage allocation. Stop adding experiments when additional work would jeopardize validation, accurate reporting, or timely response. Keep an explicit unresolved state instead of implying a deferred experiment solved the concern.
