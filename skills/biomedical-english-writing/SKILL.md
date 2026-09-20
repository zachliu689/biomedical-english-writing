---
name: biomedical-english-writing
description: "Draft or polish biomedical manuscript abstracts, introductions, results, discussions, methods, figure legends, and standard end-matter declarations with concise scientific logic, author-controlled rhetorical strength, journal conventions, terminology checks, and Chinese translation. Use for section-level biomedical English writing or editing; do not route ordinary translation, reviewer-response letters, or non-biomedical prose here. Enforces manuscript-wide abbreviation scope (abstract, main text, each legend and table as independent units), explicit per-panel sample sizes, and a pre-submission verification pass."
---

# Biomedical English Writing

Edit for scientific accuracy, logical force, conventional biomedical English, concision, and reader comprehension while preserving the author's intended message and rhetorical strength. Never invent results, methods, sample sizes, statistics, reagents, references, journal requirements, or compressed labels for relationships that can be stated directly.

## Author Style Profile

Use the shared rules in [references/editing-standard.md](references/editing-standard.md) and the section-specific rules in [references/section-guides.md](references/section-guides.md). For this author's additional scope, reporting, output, and naming conventions, read [references/author-profile.md](references/author-profile.md). Journal requirements override both the personal layer and general defaults.

## First-use Brief

On the first invocation in a manuscript workflow, give one short usage note, then proceed with the supplied material. State that the skill supports abstracts, introductions, results, discussions, methods, figure legends, Acknowledgements, Author contributions, Competing interests, Funding, Patient consent, and Ethics approval. Ask the user to identify the section and target journal when known.

For Results and figure legends, request one complete figure and its corresponding notes or draft per turn and recommend processing figures in numerical order. Do not request all figures at once unless the user prefers a batch workflow. For abstracts, introductions, discussions, and methods, request at least a rough Results draft or ordered result summary.

Recommend this manuscript sequence once per workflow: **Results + figure legends → Introduction → Discussion → Abstract → Methods → Acknowledgements → Author contributions → Competing interests → Funding → Patient consent → Ethics approval**. Do not repeat the brief on later turns in the same workflow.

## Intake

Infer information already supplied; ask only for missing items that affect the work.

1. Determine whether the task is **polishing** or **drafting**.
2. Determine the section: abstract, introduction, results, discussion, methods, figure legend, or end matter.
3. Obtain the passage, notes, data, or figure needed for that section.

For a new drafting workflow, also request the research field, target journal or representative target papers, article type, study objective, and available manuscript materials. Verify current journal requirements rather than relying on memory.

Use the section-specific intake and writing rules in [references/section-guides.md](references/section-guides.md). For results and figure legends, handle one figure plus its corresponding draft or notes per turn unless the user explicitly requests a broader batch.

For Results built around a multi-panel figure, inspect the complete figure and form an internal **figure argument map** before editing:

1. the overall question the figure resolves;
2. the specific role of each panel in answering that question;
3. what conclusion from one panel creates the need for the next panel;
4. the new subquestion or uncertainty resolved by that next panel; and
5. the innovation or comparative advantage established by each evidence module; and
6. the integrated conclusion supported by the full panel sequence.

Do not draft the panels as independent observations. If the role of a panel or the reason for its position cannot be determined from the figure and notes, ask the user rather than inventing the connection. The map is normally internal; show it only when the user requests an outline or when a substantive ambiguity needs confirmation.

For figure legends, inspect the supplied image for scale bars before drafting. If any scale bar is present, its exact physical length and panel mapping are mandatory inputs. When the user has not explicitly supplied or confirmed them, stop and ask for those values; do not guess the length, omit the scale-bar statement, or deliver a final legend until the information is provided.

For Acknowledgements, Author contributions, Competing interests, Funding, Patient consent, or Ethics approval, read [references/end-matter-guide.md](references/end-matter-guide.md) and collect only the missing mandatory information.

## Evidence Boundary

Classify every substantive statement before editing:

- **Direct result:** an observation measured by the study.
- **Conclusion:** an interpretation supported by the study's results.
- **Extension:** a mechanistic, translational, or clinical implication not directly tested.

Preserve these levels without automatically weakening the author's prose. Retain the user's intended degree of inference when it is scientifically arguable and supported by the stated evidence chain. Within defensible limits, prefer a clear, forward-moving conclusion over flat descriptions of isolated observations.

Do not insert defensive statements into the revised manuscript merely because a statistic, control, or validation detail is absent from the supplied material. Warnings such as `statistical comparisons were not available`, `did not independently establish`, or `should be interpreted cautiously` belong in a separate **Editorial notes** section unless the user asks to include them or omission would make the manuscript statement plainly false.

