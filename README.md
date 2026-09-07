# Biomedical English Writing

An AI-agent skill for drafting and polishing biomedical manuscript sections while preserving scientific meaning, evidentiary logic, and the author's intended rhetorical strength.

## Capabilities

- Abstracts, introductions, results, discussions, and methods
- Figure legends and figure-level argument flow
- Acknowledgements, author contributions, competing interests, funding, patient consent, and ethics approval
- Biomedical terminology, journal-convention, and claim-strength checks
- Chinese-to-English scientific writing and optional Chinese translation

## Import

### Claude Science

Open **Settings → Skills → Import from GitHub** and enter:

```text
https://github.com/zachliu689/biomedical-english-writing
```

Claude Science discovers the skill at:

```text
skills/biomedical-english-writing/SKILL.md
```

### OpenAI Codex

Install the repository path:

```text
skills/biomedical-english-writing
```

Then invoke it explicitly with:

```text
$biomedical-english-writing
```

## Suggested Input

Provide the manuscript section, draft or notes, study context, target journal when known, and any figures or results needed to verify the scientific logic. For Results and figure legends, provide one complete figure with panel labels, sample information, statistics, and scale-bar lengths where applicable.

## Main Output

The skill returns manuscript-ready biomedical English, preserves the supplied evidence boundary, and reports material ambiguities or unsupported details separately instead of inventing them.

## Repository Layout

```text
skills/
└── biomedical-english-writing/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    └── references/
        ├── editing-standard.md
        ├── end-matter-guide.md
        ├── evidence-and-research.md
        └── section-guides.md
```