Correct the manuscript text itself only when there is a clear design-to-claim mismatch, such as cross-sectional association presented as causation, colocalization presented as functional mediation, a nonsignificant comparison described as statistically significant, or an in vitro observation presented as clinical efficacy. For debatable rather than clearly invalid claims, preserve the requested strength and do not volunteer a flatter alternative unless the user asks for claim calibration or the ambiguity materially affects scientific accuracy.

## Abbreviation Units and Scope

Treat the manuscript as a set of independently read units. Apply G13 in [references/editing-standard.md](references/editing-standard.md) to definitions and consistency within each unit.

1. **Title and headings:** avoid abbreviations. If one is unavoidable, define it in the heading or in the first sentence that follows.
2. **Abstract:** its own unit. Define at first use. A term abbreviated in the abstract must be expanded again at first use in the main text.
3. **Main text:** Introduction, Results (including subsection headings), Discussion, and Methods form one contiguous unit. Define each abbreviation at its first occurrence in that flow and use it consistently thereafter; do not redefine it in a later section of the same unit.
4. **Each figure legend:** its own unit, and its terminal abbreviation list is a glossary for the whole figure, artwork included.
5. **Each table, with its footnotes:** its own unit.
6. **Each supplementary figure legend:** its own unit.

Journal requirements override this default unit model. Gene and protein symbols are nomenclature rather than abbreviations; apply G12 for their typography and naming.

## Research and Skill Coordination

Read [references/evidence-and-research.md](references/evidence-and-research.md) whenever terminology, references, target-journal requirements, introduction/discussion writing, or claim verification is involved.

When available and genuinely useful:

- Use `academic-research-suite` for literature discovery, synthesis, and citation verification.
- Use `paper-spine` only when the user requests an end-to-end manuscript workflow or formatted paper artifact.
- Use `scipilot-figure-skill` when the task expands from interpreting a supplied figure to choosing or producing a scientific data visualization.

Before using another skill, read its `SKILL.md` and follow its routing rules. Do not invoke extra workflows merely because they are available.

- Style audits, corpus sampling, voice selection, and collocation checks: read [references/corpus-and-style-audit.md](references/corpus-and-style-audit.md) when the relevant mode is requested or triggered.
- Per-author working conventions for reporting, output, and naming: read [references/author-profile.md](references/author-profile.md) when working for this author.

## Editing Standard

For every passage, apply [references/editing-standard.md](references/editing-standard.md). Prioritize:

1. correctness and preservation of meaning;
2. evidence strength and figure/data support;
3. English information flow and paragraph logic;
4. conventional terminology, natural collocation, nomenclature, abbreviations, and journal consistency;
5. concise expression of the same scientific content.

Apply this sequence before accepting a revision: **scientific meaning → evidentiary relationship → information focus → conventional wording → grammar and collocation → compression**. Use G5-G9 and the relevant section rules for figure logic, transitions, and compression; use G10-G17 for wording, collocations, terminology, symbol typography, abbreviation scope, voice, clause structure, and group naming. Reject any compression that weakens clarity, hides direction, invents a label, or reduces a supported conclusion's force.

## Pre-submission Verification

Run the applicable checks in [references/editing-standard.md](references/editing-standard.md) and [references/section-guides.md](references/section-guides.md) before delivering any draft or revision. This checklist routes to the detailed rules instead of restating them.

1. **Evidence and logic:** apply G1-G8 and the relevant section rules; ensure every comparison names its referent and every inference has an identifiable evidentiary basis.
2. **Language and structure:** apply G9-G17, including sentence-pattern variety, collocation verification, terminology consistency, symbol typography, clause structure, and group naming.
3. **Values and placeholders:** apply G4 and G4a; verify every number and keep every unresolved value visibly marked and listed as outstanding.
4. **Abbreviation scope:** apply G13 and the unit model above; check the abstract, main text, each legend, each table, and supplementary legends independently.
5. **Section-specific delivery:** run the relevant A/I/R/D/M/F rules, including figure-legend sample sizes, symbol keys, statistics placement, and ending order.
6. **Figures and quantified images:** cite representative images together with their quantification panels when both support the reported endpoint, and confirm that prose, artwork, and legend agree.

## Default Output

Lead with the finished manuscript-ready text. Do not make a sentence-by-sentence Markdown revision table the default; it adds length and delays the usable output. Provide such a table only when the user requests tracked reasoning, when several meaning-changing edits require confirmation, or when teaching the edits is part of the task.

Default order:

1. **Complete revised English passage**
2. **Chinese translation** when the source is Chinese/mixed-language or the user requests it
3. **Editorial notes**, only for material evidence risks, missing inputs, terminology issues, or claim-calibration alternatives explicitly requested by the user

Keep editorial cautions outside the manuscript-ready passage. For non-abstract sections, mark only claims that genuinely need references and recommend no more than three well-matched references per claim. Do not insert invented citation numbers. Abstracts normally omit citations unless the target journal requires them.

If the user explicitly requests only a clean version, tracked changes, a journal-specific format, or another output shape, follow that request while retaining the same scientific checks.
